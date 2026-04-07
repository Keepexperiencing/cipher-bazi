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
| AI生成 | Gemini Flash API via Cloudflare Worker 代理 |
| 部署 | Vercel（GitHub main 分支连接，推送自动部署）|
| 域名 | cipher-bazi.vercel.app |

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
改代码 → git add . → git commit -m "描述" → git push → Vercel 自动部署（约30秒）
```

部署后访问 cipher-bazi.vercel.app 验证。

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
| P1 | 真太阳时修正 | 当前用标准时间，未按经度修正。广州经度 113.25° |
| P1 | 神煞规则补全 | 当前9种，还有3种规则待补 |
| P2 | Phase B AI prompt 优化 | 当前 System Prompt 在 Worker 里，需要根据用户反馈调优 |
| P3 | 自定义域名 | cipher.destinyos.io |

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
