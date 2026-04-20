# 庚金 完整规则库

# 第一部分：调候规则（穷通宝鉴）

## 庚金总论（跨月通则）

**核心定位（双来源）：**
- 《滴天髓》天干论："庚金带煞，刚健为最。得水而清，得火而锐。土润则生，土干则脆。能赢甲兄，输于乙妹。"
- 《神峰通考》体象诗："庚金顽钝性偏刚，火制功成怕火乡。夏产东南遇锻炼，秋生西北亦光芒。水深反见他相克，木旺能令我自伤。戊己干支重遇土，不逢冲破即埋藏。"

**象法核心意象：**
- 庚金 = 斧头/粗矿/未锻之铁/刀剑毛坯
- 丁火锻炼 = 高温炉火把粗矿锻成利器 = 压力/磨炼让人成材
- 土多埋金 = 矿石被厚土掩埋 = 才华被保护/规矩/传统淹没
- 壬水洗金 = 淬火后冷水定型 = 锻炼之后需要冷静沉淀
- 甲木 = 庚金的天然对手/劈削对象 = 有方向的攻击力

**庚金与辛金的核心区别：**
- 庚金（阳金）= 粗矿/斧头 → **喜丁火炼** → "打磨成武器"
- 辛金（阴金）= 珠宝/首饰 → **忌丁火炼** → "清洗后展示"
- 庚金刚健，五阳从气 → 旺极则顺其刚性
- 辛金柔顺，五阴从势 → 看环境决定走向
- 庚金的核心需求是"被锻造" → 压力是好事
- 辛金的核心需求是"被展示" → 出口是好事

## 正月庚金（寅月）

**原文核心：** "正月庚金，木旺之际，有土皆死，不能生金……先用丙暖庚性，又虑土厚埋金，须甲疏泄。"

**调候优先级：** 先丙后甲，丁火次之。

**月令特征：** 寅月甲木当令。庚金休囚失令，春寒未除。寅中藏丙火长生，可暖庚金。

### 调候规则

[Rule]
ID: QT-庚-01-A
Condition: 丙甲两透
Judgment: 科甲显荣
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-01-B
Condition: 丙透甲藏/甲透丙藏
Judgment: 亦有生监
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-01-C
Condition: 丙藏甲透
Judgment: 异路功名
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-01-D
Condition: 土多 + 甲透
Judgment: 贵；甲藏者富；庚出则否
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-01-E
Condition: 丁火出干 + 戊己无水
Judgment: 有寅中甲木引丁→富贵可推
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-01-F
Condition: 支成炎局 + 壬透有根
Judgment: 大富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-01-G
Condition: 支成炎局 + 壬透无根
Judgment: 小富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-01-H
Condition: 支成炎局 + 无水
Judgment: 🚫 残疾→ 健康关注方向需特别留意
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-庚-01-I
Condition: 丙遭癸困 + 无戊制
Judgment: 平人
Safety: ✅
Confidence: 中

**总结：** 正月庚金，丙甲为上，丁火次之。"春金多火，不夭则贫，阳金最喜火炼，锻炼太过，反主奔流。"

**象法意象：**
- 正月庚金 = 初春冰冷的铁矿石——硬但脆，需要火加热才能加工
- 丙火 = 太阳暖炉 = 先解冻，让金属软化到可以加工的状态
- 甲木 = 燃料 = 助火熔炼
- "有土皆死" = 春天的土又冷又湿，不能生金反而拖累

**CIPHER映射：**
- THE HIT方向：你是一块好矿石，但现在太冷了，还没法加工。第一步是找到一把火。
- BLIND SPOT方向：你以为你需要更多保护（土）。实际保护在春天帮不了你——你需要的是温度和锻炼。
- THE MOVE方向：去一个有压力的环境。庚金不怕火——火让你成型。

## 二月庚金（卯月）

**原文核心：** "二月庚金，柱中自然有乙……故二月庚金，专用丁火，借甲引丁，借庚劈甲。"

**调候优先级：** 专用丁火，甲庚佐之。

**月令特征：** 卯月乙木当令。乙庚合——"庚见乙必留情"，庚金有暗强之势（因合化）。所以二月庚金不像正月那么弱。

### 乙庚合前置判断（v1.1新增）

⚠️ **二月庚金必须先判断乙庚合的性质，再取调候规则。**

**合化金的三条件（必须同时满足）：**
1. 日主庚金坐支有金根（庚申、庚戌、庚辰通根）
2. 月令卯木被克制（年干或时干见辛金/庚金直接克）
3. 无强木透干阻化（甲木不透干）

**合不化（大多数情况）：**
- 庚乙相合相绊
- 乙不能正常发挥财星作用
- 庚也被牵制不能专注发挥
- 此时不作正财格处理，需另取用神

### 调候规则

[Rule]
ID: QT-庚-02-A1
Condition: **乙庚合化条件全满足**
Judgment: 庚金反旺→按比劫格处理
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-02-A2
Condition: **乙庚合化条件不全→合不化**
Judgment: 财被绊，格变
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-02-B
Condition: 丁甲两透+无庚劈
Judgment: 平人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-02-C
Condition: 丁透+无庚甲
Judgment: 可许贡监
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-02-D
Condition: 无丁有丙
Judgment: 异路功名（丙不如丁）
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-02-E
Condition: 一片甲乙+无庚
Judgment: 从财格，反主富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-02-F
Condition: 从财+见比肩
Judgment: 孤贫
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-02-G
Condition: 重见戊己
Judgment: 🚫 "死金嫌盖顶之泥"→ 厚土压金，才华被掩埋，须甲透疏通
Safety: ⚠️
Confidence: 中

**CIPHER映射（乙庚合分支）：**
- QT-庚-02-A1：合化成立 → THE HIT："你在一个本该让你付出的环境里反而获得了力量"
- QT-庚-02-A2：合不化 → THE HIT："你在追一个看起来属于你但始终抓不住的东西"

**象法意象：**
- 二月庚金 = 一把铁锤被藤蔓（乙木）缠住——不是被克，是被缠
- 丁火 = 烛火/锻炉 = 适度的火力正好炼铁
- "借甲引丁" = 把大木头劈开当柴烧→间接引来炼金之火
- "死金嫌盖顶之泥" = 矿石被厚土压住→动弹不得

**CIPHER映射：**
- THE HIT方向：你不是没力气——你是被缠住了。不是敌人在阻止你，是一段"舒适关系"在拖慢你。
- BLIND SPOT方向：乙庚合=柔软的东西让你放松警惕。你以为那是爱/支持，实际是绊脚。
- THE MOVE方向：你需要一把火来烧断藤蔓——去一个需要你全力以赴的地方。

## 三月庚金（辰月）

**原文核心：** "三月庚金，戊土司令，无生金之理，有埋金之忧，故先甲后丁。"

**调候优先级：** 先甲后丁，不用庚劈甲。

**月令特征：** 辰月戊土当令。"土旺金顽"——旺土不能生金反而埋金。

### 调候规则

[Rule]
ID: QT-庚-03-A
Condition: 丁甲丙透+无比肩
Judgment: 科甲之命
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-03-B
Condition: 甲透丁藏
Judgment: 采芹拾芥
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-03-C
Condition: 甲藏丁透
Judgment: 异路功名
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-03-D
Condition: 丁甲俱藏+无庚制
Judgment: 富中取贵，刀笔起家
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-03-E
Condition: 有甲无丁
Judgment: 平常之辈
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-03-F
Condition: 有丁无甲
Judgment: 迂儒腐儒
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-03-G
Condition: 丁甲两无
Judgment: 🚫 "下贱之流"→ 此配置需要特定运程才能发挥
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-庚-03-H
Condition: 支成土局+无木
Judgment: 🚫 "贫贱僧道"→ 独处型创作路径可能性
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-庚-03-I
Condition: 支成土局+见乙
Judgment: 🚫 "奸诈小人"→ 核心输出被其他事情稀释
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-庚-03-J
Condition: 支成火局+癸透
Judgment: 富贵
Safety: ✅
Confidence: 中

**总结公式：** 三月庚金=土厚埋金。解法=甲木劈土+丁火炼金。"庚金无火，非夭则贫"。

**象法意象：**
- 三月庚金 = 被厚土深埋的矿石——上面是一座小山丘
- 甲木 = 一棵大树的根系穿透土层 = 打破封印
- 丁火 = 树根露出后点火炼矿 = 锻造
- "土旺金顽" = 保护越多，金属越顽钝

**CIPHER映射：**
- THE HIT方向：你被埋了。不是被打败——是被保护得太好了。土越厚你越动不了。
- BLIND SPOT方向：你以为稳定=安全。实际稳定=停滞。你需要有人来翻土。
- THE MOVE方向：主动打破一个你觉得"稳固"的东西——一个习惯、一段关系、一个假设。

## 四月庚金（巳月）

**原文核心：** "四月庚金，长生于巳，巳内有戊，丙不熔金，故不畏火炎……先壬水，方得中和。"

**调候优先级：** 先壬后戊，丙火佐之。

**月令特征：** 巳月丙火当令。庚金长生在巳——此月庚金不像其他金那么怕火。巳中有戊土，"丙不熔金"。

### 调候规则

[Rule]
ID: QT-庚-04-A
Condition: 壬丙戊三者齐透
Judgment: 登科及第
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-04-B
Condition: 透一二者
Judgment: 亦非白丁
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-04-C
Condition: 一派丙火+无壬制
Judgment: 假杀为权，刑妻克子
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-04-D
Condition: 一派丙火+壬制
Judgment: 荣华
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-04-E
Condition: 支成金局
Judgment: 变弱为强→用丁不用丙，丁透者吉
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-04-F
Condition: 丁出三四
Judgment: 锻制太过，奔波
Safety: ✅
Confidence: 中

**⚠️ 四月庚金的关键特殊性：** "长生于巳"——庚金在巳月不算太弱。加上巳中有戊土保护，所以"不畏火炎"。这跟其他金日主四月的处理不同。

**象法意象：**
- 四月庚金 = 刚出炉的铁锭——热但不怕热，因为温度正好
- 壬水 = 淬火的冷水 = 定型、冷却、让金属变硬
- "长生于巳" = 这个月对庚金来说是"出生"——一切刚开始

**CIPHER映射：**
- THE HIT方向：你在一个高温环境里，但你不怕。这是你出生的季节——压力是你的养分。
- BLIND SPOT方向：你以为你需要更多火（更多压力/挑战）。实际你需要的是水——冷静下来，让已有的成果定型。
- THE MOVE方向：停下来。不是因为你累了，是因为铁锭需要冷水才能变硬。

## 五月庚金（午月）

**原文核心：** "五月庚金，丁火旺烈，庚金败地，专用壬水，癸又次之。"

**调候优先级：** 专用壬水，癸次之。

**月令特征：** 午月丁火当令。庚金处"败地"（沐浴），火旺金弱。

### 调候规则

[Rule]
ID: QT-庚-05-A
Condition: 壬癸透+支见庚辛
Judgment: 钟鼎名家
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-05-B
Condition: 金透+支见申子辰
Judgment: 金榜挂名
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-05-C
Condition: 无水出干+支只一水
Judgment: 一富之造（富重贵轻）
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-05-D
Condition: 支成炎局+无壬
Judgment: 🚫 "僧道"→ 独处型创作路径
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-庚-05-E
Condition: 二壬一庚同透
Judgment: 衣锦腰金
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-05-F
Condition: 一派己土+无甲+从杀
Judgment: 大贵（从杀格，切不可破）
Safety: ✅
Confidence: 中

**象法意象：**
- 五月庚金 = 烈火锻打中的铁坯——再打就碎了
- 壬水 = 一桶冰水从头浇下 = 救命的降温
- "金水会夏天" = 金属遇冰水，嗞嗞冒烟——淬炼的声音

**CIPHER映射：**
- THE HIT方向：你正在被生活的高温锻打。再多一锤可能就碎了——你需要的不是更坚强，是一场大雨。
- THE MOVE方向：找到你的壬水——一个让你冷静下来的人、一件让你放松的事。

## 六月庚金（未月）

**原文核心：** "六月庚金，三伏生寒，顽钝极矣，先用丁火，次取甲木。"

**调候优先级：** 先丁后甲。

**月令特征：** 未月己土当令。"三伏生寒"——表面热但庚金内部已经开始冷却转顽。未中有丁火余气。

### 调候规则

[Rule]
ID: QT-庚-06-A
Condition: 丁甲两透
Judgment: 名显身荣
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-06-B
Condition: 有甲无丁
Judgment: 庸俗
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-06-C
Condition: 有丁无甲
Judgment: 生员
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-06-D
Condition: 丁甲全无
Judgment: 🚫 "下贱之人"→ 此配置需要特定环境才能发挥核心优势——在对的环境里你极强，在错的环境里你会被闷住
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-庚-06-E
Condition: 支会土局+甲先丁后
Judgment: 甲透文章显达，丁透刀笔扬名
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-06-F
Condition: 忌癸伤丁
Judgment: 癸透则丁火受伤，降格
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-06-G
Condition: 柱多金+二丁出制
Judgment: 异路功名
Safety: ✅
Confidence: 中

**象法意象：**
- 六月庚金 = 三伏天里的一块旧铁——表面还热，里面已经钝了
- 丁火 = 精密的锻炉火 = 不是大火烤，是精确加温，恢复锋利
- 甲木 = 劈开的大木柴 = 给丁火续燃料
- "顽钝极矣" = 不是断了，是钝了——最危险的不是破损，是麻木

**CIPHER映射：**
- THE HIT方向：你不是累了。你是钝了。表面看起来还在运行，内心已经失去了锋利。
- THE MOVE方向：找一件让你重新感到"痛"的事——不是受伤，是重新磨刃。

## 七月庚金（申月）

**原文核心：** "七月庚金，刚锐极矣，专用丁火锻炼，次取木引丁。"

**调候优先级：** 专用丁火，甲木佐之。

**月令特征：** 申月庚金当令（建禄）。庚金极旺极刚。"秋金锐锐最为奇"。

### 调候规则

[Rule]
ID: QT-庚-07-A
Condition: 丁甲两透
Judgment: 定步青云
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-07-B
Condition: 有丁无甲
Judgment: 俊秀
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-07-C
Condition: 有甲无丁
Judgment: 平人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-07-D
Condition: 丁甲两无
Judgment: 无用之人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-07-E
Condition: 支成水局+乏丁用丙
Judgment: 须甲引火方可
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-07-F
Condition: 支成土局
Judgment: 先甲后丁
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-07-G
Condition: 支成火局
Judgment: 富贵中人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-07-H
Condition: 一丁坐午
Judgment: 独财格，金玉满堂，富中取贵
Safety: ✅
Confidence: 中

**⚠️ 七月庚金的核心原则：** "秋金锐锐最为奇，壬癸相逢总不宜"——秋金太旺太刚，最需要丁火来炼。壬癸水在此月反而不好——泄金太过。

**象法意象：**
- 七月庚金 = 刚出矿的纯铁——锋利、刚硬、未经打磨
- 丁火 = 锻造炉 = "百炼成钢"的关键
- "壬癸相逢总不宜" = 刚开刃的刀泡在水里=锈蚀
- 甲木引丁 = 把木柴劈开点火=给锻造炉加燃料

**CIPHER映射：**
- THE HIT方向：你现在是最强的版本——但"最强"不等于"最有用"。一块未经锻打的铁，再硬也只是铁。
- BLIND SPOT方向：你以为你需要的是更多资源/机会（水生金）。实际你需要的是一个把你逼到极限的人或环境（丁火）。
- THE MOVE方向：找到你的锻造炉——一个让你痛但让你变利的地方。

## 八月庚金（酉月）

**原文核心：** "八月庚金，刚锐既退，用丁甲，丙不可少。"

**调候优先级：** 丁甲为主，丙佐之。

**月令特征：** 酉月辛金当令（庚金阳刃月）。庚金旺但"刚锐既退"——从极刚开始转向收敛。

### 调候规则

[Rule]
ID: QT-庚-08-A
Condition: 丁甲透+丙见+阳刃无冲
Judgment: 功名显赫
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-08-B
Condition: 丙杀藏支+阳刃无冲
Judgment: 阳刃架杀，出将入相
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-08-C
Condition: 丙重+丁高透
Judgment: 科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-08-D
Condition: 丙出丁藏
Judgment: 异路之仕
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-08-E
Condition: 甲藏+火透水不透
Judgment: 衣衿可望
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-08-F
Condition: 不见丙丁
Judgment: 艺术之辈
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-08-G
Condition: 支成金局+丙丁出救
Judgment: 名魁天下，五福完人
Safety: ✅
Confidence: 中

**⚠️ 八月庚金=阳刃月。** 阳刃格是庚金特有的格局（辛金无阳刃）。阳刃架杀（丙火七杀制阳刃）是庚金最贵的格局之一。

**象法意象：**
- 八月庚金 = 秋天的大刀——从极锋利开始微微回钝
- 阳刃 = 刀的最锋利的一瞬间 = 危险但有力
- 丙杀架刃 = 用火焰来控制刀的锋芒 = 权力+控制力
- "出将入相" = 军事统帅级别的格局

**CIPHER映射：**
- THE HIT方向：你天生带刃。锋利到让人害怕——包括你自己。
- BLIND SPOT方向：你以为你的锋利是你最大的资产。实际没有火来控制它，锋利就是危险。
- THE MOVE方向：找到能"架住"你的人——不是压制你，是给你一个配得上你锋利的舞台。

## 九月庚金（戌月）

**原文核心：** "九月庚金，戊土司令，最怕土厚埋金，宜先用甲疏，后用壬洗，则金自出矣。"

**调候优先级：** 先甲后壬。忌己土浊壬。

**月令特征：** 戌月戊土当令。与辛金九月同——"土厚埋金"。但庚金比辛金更不怕埋——庚金刚硬，埋了还能挖出来。

### 调候规则

[Rule]
ID: QT-庚-09-A
Condition: 壬甲两透
Judgment: 科甲相宜
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-09-B
Condition: 甲透壬藏
Judgment: 乡魁可望
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-09-C
Condition: 甲藏壬透
Judgment: 廪贡堪谋
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-09-D
Condition: 有甲无壬
Judgment: 犹有学问
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-09-E
Condition: 有壬无甲
Judgment: 莫问衣衿
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-09-F
Condition: 壬甲两无
Judgment: 下格
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-09-G
Condition: 支成水局+丙透
Judgment: 才高迈众，一榜可许
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-09-H
Condition: 戊多金旺+无甲壬
Judgment: 虽有衣禄亦不能久
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-09-I
Condition: 庚戊多+无壬甲
Judgment: 愚顽之辈
Safety: ✅
Confidence: 中

**象法意象：**
- 九月庚金 = 被黄土埋到胸口的武士——还有力气，但动不了
- 甲木 = 一棵树的根穿透土层 = 破土
- 壬水 = 雨水冲刷泥土 = 清洗露出金属
- "土厚埋金" = 你的处境不是被打败，是被淹没

**CIPHER映射：**
- THE HIT方向：你是一个被埋在官僚/规矩/传统里的战士。你的力量还在——但你动不了。
- BLIND SPOT方向：你以为更多的忍耐=更大的回报。实际土只会越来越厚——你需要主动挖。
- THE MOVE方向：找一个甲木——一个帮你破土的人、一个让你重见天日的决定。

## 十月庚金（亥月）

**原文核心：** "十月庚金，水冷性寒，非丁莫造，非丙不暖。"

**调候优先级：** 丁甲为主。

**月令特征：** 亥月壬水当令。庚金入冬，开始变冷。水旺泄金。

### 调候规则

[Rule]
ID: QT-庚-10-A
Condition: 丁甲两透+支无水局
Judgment: 一榜有之
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-10-B
Condition: 支藏丙火
Judgment: 桃浪之仙
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-10-C
Condition: 支见亥子+己出制
Judgment: 亦有功名
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-10-D
Condition: 丙透无丁
Judgment: 无显达
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-10-E
Condition: 丁藏甲透
Judgment: 武职之人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-10-F
Condition: 金水混杂+无丙丁
Judgment: 🚫 鄙夫→ 此配置需火暖局方能发挥
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-庚-10-G
Condition: 支成金局+无火
Judgment: 🚫 "僧道"→ 独处型路径
Safety: ⚠️
Confidence: 中

**象法意象：**
- 十月庚金 = 初冬的铁器——开始生锈，表面结霜
- 丁火 = 锻造炉的余温 = 还来得及加热
- "水冷金寒爱丙丁" = 冬天的金属最需要火

**CIPHER映射：**
- THE HIT方向：你的锋利还在——但在结霜。再不加温，你会变成一块冷铁。
- THE MOVE方向：趁还没完全冷下来，找到你的火。

## 十一月庚金（子月）

**原文核心：** "十一月庚金，天气严寒，仍取丁甲，次取丙火照暖。"

**调候优先级：** 丁甲为主，丙照暖。

**月令特征：** 子月癸水当令。深冬极寒。庚金被冻。

### 调候规则

[Rule]
ID: QT-庚-11-A
Condition: 丁甲两透+丙在支中
Judgment: 科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-11-B
Condition: 无丙+丁甲透
Judgment: 亦有衣衿
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-11-C
Condition: 有丁无甲
Judgment: 富中取贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-11-D
Condition: 有甲无丁
Judgment: 只作常人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-11-E
Condition: 丙透丁藏
Judgment: 异途名望
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-11-F
Condition: 支成水局+不见丙丁
Judgment: 伤官格，清雅，衣禄常盈
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-11-G
Condition: 丙丁太多
Judgment: 官杀混杂，不良
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-11-H
Condition: 一派金水+不入火土乡
Judgment: 一生孤贫浪荡
Safety: ✅
Confidence: 中

**⚠️ 金水伤官见官不忌：** 冬月庚金（子月），支成水局见丙丁，不以"伤官见官"为忌。调候暖局优先。这与辛金冬月的处理一致——硬编码例外。

**象法意象：**
- 十一月庚金 = 深冬铁器——完全冻住，动不了
- 丁甲 = 炉火+柴薪 = 解冻并锻造
- 丙火照暖 = 太阳出来了 = 起码让环境不那么冷

**CIPHER映射：**
- THE HIT方向：你现在是一块冻在冰里的铁。不是你不锋利——是环境把你冻住了。
- THE MOVE方向：先解冻。什么都不做，先让自己暖回来。

## 十二月庚金（丑月）

**原文核心：** "十二月庚金，寒气太重，且多湿泥，愈寒愈冻，先取丙火解冻，次取丁火炼金，甲亦不可少。"

**调候优先级：** 先丙解冻，次丁炼金，甲佐之。

**月令特征：** 丑月己土当令。寒极+湿泥。丑土是湿冷的土——跟戌土燥土不同。

### 调候规则

[Rule]
ID: QT-庚-12-A
Condition: 丙丁甲透
Judgment: 即不科甲亦有恩荣
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-12-B
Condition: 有丙无丁甲
Judgment: 富中取贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-12-C
Condition: 有丁甲无丙
Judgment: 特达才人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-12-D
Condition: 有丙丁无甲
Judgment: 白手成家，刀笔亨通
Safety: ✅
Confidence: 中

[Rule]
ID: QT-庚-12-E
Condition: 支成金局+无水
Judgment: 🚫 "僧道之流"→ 独处型路径
Safety: ⚠️
Confidence: 中

**象法意象：**
- 十二月庚金 = 深冬湿冷泥浆里的铁坯——又冷又湿又脏
- 丙火 = 太阳 = 先解冻
- 丁火 = 锻造炉 = 解冻后开始打磨
- 甲木 = 燃料 = 维持火力
- "愈寒愈冻" = 越等越糟——必须主动破局

**CIPHER映射：**
- THE HIT方向：你现在处于最冷最暗的时刻。但这不是终点——丙火已经在地平线上了。
- THE MOVE方向：先暖后炼。第一步不是努力——是找到温暖。

## 庚金十二月总览表

Month: 正月（寅）
月令: 甲木
核心问题: 春寒+金弱
Priority: 先丙后甲
Imagery_OneLine: 冰冷的矿石
THE_HIT: 你需要火，不是保护
Sensitive: QT-庚-01-H

Month: 二月（卯）
月令: 乙木
核心问题: 乙庚合绊
Priority: 专用丁火
Imagery_OneLine: 被藤蔓缠住的铁锤
THE_HIT: 缠住你的不是敌人，是舒适
Sensitive: QT-庚-02-G

Month: 三月（辰）
月令: 戊土
核心问题: 土厚埋金
Priority: 先甲后丁
Imagery_OneLine: 被厚土深埋的矿石
THE_HIT: 稳定=停滞，你需要破土
Sensitive: QT-庚-03-G/H/I

Month: 四月（巳）
月令: 丙火
核心问题: 金遇长生
Priority: 先壬后戊
Imagery_OneLine: 刚出炉的铁锭
THE_HIT: 你不怕热——但需要冷水定型
Sensitive: —

Month: 五月（午）
月令: 丁火
核心问题: 火旺金败
Priority: 专用壬水
Imagery_OneLine: 快碎的铁坯
THE_HIT: 再打一锤就碎了——需要水
Sensitive: QT-庚-05-D

Month: 六月（未）
月令: 己土
核心问题: 顽钝
Priority: 先丁后甲
Imagery_OneLine: 三伏天的旧铁
THE_HIT: 你不是累了，是钝了
Sensitive: QT-庚-06-D

Month: 七月（申）
月令: 庚金
核心问题: 极刚
Priority: 专用丁火
Imagery_OneLine: 纯铁——硬但未成器
THE_HIT: 最强≠最有用，需要锻造
Sensitive: —

Month: 八月（酉）
月令: 辛金
核心问题: 阳刃
Priority: 丁甲+丙佐
Imagery_OneLine: 秋天的大刀
THE_HIT: 你天生带刃，需要架住你的火
Sensitive: —

Month: 九月（戌）
月令: 戊土
核心问题: 土厚埋金
Priority: 先甲后壬
Imagery_OneLine: 被黄土埋住的武士
THE_HIT: 你在被规矩/传统淹没
Sensitive: —

Month: 十月（亥）
月令: 壬水
核心问题: 水冷金寒
Priority: 丁甲为主
Imagery_OneLine: 结霜的铁器
THE_HIT: 你在结霜——再不加温就锈了
Sensitive: QT-庚-10-F/G

Month: 十一月（子）
月令: 癸水
核心问题: 寒冻
Priority: 丁甲+丙暖
Imagery_OneLine: 冻在冰里的铁
THE_HIT: 你被冻住了
Sensitive: —

Month: 十二月（丑）
月令: 己土
核心问题: 寒+湿泥
Priority: 先丙后丁+甲
Imagery_OneLine: 湿冷泥浆里的铁坯
THE_HIT: 先暖后炼
Sensitive: QT-庚-12-E

# 第二部分：格局规则（子平真诠）

## 庚金十神对照表

Stem: 甲
庚金的十神: 偏财
说明: 我克之阳=偏财/副业/父亲

Stem: 乙
庚金的十神: 正财
说明: 我克之阴=正妻/正当收入

Stem: 丙
庚金的十神: 七杀
说明: 克我之阳=偏官/压力/竞争对手

Stem: 丁
庚金的十神: 正官
说明: 克我之阴=正官/规则/正当权威

Stem: 戊
庚金的十神: 偏印(枭神)
说明: 生我之阳=偏印/非正统学问

Stem: 己
庚金的十神: 正印
说明: 生我之阴=正印/母亲/正统教育

Stem: 庚
庚金的十神: 比肩
说明: 同类之阳=比肩/同伴/同行

Stem: 辛
庚金的十神: 劫财
说明: 同类之阴=劫财/竞争同类

Stem: 壬
庚金的十神: 食神
说明: 我生之阳=食神/温和表达/创作才华

Stem: 癸
庚金的十神: 伤官
说明: 我生之阴=伤官/叛逆表达/非正统才华

**⚠️ 庚金与辛金十神的关键差异：**
- 庚金的正官是**丁火**（阴火锻金→正统磨炼），辛金的正官是丙火
- 庚金的七杀是**丙火**（阳火烈炼→高压逼迫），辛金的七杀是丁火
- 庚金的食神是**壬水**，伤官是**癸水**——跟辛金正好反过来

## 庚金十二月格局映射表

Month: 正月
Branch: 寅
HiddenStem: 甲丙戊
MainGod: 甲(偏财)
Patterns: **偏财格**
用神变化可能: 丙透→七杀格；戊透→偏印格（印轻，戊仅余气）

Month: 二月
Branch: 卯
HiddenStem: 乙
MainGod: 乙(正财)
Patterns: **正财格**
用神变化可能: 专气。⚠️ 乙庚合，需判断合化

Month: 三月
Branch: 辰
HiddenStem: 戊乙癸
MainGod: 戊(偏印)
Patterns: **杂气格**
用神变化可能: 戊透→偏印格；乙透→正财格；癸透→伤官格

Month: 四月
Branch: 巳
HiddenStem: 丙庚戊
MainGod: 丙(七杀)
Patterns: **七杀格**
用神变化可能: 戊透→偏印格；庚透→建禄月劫

Month: 五月
Branch: 午
HiddenStem: 丁己
MainGod: 丁(正官)
Patterns: **正官格**
用神变化可能: 己透→正印格

Month: 六月
Branch: 未
HiddenStem: 己丁乙
MainGod: 己(正印)
Patterns: **杂气格**
用神变化可能: 己透→正印格；丁透→正官格；乙透→正财格

Month: 七月
Branch: 申
HiddenStem: 庚壬戊
MainGod: 庚(比肩)
Patterns: **建禄格**
用神变化可能: 壬透→食神格；戊透→偏印格

Month: ⭐八月
Branch: 酉
HiddenStem: 辛
MainGod: 辛(劫财)
Patterns: **阳刃格**
用神变化可能: 专气。庚金酉月=阳刃！

Month: 九月
Branch: 戌
HiddenStem: 戊辛丁
MainGod: 戊(偏印)
Patterns: **杂气格**
用神变化可能: 戊透→偏印格；丁透→正官格

Month: 十月
Branch: 亥
HiddenStem: 壬甲
MainGod: 壬(食神)
Patterns: **食神格**
用神变化可能: 甲透→偏财格

Month: 十一月
Branch: 子
HiddenStem: 癸
MainGod: 癸(伤官)
Patterns: **伤官格**
用神变化可能: 专气。⚠️ 冬月金水伤官见官不忌

Month: 十二月
Branch: 丑
HiddenStem: 己辛癸
MainGod: 己(正印)
Patterns: **杂气格**
用神变化可能: 己透→正印格；癸透→伤官格

**⚠️ 庚金的核心特殊性：**
1. **酉月=阳刃格（辛金没有阳刃）** → 庚金最独特的格局
2. **乙庚合** → 二月卯月乙木当令，庚见乙合（可能化金）
3. **巳月庚金长生** → 四月七杀格但庚金不弱（"丙不熔金"）
4. **金水伤官见官不忌** → 冬月（亥子丑）庚金，伤官见丁火正官不以为忌

## 庚金可成格局详细规则

### 一、正官格（庚金见丁火为正官）

**出现月份：** 午月（丁火当令）、未月（杂气丁火透出）、戌月（杂气丁火透出）

**核心原则：** 庚金喜丁火炼——"阳金最喜火炼"。丁火正官对庚金不是压制，是锻造。这跟辛金见丙火正官（怕裂）完全不同。

[Rule]
ID: ZP-庚-官-成01
Condition: 月令丁火正官 + 财印相随不碍
Judgment: 贵格
Narrative: 你天生适合被磨炼。规矩不是束缚——是让你成型的模具

[Rule]
ID: ZP-庚-官-成02
Condition: 正官 + 甲乙财生官 + 身不弱
Judgment: 财旺生官
Narrative: 你的资源直接服务于你的锻造——越有料越能打

[Rule]
ID: ZP-庚-官-成03
Condition: 正官 + 己土印护官 + 无癸伤官
Judgment: 官印相生
Narrative: 你的教育和背景保护着你的锻造过程——传统路径对你最有利

[Rule]
ID: ZP-庚-官-败01
Condition: 正官 + 癸水伤官透干
Judgment: 破格
Narrative: 你的叛逆正在消解你的锻造——不让火烧你，你就永远是块矿石

[Rule]
ID: ZP-庚-官-败02
Condition: 正官 + 丙火七杀混杂
Judgment: 官杀混杂
Narrative: 你面前有两种火——温火和烈火——你在两者之间犹豫

[Rule]
ID: ZP-庚-官-救01
Condition: 官逢癸伤 + 己土印制癸
Judgment: 印制伤护官
Narrative: 你的学识帮你控制住了叛逆——该受锻炼时你忍得住

[Rule]
ID: ZP-庚-官-救02
Condition: 官杀混杂 + 壬水合丁去官（或制丙留丁）
Judgment: 取清
Narrative: 你学会了选择适合你的"火"——不是所有压力都值得承受

**取运喜忌：**
- 喜：财运（甲乙木生官）、印运（己土护官）
- 忌：伤官运（癸水）、食神运（壬水泄金伤官）

### 二、七杀格（庚金见丙火为七杀）

**出现月份：** 巳月（丙火当令）、寅月（杂气丙火透出）

**⚠️ 庚金七杀的特殊性：** 巳月庚金"长生于巳"——庚金在巳月不弱！"丙不熔金"（巳中有戊土保护）。所以庚金四月七杀格不像其他日主那么危险。

[Rule]
ID: ZP-庚-煞-成01
Condition: 月令丙火七杀（巳月）+ 壬水食神制煞 + 庚金通根（巳中庚禄或他处金根）
Judgment: 身强煞强，食神制煞有力则大贵
Narrative: 你面对的是烈火级别的压力——你也有配得上这种压力的硬度

[Rule]
ID: ZP-庚-煞-成02
Condition: 七杀 + 己土正印化煞 + 身弱
Judgment: 煞印相生
Narrative: 高压环境通过你的学识被消化了——越有压力越成长

[Rule]
ID: ZP-庚-煞-败01
Condition: 七杀 + 甲乙财滋煞 + 无制
Judgment: 财滋煞无制
Narrative: 你在用资源去喂养一个越来越大的压力源

[Rule]
ID: ZP-庚-煞-救01
Condition: 煞逢食制+戊印护煞 + 甲财去印存食
Judgment: 去印存食
Narrative: 去掉那些"保护你不用面对"的东西，直接用技能对抗

**⚠️ 巳月庚金的特殊性（补充说明）：**

巳中藏庚（长生），庚金在月令有根。这不是其他日主"在七杀月被克"的情况——是"双方都强"。
- 身强煞强（巳月庚金） ≠ 身煞两停（寅月庚金或他处庚金见丙）
- 身强煞强的人生状态：高压高产出，能扛能打
- 身煞两停的人生状态：精准平衡，不能偏

**取运喜忌：**
- 食神制煞：喜食伤运、身旺运。忌印运（去食护煞）、财运（滋煞）
- 印化煞：喜印运、比劫运。忌财运（破印党煞）

### 三、财格（庚金见甲木偏财/乙木正财）

**出现月份：** 寅月（甲木当令→偏财格）、卯月（乙木当令→正财格）、辰未月杂气

**⚠️ 二月卯月特殊性：乙庚合。** 卯月乙木当令，庚见乙合。"庚见乙必留情"——合而化金则庚反旺；合而不化则庚被绊。

[Rule]
ID: ZP-庚-财-成01a
Condition: 月令甲木偏财（寅月）+ 丁火官透
Judgment: 财旺生官
Narrative: 你赚的钱直接让人尊敬你

[Rule]
ID: ZP-庚-财-成01b
Condition: 月令乙木正财（卯月）+ 丁火官透 + 乙庚不合（乙被其他字合住或克制）
Judgment: 财旺生官（需避合）
Narrative: 你的财运需要突破一个关键的牵绊才能稳定

[Rule]
ID: ZP-庚-财-成01c
Condition: 月令乙木正财（卯月）+ 乙庚直接相合
Judgment: 财格变质，需另取用神
Narrative: 看起来属于你的东西被你自己抓得太紧反而失去

[Rule]
ID: ZP-庚-财-成02
Condition: 财星 + 壬癸食伤透 + 身强
Judgment: 食伤生财
Narrative: 你的才华直接变成收入

[Rule]
ID: ZP-庚-财-成03
Condition: 一片甲乙+无庚比
Judgment: 从财格（身极弱财极旺）
Narrative: 你不是老板——你天生是投资人

[Rule]
ID: ZP-庚-财-败01
Condition: 财星 + 庚辛比劫重 + 无食伤化
Judgment: 比劫争财
Narrative: 同行太多，蛋糕被分光了

[Rule]
ID: ZP-庚-财-败02
Condition: 财星 + 丙火七杀透 + 无制
Judgment: 财滋煞
Narrative: 赚的钱反而养大了你的对手

[Rule]
ID: ZP-庚-财-救01
Condition: 财逢劫 + 壬癸食伤化劫
Judgment: 化劫生财
Narrative: 竞争者被转化成了生产力

**取运喜忌：**
- 喜：官运、食伤运（生财）
- 忌：比劫运（争财）、七杀运（滋煞）

### 四、印绶格（庚金见戊土偏印/己土正印）

**出现月份：** 辰月（戊土当令→偏印格）、未月（己土当令→正印格）、戌月（戊土当令→偏印格）、丑月（己土当令→正印格）

**⚠️ 庚金印格的特殊问题——土厚埋金：** "三月庚金，戊土司令，无生金之理，有埋金之忧。" 旺土不生金反而埋金，这是庚金印格最大的陷阱。

[Rule]
ID: ZP-庚-印-成01
Condition: 印星 + 丙丁官煞来生印 + 身弱
Judgment: 煞印相生
Narrative: 压力被你的背景消化了——越有压力支持系统越强

[Rule]
ID: ZP-庚-印-成02
Condition: 身印两旺 + 壬癸食伤泄秀
Judgment: 泄秀
Narrative: 你的支持系统太强了——需要出口来释放

[Rule]
ID: ZP-庚-印-成03
Condition: 印多 + 甲乙财透制印
Judgment: 财损过旺之印
Narrative: 土厚埋金的解法——用木来劈开泥土

[Rule]
ID: ZP-庚-印-败01
Condition: 土多无甲
Judgment: 🚫 土厚埋金→ "才华被保护层完全淹没"
Narrative: 你的支持系统把你活埋了

[Rule]
ID: ZP-庚-印-败02
Condition: 身强印重 + 丙七杀透 + 无食伤泄
Judgment: 煞生印更旺
Narrative: 压力反而让保护者更过度保护你——恶性循环

[Rule]
ID: ZP-庚-印-救01
Condition: 印逢财破 + 庚辛比劫护印
Judgment: 劫护印
Narrative: 同伴帮你挡住了诱惑

**取运喜忌：**
- 身弱印轻：喜官煞生印、比劫帮身
- 身旺印重：喜食伤泄秀、财运（甲木劈土）。忌再见土（更埋）

### 五、食神格/伤官格（庚金见壬水食神/癸水伤官）

**出现月份：** 亥月（壬水当令→食神格）、子月（癸水当令→伤官格）、申月（壬水透出→食神格）

[Rule]
ID: ZP-庚-食-成01
Condition: 月令壬食神 + 甲乙财透
Judgment: 食神生财
Narrative: 才华温和地流向收入——稳定可持续

[Rule]
ID: ZP-庚-食-成02
Condition: 食神 + 丙火七杀透 + 无财
Judgment: 食神制煞
Narrative: 温和的才华驯服了最大的压力——四两拨千斤

[Rule]
ID: ZP-庚-伤-成01
Condition: 月令癸伤官 + 甲乙财透 + 身强
Judgment: 伤官生财
Narrative: 叛逆的才华直接变钱——越不走寻常路越赚钱

[Rule]
ID: ZP-庚-伤-成02
Condition: 伤官 + 己土正印透有根 + 身弱
Judgment: 伤官佩印
Narrative: 叛逆被学问收敛——有深度的锋利

[Rule]
ID: ZP-庚-食-败01
Condition: 食神 + 戊偏印透（枭神夺食）
Judgment: 破格
Narrative: 旧体系在扼杀你的才华

[Rule]
ID: ZP-庚-伤-败01
Condition: 伤官 + 丁火正官透（**非亥子丑月，且不符合ZP-庚-伤-成03条件**）
Judgment: 伤官见官
Narrative: 你的叛逆正在跟规则正面冲突

### 🔴 金水伤官见官——独立美格（非败格豁免）

在冬月（亥子丑）金水配置下，伤官见官**不是"豁免破格"，而是独立的美格**。
调候需要火，伤官生财生官形成流通。这是庚金冬月最优雅的配置之一。

[Rule]
ID: ZP-庚-伤-成03
Condition: 亥子丑月 + 壬癸伤食透 + 丁丙官煞透 + 身强
Judgment: 金水伤官喜见官，调候为急，美格
Narrative: 你的"叛逆"和"规则"在冬月互相需要——没有对手你会冷得停摆

**⚠️ 此规则位置：** 独立在伤官格主规则之后，优先级高于ZP-庚-伤-败01。

**引擎判断顺序：** 先检查是否符合ZP-庚-伤-成03 → 如果符合，直接成格 → 不再触发"伤官见官破格"警报。

**⭐ 金水相涵美格：** 庚金申月（建禄），支全申子辰水局，壬癸泄秀→"金水相涵"，为伤官格中最秀最贵的配置之一。子平真诠特别提到"庚日全逢润下"。

**取运喜忌：**
- 食伤生财：喜财运、食伤运。忌枭印运
- 金水相涵：喜金水运。忌火土运（逆其势）

### 六、阳刃格 ⭐（庚金酉月独有）

**出现月份：** 酉月（辛金当令=庚金阳刃月）

**⚠️ 这是庚金最独特的格局——辛金没有阳刃格。** 阳刃=旺逾其分=刀的最锋利一瞬。庚金在酉月极旺，需要官煞（丁火/丙火）来制刃。

[Rule]
ID: ZP-庚-刃-成01
Condition: 酉月 + 丁火正官透 + 财印不碍 + 无伤官
Judgment: 阳刃用官，贵格
Narrative: 你天生带刃。需要规矩来架住你的锋利

[Rule]
ID: ZP-庚-刃-成02
Condition: 酉月 + 丙火七杀透 + 身煞两停
Judgment: 煞刃格，威权大贵
Narrative: 烈火控制利刃——这是将军的格局

[Rule]
ID: ZP-庚-刃-成03
Condition: 酉月 + 壬癸食伤泄秀 + 无官煞
Judgment: 刃用食伤泄
Narrative: 锋利得无处安放，只能转化为才华输出

[Rule]
ID: ZP-庚-刃-败01
Condition: 酉月 + 无丁丙官煞 + 无食伤
Judgment: 刃旺无制
Narrative: 一把没有鞘的刀——锋利但危险

[Rule]
ID: ZP-庚-刃-败02
Condition: 阳刃用官 + 癸伤官透克丁
Judgment: 伤官破官
Narrative: 你的叛逆在消解你唯一的控制力

[Rule]
ID: ZP-庚-刃-救01
Condition: 刃用官+伤透 + 己印合去癸伤
Judgment: 印护官
Narrative: 学识帮你压住叛逆，保住控制力

[Rule]
ID: ZP-庚-刃-救02
Condition: 官煞混杂 + 壬合丁去官留煞
Judgment: 合官留煞，煞刃格清
Narrative: 只留最强的火——煞刃格越纯越贵

**阳刃架杀（子平真诠经典组合）：**
- 丙火七杀+酉月阳刃=煞刃格
- "刃旺煞强，威权显赫"
- 财印并见不相碍则大贵
- 不见伤官为格之成
- 乾隆皇帝造"辛卯/丁酉/庚午/丙子"即为阳刃格官煞竞出。子平真诠的处理是"子午相冲，冲去午中丁火正官，只留丙火七杀"——煞刃格纯，威权大贵。
- **规则启示：** 官煞混杂时的取清方式有两种——**合去**（如丁壬合）和**冲去**（如子午冲）。两种方式在CIPHER引擎中需要分别判断：合需要有合化条件，冲需要地支冲的位置关系。

**取运喜忌：**
- 刃用官：喜助官运（丁火得助）、印运。忌伤食运（克官）
- 煞刃格：煞轻→喜助煞运；煞重→喜身旺印运
- 刃用食伤：喜财运（食伤生财流通）

### 七、建禄格（庚金申月）

**出现月份：** 申月（庚金建禄）

[Rule]
ID: ZP-庚-禄-成01
Condition: 申月 + 丁火官透 + 财印随
Judgment: 同正官格
Narrative: 你本身很强，需要锻造来定型

[Rule]
ID: ZP-庚-禄-成02
Condition: 申月 + 甲乙财透 + 壬癸食伤化劫
Judgment: 同财格
Narrative: 你很强但需要出口——才华→收入的通道要打通

[Rule]
ID: ZP-庚-禄-成03
Condition: 申月 + 丙煞透 + 壬食制煞
Judgment: 同七杀格
Narrative: 你很强，正好可以承受大压力

[Rule]
ID: ZP-庚-禄-成04
Condition: 申月 + 壬癸泄秀 + 甲乙财接
Judgment: 金水相涵
Narrative: 秋金生水=金水相涵，最秀之格

[Rule]
ID: ZP-庚-禄-败01
Condition: 申月 + 无财官食伤
Judgment: 孤禄无用
Narrative: 一身力气不知往哪使

**取运：** 取决于所取用神，与该格局取运同。

### 八、杂气格

[Rule]
ID: ZP-庚-杂-01
Condition: 辰月 + 戊透
Judgment: 偏印格

[Rule]
ID: ZP-庚-杂-02
Condition: 辰月 + 乙透
Judgment: 正财格

[Rule]
ID: ZP-庚-杂-03
Condition: 辰月 + 癸透
Judgment: 伤官格

[Rule]
ID: ZP-庚-杂-04
Condition: 戌月 + 戊透
Judgment: 偏印格

[Rule]
ID: ZP-庚-杂-05
Condition: 戌月 + 丁透
Judgment: 正官格

[Rule]
ID: ZP-庚-杂-06
Condition: 未月 + 己透
Judgment: 正印格

[Rule]
ID: ZP-庚-杂-07
Condition: 未月 + 丁透
Judgment: 正官格

[Rule]
ID: ZP-庚-杂-08
Condition: 未月 + 乙透
Judgment: 正财格

[Rule]
ID: ZP-庚-杂-09
Condition: 丑月 + 己透
Judgment: 正印格

[Rule]
ID: ZP-庚-杂-10
Condition: 丑月 + 癸透
Judgment: 伤官格

## 庚金与辛金格局体系核心差异

Dimension: 阳刃格
庚金: ✅ 酉月（最独特格局）
辛金: ❌ 无阳刃

Dimension: 正官火
庚金: 丁火=锻造之火（喜）
辛金: 丙火=烈日直射（怕）

Dimension: 对火的态度
庚金: "阳金最喜火炼"
辛金: "辛金珠玉最怕红炉"

Dimension: 核心需求
庚金: 被锻造→压力是好事
辛金: 被展示→出口是好事

Dimension: 乙庚合
庚金: 庚为日主，遇乙合（被缠）
辛金: 辛为日主，不存在此合

Dimension: 丙辛合
庚金: 不存在此合
辛金: 辛为日主，遇丙合（官来合我）

Dimension: 对水的态度
庚金: 喜水淬火定型；怕水多淹没（"壬癸相逢总不宜"）
辛金: 喜壬水洗淘（壬水=辛金的解药）

# 第三部分：象法意象库

## 庚金象法意象库

## 一、庚金核心原型

### 古籍原始定位

Source: 滴天髓
Original: "庚金带煞，刚健为最。得水而清，得火而锐。土润则生，土干则脆。能赢甲兄，输于乙妹"
Core_Imagery: 刚健、带煞气、喜水喜火、怕燥土

Source: 神峰通考
Original: "庚金顽钝性偏刚，火制功成怕火乡"
Core_Imagery: 顽钝、刚硬、需火锻炼

Source: 神峰通考
Original: "夏产东南遇锻炼，秋生西北亦光芒"
Core_Imagery: 夏天=锻炼成器；秋天=自然发光

Source: 神峰通考
Original: "水深反见他相克，木旺能令我自伤"
Core_Imagery: 水太多反而淹没；木太多消耗自身

Source: 神峰通考
Original: "戊己干支重遇土，不逢冲破即埋藏"
Core_Imagery: 土厚埋金——保护过度=埋没

Source: 穷通宝鉴
Original: "秋金锐锐最为奇，壬癸相逢总不宜"
Core_Imagery: 秋天最锋利，不需要更多水泄

Source: 穷通宝鉴
Original: "庚金无火，非夭则贫"
Core_Imagery: 没有火的锻炼=废铁

Source: 三命通会
Original: "庚金为月"
Core_Imagery: 月亮——秋月最明，冷光照世

Source: 滴天髓
Original: "能赢甲兄，输于乙妹"
Core_Imagery: 打得过硬木，被软藤缠住

### CIPHER核心原型定义

**庚金 = THE AXE**

一句话：**你是一把需要被锻造才能成器的粗铁。不怕火——火让你变利。**

核心物质意象（按优先级）：
1. **斧头/大刀** — 粗犷、有力、直接、需要磨砺
2. **未炼之铁矿** — 有潜力但还没成型
3. **月亮** — 冷光照世，秋天最亮（三命通会取象）
4. **铁锤** — 重击的工具，需要方向
5. **盔甲** — 保护者，刚硬但沉重

**庚金与辛金的原型对比：**

Dimension: 物质
庚金 THE AXE: 粗铁/斧头/矿石
辛金 THE REFINED ARTIFACT: 珠宝/首饰/手术刀

Dimension: 本质
庚金 THE AXE: 刚健、顽钝、需锻炼
辛金 THE REFINED ARTIFACT: 柔润、虚灵、需展示

Dimension: 对火
庚金 THE AXE: 喜火炼→"百炼成钢"
辛金 THE REFINED ARTIFACT: 忌火炼→"烈火碎玉"

Dimension: 对水
庚金 THE AXE: 喜水淬火定型；忌水太多淹没
辛金 THE REFINED ARTIFACT: 喜水洗淘展示光泽

Dimension: 对土
庚金 THE AXE: 土多埋金=被保护到窒息
辛金 THE REFINED ARTIFACT: 土多埋金=才华被遮蔽

Dimension: 核心需求
庚金 THE AXE: 被锻造 → 压力是好事
辛金 THE REFINED ARTIFACT: 被展示 → 出口是好事

Dimension: THE MOVE方向
庚金 THE AXE: 去找一把火
辛金 THE REFINED ARTIFACT: 让一条河流出去

## 二、庚金与十天干的关系意象

TenGod: 偏财·甲木
Stem: 我克之阳
NaturalImagery: 斧头劈大树——正对手，一刀下去干脆利落
OneLine: 你的赚钱方式是直接的、有力的、一刀见血的

TenGod: 正财·乙木（常态）
Stem: 我克之阴
NaturalImagery: 铁匠雕刻柔软的木料——需要极精确的手艺才能保持木料不裂
OneLine: 你赚钱靠耐心和精细。乙木对你来说不是对手，是作品

TenGod: 正财·乙木（合不化时）
Stem: 乙庚相绊
NaturalImagery: 铁锤砸藤蔓——用力过猛，藤蔓反而缠上锤头
OneLine: 你越追越抓不住。这不是能力问题，是这个目标跟你的关系本身就绕着你走

TenGod: 七杀·丙火
Stem: 克我之阳
NaturalImagery: 烈火烧铁矿——温度极高，要么成钢要么烧废
OneLine: 这种压力不是磨炼——是生死考验。撑过去你就是钢

TenGod: 正官·丁火
Stem: 克我之阴
NaturalImagery: 锻造炉的恒温火——精确控温，慢慢炼
OneLine: 最好的压力是持续的、精确的、不致命但不间断的

TenGod: 偏印·戊土
Stem: 生我之阳
NaturalImagery: 厚厚的矿山——铁矿藏在里面
OneLine: 保护太厚了。矿山保护矿石，但也困住了矿石

TenGod: 正印·己土
Stem: 生我之阴
NaturalImagery: 湿润的泥土滋养金属——温柔的培育
OneLine: 最好的支持不是铁墙，是适度的湿润

TenGod: 比肩·庚金
Stem: 同类之阳
NaturalImagery: 一堆铁锭堆在一起——谁也不比谁强
OneLine: 同类太多=没有差异化。一仓库铁不值钱

TenGod: 劫财·辛金
Stem: 同类之阴
NaturalImagery: 粗铁旁边放一颗珠宝——气质完全不同
OneLine: 你的竞争者比你精致，但没你有力。各走各的路

TenGod: 食神·壬水
Stem: 我生之阳
NaturalImagery: 铁被淬入大河——嗞嗞冒烟，定型
OneLine: 你最好的表达是冷静的、沉稳的、一锤定音的

TenGod: 伤官·癸水
Stem: 我生之阴
NaturalImagery: 铁器上的露珠——精致但不是你的本色
OneLine: 你偶尔的敏感让人意外——粗犷的外表下有精微的一面

## 三、庚金十二月意象库（季节变体）

### 春季（寅卯辰月）—— 冰冷休囚的铁

Month: 正月·寅
Scene: 初春冰冷的铁矿石——硬但脆，表面结霜
CoreConflict: 太冷了，还没法加工
Solution: 太阳（丙）升起，炉火（丁）点燃，矿石开始软化

Month: 二月·卯
Scene: 一把铁锤被藤蔓（乙木）缠住——手柄被缠死
CoreConflict: 不是被克，是被缠
Solution: 丁火烧断藤蔓+庚金劈开甲木当柴

Month: 三月·辰
Scene: 被厚土深埋的矿石——上面是一座小山
CoreConflict: 土旺金顽：保护越多越钝
Solution: 甲木根系穿透土层，丁火在洞口等着炼

**春季庚金总方向：** 你在冬眠中。第一步是找到火——不是保护，是锻炼。

### 夏季（巳午未月）—— 火中的铁

Month: 四月·巳
Scene: 刚出矿的铁锭放进锻造炉——温度正好
CoreConflict: 没有困境！这是庚金的出生地（长生）
Solution: 壬水淬火定型——热铁需要冷水

Month: 五月·午
Scene: 烈火锻打中的铁坯——再打一锤就碎了
CoreConflict: 火太旺了，铁快承受不住
Solution: 一桶壬水从天浇下——救命的降温

Month: 六月·未
Scene: 三伏天的旧铁——表面还热，里面已经钝了
CoreConflict: 不是累了，是钝了。麻木比断裂更危险
Solution: 丁火精准加温恢复锋利+甲木劈开当柴

**夏季庚金总方向：** 四月是你的黄金时刻——其他月份要么太热要么钝了。控温是关键。

### 秋季（申酉戌月）—— 当令的铁

Month: 七月·申
Scene: 纯铁——刚出矿，锋利、刚硬、未经打磨
CoreConflict: 最强≠最有用。纯铁不是武器
Solution: 丁火锻造炉——"百炼成钢"

Month: ⭐八月·酉
Scene: 秋天的大刀——锋利到极致的一瞬间
CoreConflict: 阳刃！危险但有力。没有鞘的刀
Solution: 丙火七杀架住刀刃=煞刃格=将军的格局

Month: 九月·戌
Scene: 被黄土埋到胸口的武士——有力但动不了
CoreConflict: 土厚埋金。你在被传统/规矩淹没
Solution: 甲木劈土+壬水冲刷=重见天日

**秋季庚金总方向：** 秋天是你的主场。但"最强"不等于"已成器"——斧头需要被磨，刀需要鞘。

### 冬季（亥子丑月）—— 被冻住的铁

Month: 十月·亥
Scene: 初冬的铁器——开始结霜，表面生锈
CoreConflict: 还没完全冷，但在结霜
Solution: 丁火余温+甲木续柴=趁还有温度赶紧炼

Month: 十一月·子
Scene: 深冬冻铁——完全冻住，一碰就断
CoreConflict: 冻脆了。不是不锋利，是环境把你冻脆了
Solution: 丁甲引火+丙照暖=先解冻再锻造

Month: 十二月·丑
Scene: 深冬湿冷泥浆里的铁坯——又冷又湿又脏
CoreConflict: 最难的月份：冷+湿+埋
Solution: 先丙解冻→再丁炼金→甲木续火

**冬季庚金总方向：** 你被冻住了。第一步不是努力——是找到温暖。"水冷金寒爱丙丁"。

## 四、庚金五行配置变体意象

### 金多（比劫重）

Imagery: 一仓库铁锭
Scene: 堆得满满的——多到没人在乎
Mapping: 你的同类太多了。需要火来炼出差异

Imagery: 铁匠铺里全是锤子
Scene: 没有一把是成品——全是半成品
Mapping: 金多无火不成器。有力气没方向

### 土多（印重）

Imagery: 矿石被整座山压住
Scene: 外面看是山，里面藏着铁矿——但没人知道
Mapping: 你被保护/传统/规矩完全淹没了。甲木=挖掘机

Imagery: 铁甲武士穿了十层盔甲
Scene: 安全到极致，但动不了
Mapping: 你的安全感是你最大的负担

### 水多（食伤重）

Imagery: 铁器泡在水里——生锈
Scene: "秋金锐锐，壬癸相逢总不宜"
Mapping: 你表达太多/泄气太过，锋利在消失

Imagery: 金白水清
Scene: 金属在清水中倒映——清澈、纯净
Mapping: ⭐ 适量水+适温火=庚金最美的状态

### 木多（财重）

Imagery: 一把斧头面对整片森林
Scene: 砍得了但累死了——"木旺能令我自伤"
Mapping: 机会太多，你在消耗自己去追逐所有的树

Imagery: 铁匠接了一百个订单
Scene: 每把刀都赶工——没一把是精品
Mapping: 财多身弱=赚着钱但没命花

### 火多（官煞重）

Imagery: 烈火中的铁——锻造进行时
Scene: 适量=成钢；过量=烧废
Mapping: 庚金不怕火——但有上限。"锻炼太过反主奔流"

Imagery: 铁水在模具里
Scene: 液态金属——已经不是铁了
Mapping: 压力太大你会失去自己的形状——被环境完全重塑

### 缺火

Imagery: 一块原矿放在博物馆
Scene: 标签写着"有价值"但没人加工
Mapping: "庚金无火，非夭则贫"——你有潜力但没人逼你成型

Imagery: 冬天的铁器
Scene: 冷、脆、容易断
Mapping: 你不是不够硬——你缺温度

### 缺木

Imagery: 锋利的斧头没有树可砍
Scene: 有力无处使
Mapping: 你缺的不是能力——是目标。甲木=你的方向

Imagery: 炼好的钢刀放在抽屉里
Scene: 成品了但没用过
Mapping: 你已经成器了——现在需要一个值得你出手的对象

## 五、庚金格局意象库

Pattern: 正官格（丁）
Core_Imagery: 锻造炉里的铁——恒温持续，慢慢成钢
THE_HIT_Seed: 你天生适合被磨炼。最好的你需要持续的压力
BLIND_SPOT_Seed: 你以为你需要自由。实际你需要的是一个好的模具——精确的压力让你成型

Pattern: 七杀格（丙）
Core_Imagery: 烈火中的铁矿——要么成钢要么烧废
THE_HIT_Seed: 你面对的不是普通压力——是生死级别的锻炼
BLIND_SPOT_Seed: 你以为你扛不住。实际你比你以为的更耐烧——巳中有戊土保护你

Pattern: 财格（甲乙）
Core_Imagery: 斧头劈森林——精准有力
THE_HIT_Seed: 你赚钱的方式是直接的、一刀见血的
BLIND_SPOT_Seed: 你以为你需要更多机会（更多树）。实际你需要的是只砍一棵

Pattern: 印绶格（戊己）
Core_Imagery: 被矿山包裹的铁矿——安全但被困
THE_HIT_Seed: 你的支持系统把你埋了
BLIND_SPOT_Seed: 你以为安全=好。实际安全已经变成了牢笼

Pattern: 食神格（壬）
Core_Imagery: 热铁入冷水——嗞嗞冒烟，定型
THE_HIT_Seed: 你最好的表达方式是冷静沉稳的
BLIND_SPOT_Seed: 你以为你需要更多激情。实际你需要的是冷却——让已有的锋利定型

Pattern: 伤官格（癸）
Core_Imagery: 铁器上的露珠——精致意外
THE_HIT_Seed: 你粗犷外表下有精微的一面。让人意外的那部分才是真正的你
BLIND_SPOT_Seed: 你以为你的力量在直接。实际你最打动人的是偶尔的细腻

Pattern: ⭐阳刃格（酉月）
Core_Imagery: 刀的最锋利一瞬——没有鞘的刀
THE_HIT_Seed: 你天生带刃。锋利到让人害怕——包括你自己
BLIND_SPOT_Seed: 你以为你最大的资产是锋利。实际没有火来架住它，锋利就是危险

Pattern: 建禄格（申月）
Core_Imagery: 铁匠自己的铁——仓库满但门口没客人
THE_HIT_Seed: 你什么都有了。唯一缺的是一把火让你成型
BLIND_SPOT_Seed: 你以为你还需要更多原料。你不需要——你需要的是开炉

Pattern: 金水相涵
Core_Imagery: 月光落在大河上——冷冽、壮阔、宁静的光
THE_HIT_Seed: 你最美的状态是"清而冷"——冷静的壮阔
BLIND_SPOT_Seed: 如果只有冷没有目标（木），月光再美也只是照着空河

## 六、产品安全过滤

（同辛金，通用规则）

🚫 禁用: 你会碎/你会烧废/你会断
替代方案: 你在承受超出设计极限的压力

🚫 禁用: 你注定孤独
替代方案: 你的系统设计偏向独立运作

🚫 禁用: 你是脆弱的
替代方案: 你是刚硬的——刚硬意味着需要适度的火力来调配

🚫 禁用: 你的命不好
替代方案: 你的配置有特定的最佳运行条件

🚫 禁用: 你缺X
替代方案: 你的X通道有待激活

🚫 禁用: 庚金无火非夭则贫
替代方案: 你的配置需要持续的锻炼和压力才能发挥——找到你的"火"
