# CLAUDE.md — CIPHER 项目
## Claude Code 专用配置文件

---

## 项目是什么

CIPHER 是一个 BaZi（八字）人格分析 Web App，定位"东方MBTI"。
用户输入生日 → 排盘 → 输出五行分布+人格分析+技能树+神煞+AI个性化路径分析 → 分享卡片。

---

## 技术栈

| 层 | 技术 |
|----|------|
| 前端 | 单 HTML 文件（index.html），纯前端，无框架 |
| 排盘库 | lunar-javascript@1.7.7（CDN引入）|
| 分享卡片 | Canvas API → PNG 下载 |
| AI生成 | Claude Sonnet 4.5 via OpenRouter，经 Cloudflare Worker 代理（备援：DeepSeek）。Worker 端：8步引擎 + 5道Gate + 11份规则内嵌 + 中文清洗 + 确定性 Punchline |
| 部署 | Cloudflare Pages（GitHub main 分支连接，推送自动部署）|
| 域名 | cipher-bazi.pages.dev |

---

## 文件结构

```
/
├── index.html          ← 唯一前端文件（所有HTML/CSS/JS都在这里）
├── CLAUDE.md           ← 本文件
└── .github/            ← 如有
```

**Cloudflare Worker 代码不在本仓库。** Worker 通过 wrangler CLI 单独部署。Worker URL 硬编码在 index.html 里。

---

## 我是谁

Shadow（Sam Ho）。44岁财务经理。**不是程序员**（有CS学位但18年没写过代码）。

请遵守以下规则：
1. **每次修改前先说明改什么、为什么。** 用简单语言。
2. **不要一次改太多。** 一个功能一个 commit。
3. **改完后测试说明。** 告诉我怎么验证改动是否成功。
4. **遇到技术选择给两个选项+推荐。** 不要自作主张。
5. **不要自行增加未被要求的功能。**

---

## 部署流程

```
改代码 → git add . → git commit -m "描述" → git push → Cloudflare Pages 自动部署（约30秒）
```

部署后访问 cipher-bazi.pages.dev 验证。

---

## 工程 Runbook（Claude Code 专用）

> 2026-06-04 起，系统由**两个组件**组成，部署方式不同：

### 组件与路径
| 组件 | 路径 | 部署方式 |
|------|------|---------|
| **前端** | `cipher-bazi/index.html`（本仓库）| `git push` main → Cloudflare Pages 自动部署 |
| **Worker** | `C:\Users\HP\Dev\CIPHER\cipher-proxy\`（**不在本仓库**）| `wrangler deploy` |
| Worker 备份 | `G:\My Drive\Share\3_Files\CIPHER\Backup\cipher-proxy\` | 每次改完 `cp` 同步 |
| 规则源 | `C:\Users\HP\0_Cowork\Cowork_Temp_Files\CIPHER_Knowledge\CIPHER_Rules\*-for-ai.md`（11份）| 改规则后重跑打包脚本 |

- Worker URL: `https://cipher-proxy.cipher-api.workers.dev`
- KV 限流: namespace `RATE_LIMIT_KV`，**60次/小时/IP（构建期值，上线前收紧）**

### Worker 部署流程
```
改 cipher-proxy/index.js → node --check --input-type=module < index.js
  → wrangler deploy（⚠️ 直接动生产，需人工确认）
  → cp index.js + rules-embedded.js 到 Backup
```

### 规则内嵌重新打包（改了规则文件后）
读 `CIPHER_Knowledge/CIPHER_Rules/*-for-ai.md` 11份 → 用 JSON.stringify 生成 `cipher-proxy/rules-embedded.js`（key=engine-core/jia-mu/…），Worker `import { RULES }` 使用。规则**不再放公开 /rules/ 目录**（已删，护 IP）。

### 测试 Worker（curl）
```
curl -s -X POST https://cipher-proxy.cipher-api.workers.dev/ \
  -H "Content-Type: application/json" -H "Origin: https://cipher-bazi.pages.dev" \
  -d '{"chart":{"day_master_cn":"辛",...},"path":"Money","message":"x"}'
```
看返回 `_meta.fallback`（NONE=纯v2成功 / v2_lenient=干净兜底 / legacy=最后兜底）、正文应**零中文**、含 4 模块（THE HIT/THE MAP/BLIND SPOT/THE MOVE）+ 末尾对应日主 Punchline。

### 输出结构（新版 7 模块）
Core Kernel（前端排盘）/ THE HIT / THE MAP / BLIND SPOT / THE MOVE+Punchline（**AI 写**）/ YOUR CONFIGURATION（前端接 judgment 的格局+用神）/ YOUR CURRENT SEASON（v2 占位）。

---

## 每次完成功能后输出变更摘要

```
【CIPHER变更】YYYY-MM-DD
改动：[一句话说做了什么]
文件：[哪个文件，哪个区域]
已部署：[是/否]
需要其他角色知道：[谁/无]
```

这段摘要我会复制给其他 Claude 对话审核。格式不要改。

---

## 已知技术债（按优先级）

| 优先级 | 技术债 | 说明 |
|--------|--------|------|
| P1 | 上线前收紧限流 | 现 60次/小时/IP 是构建期值；Sonnet 贵 3 倍，营销前必须右调防刷量 |
| P1 | 懒缓存（KV）| 按完整四柱签名缓存读盘结果，砍重复盘的 Sonnet 成本 + 热门盘秒出 |
| P2 | staging 环境 | 现每次部署直接动生产。加 wrangler [env.staging] + dev 分支 preview |
| P2 | 中文版 | 一套 Worker 加 `lang` 分叉（en→Sonnet / zh→DeepSeek），规则/judgment 共用 |
| P2 | 神煞规则补全 | 当前9种，还有3种规则待补 |
| P3 | 自定义域名 | cipher.destinyos.io（顺便可一键清 CDN 缓存）|
| P3 | /rules 旧 CDN 缓存 | 源已删，旧缓存自然过期中；自定义域名后可手动清 |
| — | 前端 session 缓存 key bug | 现 key 只用 日主+路径，未带完整四柱 → 同日主不同盘会串（做懒缓存时一并修）|

> 已解决（2026-06-04）：真太阳时修正（已加经度校正）、AI prompt（升 Sonnet + 新7模块）、IP 泄漏（规则内嵌）、安全（Origin+限流）。

---

## 不要碰的部分

- **排盘引擎核心逻辑**（lunar-javascript 的调用方式）——已验证通过，不要改
- **Cloudflare Worker 代码**——不在本仓库，需要用 wrangler CLI 单独操作
- **品牌调性/配色/文案**——这些由另一个角色（流）决定，不要自作主张改

---

## 关键验证用例

| 测试 | 输入 | 预期输出 |
|------|------|---------|
| Shadow 八字 | 1981-10-10, 8AM | 辛酉/戊戌/辛酉/壬辰 |
| Nova 八字 | 2014-05-23 | 甲午/己巳/甲午/辛未 |
| 缺时辰 | 任意日期, "I don't know" | 默认子时，标注"approximate" |

每次改完排盘相关代码，必须跑这三个用例验证。
