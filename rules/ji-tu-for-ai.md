# 己土 完整规则库

# 第一部分：调候规则（穷通宝鉴）

## 己土总论（跨月通则）

**核心定位（三来源）：**

Source: 滴天髓
Original: "己土卑湿，中正蓄藏。不愁木盛，不畏水狂。火少火晦，金多金光。若要物旺，宜助宜帮"
Core_Imagery: ⭐卑湿、蓄藏、不愁木不畏水

Source: 任铁樵注
Original: "己土为阴湿之地，中正蓄藏，贯八方而旺四季……不愁木盛者，其性柔和，木藉以培养，木不克也。不畏水狂者，其体端凝，水得以纳藏，水不冲也"
Core_Imagery: ⭐柔和=木不克；端凝=水不冲

Source: 任铁樵注
Original: "火少火晦者，丁火也，阴土能敛火，晦火也。金多金光者，辛金也，湿土能生金，润金也"
Core_Imagery: 丁火被己晦/辛金被己润

Source: 穷通宝鉴
Original: 正月"丙为尊……忌见壬水，反为己病"；二月"先取甲木疏之"
Core_Imagery: 春己先丙后甲

Source: 穷通宝鉴
Original: 三夏"取癸为要，次用丙火"/"名水火既济"
Core_Imagery: 夏己癸丙并用

Source: 穷通宝鉴
Original: 三冬"非丙暖不生，取丙为尊"
Core_Imagery: 冬己丙火为尊

### 象法核心意象

- 己土 = 田园/沃土/湿泥/花圃
- 丙火 = 阳光（暖己温土）
- 甲木 = 大树疏土（甲疏己）——但甲己合化土
- 癸水 = 甘霖润田（"无癸曰旱田"）
- 戊土 = 堤防（戊为己的城墙/大山——己依附戊）
- 壬水 = 洪水（"壬乃江湖之水，湖水一发则田园洗荡"——己最忌壬）

**己土的独特性（跟戊土对比）：**

Dimension: 物质
戊土 THE MOUNTAIN: 大山/城墙/高原
己土 THE FIELD: 田园/沃土/湿泥/花圃

Dimension: 本质
戊土 THE MOUNTAIN: **固重刚燥、万物司命**
己土 THE FIELD: **卑湿蓄藏、中正柔和**

Dimension: 对木
戊土 THE MOUNTAIN: "无甲疏劈戊土不灵"
己土 THE FIELD: ⭐ "不愁木盛"（木藉以培养，木不克己）

Dimension: 对水
戊土 THE MOUNTAIN: "无癸滋润万物不长"
己土 THE FIELD: ⭐ "不畏水狂"（水得以纳藏，水不冲己）但**忌壬水**（洪水洗田）

Dimension: 对火
戊土 THE MOUNTAIN: "无丙照暖戊土不生"
己土 THE FIELD: ⭐ "火少火晦"（己土能晦丁火）但需丙暖

Dimension: 对金
戊土 THE MOUNTAIN: 金多泄土
己土 THE FIELD: ⭐ "金多金光"（湿土润金=辛金被己润得更亮）

Dimension: 核心合化
戊土 THE MOUNTAIN: 戊癸合化火
己土 THE FIELD: ⭐ **甲己合化土**

Dimension: 阳刃
戊土 THE MOUNTAIN: 有？（戊午月——奇确认不取阳刃走正印）
己土 THE FIELD: ⭐ **无**（五阴无阳刃）

Dimension: 从势性
戊土 THE MOUNTAIN: 弱（阳干不易从）
己土 THE FIELD: ⭐ **强**（五阴从势无情义）

Dimension: THE HIT方向
戊土 THE MOUNTAIN: 你是大山——承载一切
己土 THE FIELD: ⭐ 你是田园——滋养万物

## 正月己土（寅月）

**原文核心：** "正月己土，田园犹冻，盖因腊气未除，余寒未退，故丙为尊……忌见壬水，反为己病。"

**调候优先级：** **丙火为尊**。忌壬水。

**月令特征：** 寅月甲木当令。甲木克己土但甲己合→情况复杂。

### 调候规则

[Rule]
ID: QT-己-01-A
Condition: 丙火照暖
Judgment: 万物自生
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-01-B
Condition: ⭐壬多+戊出干制
Judgment: "玉堂金马"
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-01-C
Condition: 壬多+乏戊制
Judgment: 平常
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-01-D
Condition: 一派甲木+庚出干+癸丙齐透
Judgment: 名利双全
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-01-E
Condition: 甲多无庚
Judgment: 🚫 "残疾废人"→此配置官煞过重需庚制（+健康免责）
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-01-F
Condition: 一派火+不见水
Judgment: 正月己土湿需丙燥暖，反主厚禄
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-01-G
Condition: 一派戊土+有甲出制
Judgment: 荣显
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-01-H
Condition: 见乙出
Judgment: 🚫 "虽多不能疏土，且乙多者奸诈小人"→乙不能替代甲疏己
Safety: ⚠️
Confidence: 中

**⭐ 正月己土"忌壬水"：** "壬乃江湖之水，湖水一发，则田园洗荡，变为沙土"——己土最忌壬水洪水冲刷。需戊土堤防保护。这是己土跟戊土最大的区别——戊土需要壬水（"无癸滋润万物不长"），己土怕壬水。

**⭐ "乙不能疏土"：** 甲木能疏己土（大树松土），乙木不能（花草无法松田），且乙多者反为小人。引擎需区分甲乙对己土的不同作用。

## 二月己土（卯月）

**原文核心：** "二月己土，阳气渐升，虽禾稼未成，万物出土，田园未展，先取甲木疏之，忌合，次取癸水润之。"

**调候优先级：** 先甲后癸。忌甲己合。

[Rule]
ID: QT-己-02-A
Condition: 甲癸出干+一丙出透
Judgment: 势压百僚
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-02-B
Condition: 甲癸出干
Judgment: 科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-02-C
Condition: 一见壬水
Judgment: 微末官职（壬代替癸效果差）
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-02-D
Condition: 支成木局+庚透
Judgment: 富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-02-E
Condition: 柱多乙木+"庚必输情于乙"
Judgment: 🚫 "狡诈之徒"→庚乙贪合
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-02-F
Condition: 无比印+从杀
Judgment: **从杀者贵**
Safety: ✅
Confidence: 中

**⭐ 二月己土"先甲忌合"：** 甲木疏己=好事，但甲己合化土→甲从疏土工具变成了"己的一部分"→功能丧失。引擎需判断：甲己是否合化成功——合则失甲，不合则甲有用。

## 三月己土（辰月）

**原文核心：** "三月己土，正栽培禾稼之时，先丙后癸，土暖而润，随用甲疏。三者俱透天干，必官居黄阁。"

**调候优先级：** 先丙后癸，甲次之。忌庚。

[Rule]
ID: QT-己-03-A
Condition: 丙癸甲三者俱透
Judgment: 官居黄阁
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-03-B
Condition: 三者透一
Judgment: 科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-03-C
Condition: 以庚金为病
Judgment: ⚠️ 庚金在此月为忌
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-03-D
Condition: 丙癸全无
Judgment: 🚫 "流俗之辈"
Safety: ⚠️
Confidence: 中

## 三夏己土总论

**穷通宝鉴核心：** "三夏己土，杂气才官，禾稼在田，最喜甘沛，取癸为要，次用丙火。夏无太阳禾稼不长。故无癸曰旱田，无丙曰孤阴。"

## 四五六月己土（巳午未月）

**原文核心（合论）：** 专用癸水+丙火。"丙癸两透+辛金生癸=水火既济，鼎甲之人。忌戊癸化合。"

[Rule]
ID: QT-己-04-A
Condition: 丙癸两透+辛金生癸
Judgment: ⭐ **"水火既济"**，鼎甲之人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-04-B
Condition: 忌戊癸化合
Judgment: ⚠️ 戊癸合化火→癸水被合走=旱田
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-04-C
Condition: 有丙无癸+有壬
Judgment: 可但不大发
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-04-D
Condition: 一丙火烈土+丁火制辛+癸水无根
Judgment: 🚫 "孤苦零丁"→如七八月之间旱
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-04-E
Condition: 有壬水+又见庚辛
Judgment: 不作孤看，但恐目疾（+健康免责）
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-04-F
Condition: 壬癸并出破火润土
Judgment: "聪颖特达，富中取贵，转祸为福"
Safety: ✅
Confidence: 中

**⭐ "水火既济"——己土夏月最美配置：** 丙癸两透+辛金生癸=天干有阳光+甘霖+金生水→田园最佳状态。但忌戊癸化合（戊把癸合走=旱田）。

**⭐ 三夏己土"忌壬取癸"（同正月）：** "无癸曰旱田"——但癸=甘霖（温柔），壬=洪水（猛烈）。正月"忌壬"与夏月"取癸"一致——己土需要的是精细的水，不是猛烈的水。

## 三秋己土（申酉戌月）

**原文核心：** "三秋己土，万物收藏之际，外虚内实，寒气渐升，须丙火温之，癸水润之……癸先丙后。"

[Rule]
ID: QT-己-07-A
Condition: 丙癸两透
Judgment: 雁塔题名
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-07-B
Condition: 无癸+两丙透
Judgment: 异途显达或武职
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-07-C
Condition: 有丙火+不见壬癸
Judgment: 🚫 "假道斯文"→表面文雅实无诚意
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-07-D
Condition: 支成金局+癸透有根
Judgment: 家畜万缗，富中取贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-07-E
Condition: 支四库+甲透
Judgment: 富
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-07-F
Condition: 八月支成金局+丙透丁藏
Judgment: ⭐ "名魁天下，五福完人"
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-07-G
Condition: 见戊透
Judgment: 🚫 "主遭凶厄且贫"
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-07-H
Condition: 九月土盛
Judgment: 宜甲木疏之
Safety: ✅
Confidence: 中

**⭐ "见戊透者主遭凶厄"：** 三秋己土忌戊土透干——戊土比肩过重+燥土克水=己土失去调和能力。这是戊己土的核心差异之一——戊土喜戊比肩（"稼穑格"），己土忌戊比肩（破坏己的柔和本质）。

**⭐ "总之三秋己土，先癸后丙，取辛辅癸"：** 辛金生癸水→癸润己土。辛金对己土是食神——温和泄秀+生水的双重功能。

## 三冬己土（亥子丑月）

**原文核心：** "三冬己土，湿泥寒冻，非丙暖不生，取丙为尊，甲木参酌。戊土癸水不用。惟初冬壬旺，取戊制之。"

[Rule]
ID: QT-己-10-A
Condition: 丙透+甲透
Judgment: 科甲有准
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-10-B
Condition: 多壬水+戊透制
Judgment: 安然富中取贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-10-C
Condition: 壬水出干+不见戊
Judgment: 🚫 "富屋贫人"→水浸湖田
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-10-D
Condition: 壬水出干
Judgment: ⭐ "水浸湖田，此人孤苦"。若见火不孤，见土不贫
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-10-E
Condition: 一派癸+不见比劫
Judgment: ⭐ **从才格**，反主富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-10-F
Condition: 一派戊己+甲透制
Judgment: 甲透者富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-10-G
Condition: 一片辛庚+丙火+丁火为助
Judgment: 丙藏=富贵奇特之命
Safety: ✅
Confidence: 中

[Rule]
ID: QT-己-10-H
Condition: 二癸透月时
Judgment: 🚫 "争合，终属劳碌"。得己出干制癸=忠义之士
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-己-10-I
Condition: 年月透辛金
Judgment: 土金伤官，异路功名
Safety: ✅
Confidence: 中

**⭐ "三冬己土戊土癸水不用"：** 冬月己土不用戊土比肩（燥土在冬月无用），不用癸水（冬月已够湿不需要更多水）。但初冬壬旺时需戊制壬——戊只是堤防功能，不是用神。

**⭐ "二癸透月时=争合"：** 两个癸水同时合一个己土=争合。但得一个己出干制癸=化争合为忠义。这是"合=好事但争合=坏事"的经典案例。

## 己土十二月总览表

Month: 正月（寅）
月令: 甲木
核心问题: 田园犹冻
Priority: **丙为尊**+忌壬
Imagery_OneLine: 冻田需阳光
THE_HIT: ⭐壬水洗田是最大危机
Sensitive: 01-E/H

Month: 二月（卯）
月令: 乙木
核心问题: 万物出土
Priority: 先甲后癸+忌合
Imagery_OneLine: 田园待展
THE_HIT: 甲疏己但忌甲己合
Sensitive: 02-E

Month: 三月（辰）
月令: 戊土
核心问题: 栽培时
Priority: 先丙后癸+甲次
Imagery_OneLine: 春耕
THE_HIT: 三者齐透=最高
Sensitive: 03-D

Month: ⭐四月（巳）
月令: 丙火
核心问题: 旱田需水
Priority: 癸为要+丙次
Imagery_OneLine: 旱禾
THE_HIT: ⭐水火既济=最美
Sensitive: 04-D/E

Month: 五月（午）
月令: 丁火
核心问题: 极旱
Priority: 癸为要
Imagery_OneLine: 极旱
THE_HIT: 同四月
Sensitive: —

Month: 六月（未）
月令: 己土
核心问题: 己当令
Priority: 癸丙并用
Imagery_OneLine: 田园当令
THE_HIT: 忌戊癸化合
Sensitive: —

Month: 七月（申）
月令: 庚金
核心问题: 外虚内实
Priority: 癸先丙后
Imagery_OneLine: 秋收前
THE_HIT: 辛辅癸=食神生财
Sensitive: 07-C/G

Month: 八月（酉）
月令: 辛金
核心问题: 金泄土
Priority: 癸先丙后
Imagery_OneLine: 秋实
THE_HIT: ⭐丙透丁藏=五福完人
Sensitive: —

Month: 九月（戌）
月令: 戊土
核心问题: 土盛
Priority: 甲疏+癸丙
Imagery_OneLine: 晚秋
THE_HIT: 甲疏九月土
Sensitive: —

Month: ⭐十月（亥）
月令: 壬水
核心问题: ⭐壬水冲田
Priority: 丙为尊+戊制壬
Imagery_OneLine: 水浸湖田
THE_HIT: ⭐壬水最忌=需戊堤防
Sensitive: 10-C/D

Month: 十一月（子）
月令: 癸水
核心问题: 湿泥寒冻
Priority: 丙为尊
Imagery_OneLine: 冻田
THE_HIT: 丙暖+甲佐
Sensitive: —

Month: 十二月（丑）
月令: 己土
核心问题: 极寒
Priority: 丙为尊
Imagery_OneLine: 冻泥
THE_HIT: 从才路径存在
Sensitive: 10-H

# 第二部分：格局规则（子平真诠）

## 己土十神对照表

Stem: 甲
己土的十神: 正官

Stem: 乙
己土的十神: 七杀

Stem: 丙
己土的十神: 正印

Stem: 丁
己土的十神: 偏印（枭神）

Stem: 戊
己土的十神: 劫财

Stem: 己
己土的十神: 比肩

Stem: 庚
己土的十神: 伤官

Stem: 辛
己土的十神: 食神

Stem: 壬
己土的十神: 正财

Stem: 癸
己土的十神: 偏财

## 己土十二月格局映射表

Month: 正月
Branch: 寅
HiddenStem: 甲丙戊
MainGod: 甲(正官)
Patterns: **正官格**
Notes: ⭐甲己合化土。丙透→正印格

Month: 二月
Branch: 卯
HiddenStem: 乙
MainGod: 乙(七杀)
Patterns: **七杀格**
Notes: ⭐乙木克己但"不愁木盛"。专气

Month: 三月
Branch: 辰
HiddenStem: 戊乙癸
MainGod: 戊(劫财)
Patterns: **杂气劫财**
Notes: 癸透→偏财格；乙透→七杀格

Month: 四月
Branch: 巳
HiddenStem: 丙庚戊
MainGod: 丙(正印)
Patterns: **正印格**
Notes: 庚透→伤官格；戊透→劫财

Month: 五月
Branch: 午
HiddenStem: 丁己
MainGod: 丁(偏印)
Patterns: **偏印格**
Notes: 己透→比肩。丁火被己晦

Month: ⭐六月
Branch: 未
HiddenStem: 己丁乙
MainGod: 己(比肩)
Patterns: **建禄格**
Notes: ⭐己禄在午，但未月己土当令=类建禄。丁透→偏印；乙透→七杀

Month: 七月
Branch: 申
HiddenStem: 庚壬戊
MainGod: 庚(伤官)
Patterns: **伤官格**
Notes: 壬透→正财格

Month: 八月
Branch: 酉
HiddenStem: 辛
MainGod: 辛(食神)
Patterns: **食神格**
Notes: ⭐辛金被己润="金多金光"。专气

Month: 九月
Branch: 戌
HiddenStem: 戊辛丁
MainGod: 戊(劫财)
Patterns: **杂气劫财**
Notes: 辛透→食神格；丁透→偏印格

Month: ⭐十月
Branch: 亥
HiddenStem: 壬甲
MainGod: 壬(正财)
Patterns: **正财格**
Notes: ⭐壬水洗田最忌。甲透→正官格

Month: 十一月
Branch: 子
HiddenStem: 癸
MainGod: 癸(偏财)
Patterns: **偏财格**
Notes: 专气

Month: 十二月
Branch: 丑
HiddenStem: 己辛癸
MainGod: 己(比肩)
Patterns: **杂气比肩**
Notes: 辛透→食神格；癸透→偏财格

**己土格局特殊性（阴干第四个，最后一个）：**

1. **五阴无阳刃**：己土没有阳刃格。未月类建禄处理
2. **甲己合化土**：甲是己的正官→合之则官消→"先甲忌合"
3. **"不愁木盛，不畏水狂"**：己土对官煞（甲乙）和财星（壬癸）有天然免疫力——但"忌壬水"是调候层面的忌（洪水冲田），不是格局层面的忌
4. **"火少火晦"**：己土能晦丁火（偏印）——己的偏印功能被削弱
5. **"金多金光"**：己土生辛金=湿土润金→辛金越多越亮
6. **从势性强**：五阴从势无情义——从财/从杀/从儿都有
7. **戊己差异**：己忌戊透（秋月"见戊透者主遭凶厄"）——戊比肩破坏己的柔和
8. **壬癸差异**：己忌壬（洪水），喜癸（甘霖）——同为财星但性质完全不同

## 己土可成格局详细规则

### 一、建禄格（己土未月/午月）

**出现月份：** 未月（己土当令=类建禄）。己禄在午——午月丁火当令但己有余气。

**⚠️ 注意：** 五阴无阳刃。己土未月走建禄路径。

**核心原则：** 未月己土当令，夏月禾稼在田，最喜甘沛（癸水），次用丙火。

[Rule]
ID: ZP-己-禄-成01
Condition: 未月+丙癸两透+辛金生癸
Judgment: ⭐ **"水火既济"**，鼎甲
Narrative: 阳光+甘霖+金生水=田园极美

[Rule]
ID: ZP-己-禄-成02
Condition: 未月+壬癸并出破火润土
Judgment: "聪颖特达，富中取贵"
Narrative: 水润了你——转祸为福

[Rule]
ID: ZP-己-禄-败01
Condition: 未月+忌戊癸化合
Judgment: ⚠️ 癸被戊合走=旱田
Narrative: 你的甘霖被大山吸走了

[Rule]
ID: ZP-己-禄-败02
Condition: 未月+一丙火烈土+丁制辛+癸无根
Judgment: 🚫 "孤苦零丁"→火过旺水无根
Narrative: 田被烧焦

### 二、正官格 ⭐（己土见甲木=正官）

**出现月份：** 寅月（甲木当令→正官格）

**⭐ 甲己合化土：** 己土日主遇甲木合。甲是己的正官，合之则"官变为比"。

[Rule]
ID: ZP-己-官-成01
Condition: 寅月+甲官+丙印护
Judgment: 官印相生
Narrative: 规则被知识保护

[Rule]
ID: ZP-己-官-成02
Condition: 寅月+甲透+庚出干+癸丙齐透
Judgment: 名利双全
Narrative: 全套配置=完美田园

[Rule]
ID: ZP-己-官-败01
Condition: 寅月+甲多无庚
Judgment: 🚫 "残疾"→官煞过重
Narrative: 太多规则压垮田园

[Rule]
ID: ZP-己-官-败02
Condition: ⭐ 甲己合化+条件满足
Judgment: 官变为比（官消失）
Narrative: 你跟规则合体了——规则不再制约你

**⭐ 甲己合化土的条件（引用月份反向判断清单）：**

[Rule]
ID: ZP-己-化-01
Condition: 辰戌丑未月+甲己合化土条件满足
Judgment: **化气格（甲己化土）**

**甲己合化土的四条件（奇第三批已审核通过）：**
1. 月令是土月（辰戌丑未）或地支土局，且日主坐土支
2. 日主甲木/己土无强根
3. 化神戊土透干
4. 无金透干克化神

**⭐ 甲己合化土的特殊性：** 合化后保留土性→己土"不失本气"（奇在月份反向判断清单中已确认："合化土不失本气"）。这跟辛金遇丙辛合化水（失金性）完全不同。

### 三、七杀格（己土见乙木=七杀）

**出现月份：** 卯月（乙木当令→七杀格）

**⭐ "不愁木盛"：** 滴天髓明确"己土不愁木盛"——但这是因为己土柔和"木藉以培养"。格局法层面乙木仍是七杀，需制化。

[Rule]
ID: ZP-己-煞-成01
Condition: 卯月+辛食神制煞
Judgment: 食神制煞
Narrative: 温和创造驯服了对手

[Rule]
ID: ZP-己-煞-成02
Condition: 卯月+丙印化煞
Judgment: 煞印相生
Narrative: 知识化解了压力

[Rule]
ID: ZP-己-煞-成03
Condition: 卯月+支成木局+庚透
Judgment: 富贵
Narrative: 庚金扫除杂木

[Rule]
ID: ZP-己-煞-成04
Condition: **卯月+无比印+从杀**
Judgment: ⭐ **从杀者贵**
Narrative: 你臣服于木=大贵

[Rule]
ID: ZP-己-煞-败01
Condition: 卯月+柱多乙木+庚乙贪合
Judgment: 🚫 "狡诈之徒"→庚输情于乙
Narrative: 制煞工具被迷走

**⭐ "不愁木盛"的格局法理解：**
- 调候层面：己土柔和，木来了己能培养木根→互利
- 格局层面：乙木仍是七杀，仍需制化。"不愁"不是"无害"，是"承受得住"
- 引擎处理：七杀格正常判断，但己土的身弱判断需考虑"己对木免疫力高"→同等木量下己土比戊土更耐受

### 四、财格（己土见壬水正财/癸水偏财）

**出现月份：** 亥月（壬水当令→正财格）、子月（癸水当令→偏财格）

**⭐ 壬癸差异——己土最关键的分水岭：**
- 壬水=洪水→"田园洗荡"→忌
- 癸水=甘霖→"禾稼甘沛"→喜

[Rule]
ID: ZP-己-财-成01
Condition: 亥月+壬水+戊土制壬+丙火暖
Judgment: 安然富中取贵
Narrative: 有堤防+有温度=洪水变灌溉

[Rule]
ID: ZP-己-财-成02
Condition: 子月+癸水+丙火暖
Judgment: 甘霖润田
Narrative: 温柔的财源滋养你

[Rule]
ID: ZP-己-财-成03
Condition: **冬月+一派癸+不见比劫**
Judgment: ⭐ **从才格**，反主富贵
Narrative: 你变成了水的一部分

[Rule]
ID: ZP-己-财-败01
Condition: 亥月+壬水出干+不见戊
Judgment: 🚫 "水浸湖田，孤苦"
Narrative: 洪水冲垮了田园

[Rule]
ID: ZP-己-财-败02
Condition: 十月+壬水+无火无土
Judgment: 🚫 "孤苦"→火不见不孤，土不见不贫
Narrative: 没有堤防也没有温度

**⭐ "不畏水狂"的格局法理解（同"不愁木盛"）：**
- 滴天髓"不畏水狂"=己土端凝，水得以纳藏
- 但穷通宝鉴"忌壬水"=调候层面洪水冲田
- 引擎处理：壬水正财在格局法上是"我克之财"=好事；但调候层面壬多则"田园洗荡"=坏事。两层分开

### 五、印绶格（己土见丙火正印/丁火偏印）

**出现月份：** 巳月（丙火当令→正印格）、午月（丁火当令→偏印格）

**⭐ "火少火晦"：** 己土能晦丁火——偏印功能被削弱。但丙火不被晦（丙太阳，己田园无法遮太阳）。

[Rule]
ID: ZP-己-印-成01
Condition: 巳月+丙印+癸水润
Judgment: 水火既济
Narrative: 阳光+雨=最美田园

[Rule]
ID: ZP-己-印-成02
Condition: 巳月+支成金局+干出癸水
Judgment: ⭐ "土润金生"，奇格
Narrative: 湿土生金+水润=异路恩荣

[Rule]
ID: ZP-己-印-特01
Condition: 午月+丁火被己晦
Judgment: ⭐ 偏印"火少火晦"
Narrative: 你的滋养源被你自己消解了

[Rule]
ID: ZP-己-印-败01
Condition: 巳月+一派丙火+无癸
Judgment: 🚫 "僧道"→火炎土燥
Narrative: 太阳太烈田地焦裂

### 六、食神格/伤官格（己土见辛金食神/庚金伤官）

**出现月份：** 酉月（辛金当令→食神格）、申月（庚金当令→伤官格）

**⭐ "金多金光"：** 湿土能润金→辛金越多越亮。己土的食神格=最美的泄秀。

[Rule]
ID: ZP-己-食-成01
Condition: 酉月+辛食神+丙癸配合
Judgment: ⭐ "金多金光"——湿土润金
Narrative: 你的产出越多越亮

[Rule]
ID: ZP-己-食-成02
Condition: 八月+支成金局+丙透丁藏
Judgment: ⭐ **"名魁天下，五福完人"**
Narrative: 食神泄秀+印绶双全

[Rule]
ID: ZP-己-伤-成01
Condition: 申月+庚伤官+壬财
Judgment: 伤官生财
Narrative: 激烈创造变钱

[Rule]
ID: ZP-己-食-败01
Condition: 酉月+辛多+无丙丁
Judgment: 金泄土弱
Narrative: 产出太多把自己掏空

### 七、从格系列（己土从势性强）

**⚠️ 奇提示："五阴从势无情义"——己土从势性强。**

[Rule]
ID: ZP-己-从-01
Condition: **卯月+无比印+木旺**
Judgment: **从杀格**
Narrative: 你臣服于最旺的木=大贵

[Rule]
ID: ZP-己-从-02
Condition: **冬月+一派癸+无比劫**
Judgment: **从财格**
Narrative: 你变成了水的一部分

[Rule]
ID: ZP-己-从-03
Condition: **辰戌丑未月+甲己合化土+条件满足**
Judgment: **化气格（甲己化土）**
Narrative: 你和规则合体=保留本气

[Rule]
ID: ZP-己-从-04
Condition: **四季月+支全辰戌丑未+无木**
Judgment: **稼穑格**（专旺格）
Narrative: 你的极致是承载——跟戊土稼穑格一致

[Rule]
ID: ZP-己-从-05
Condition: **秋月+金极旺+无印比**
Judgment: **从儿格（从金）**
Narrative: 你的产出变成你的主人

**⭐ 己土稼穑格：** 跟戊土共享稼穑格。戊土稼穑格的叙事已在第三批锁定（"极致承载"反向叙事——奇确认）。己土稼穑格同理。

### 八、杂气格

[Rule]
ID: ZP-己-杂-01
Condition: 辰月+戊透
Judgment: 劫财

[Rule]
ID: ZP-己-杂-02
Condition: 辰月+癸透
Judgment: 偏财格

[Rule]
ID: ZP-己-杂-03
Condition: 辰月+乙透
Judgment: 七杀格

[Rule]
ID: ZP-己-杂-04
Condition: 戌月+戊透
Judgment: 劫财

[Rule]
ID: ZP-己-杂-05
Condition: 戌月+辛透
Judgment: 食神格

[Rule]
ID: ZP-己-杂-06
Condition: 戌月+丁透
Judgment: 偏印格

[Rule]
ID: ZP-己-杂-07
Condition: 未月+己透
Judgment: 比肩

[Rule]
ID: ZP-己-杂-08
Condition: 未月+丁透
Judgment: 偏印格

[Rule]
ID: ZP-己-杂-09
Condition: 未月+乙透
Judgment: 七杀格

[Rule]
ID: ZP-己-杂-10
Condition: 丑月+己透
Judgment: 比肩

[Rule]
ID: ZP-己-杂-11
Condition: 丑月+辛透
Judgment: 食神格

[Rule]
ID: ZP-己-杂-12
Condition: 丑月+癸透
Judgment: 偏财格

## 己土核心美格/病格标注

Name: ⭐**水火既济**
Nature: **美格（最美）**
Trigger: 三夏丙癸两透+辛生癸
Product_Meaning: 阳光+甘霖=田园极美

Name: ⭐**五福完人**
Nature: **美格**
Trigger: 八月支成金局+丙透丁藏
Product_Meaning: 食神泄秀+印绶双全

Name: **土润金生**
Nature: 美格
Trigger: 巳月支成金局+癸出
Product_Meaning: 湿土生金=奇格

Name: **从杀格**
Nature: 变格
Trigger: 卯月无比印+木旺
Product_Meaning: 臣服于木

Name: **从才格**
Nature: 变格
Trigger: 冬月一派癸无比劫
Product_Meaning: 变成水的一部分

Name: **甲己合化土**
Nature: 变格
Trigger: 四季月+条件满足
Product_Meaning: 合化保留本气

Name: **稼穑格**
Nature: 专旺格
Trigger: 四季月支全辰戌丑未
Product_Meaning: 极致承载（同戊土）

Name: ⭐**壬水洗田**
Nature: **病格（独家）**
Trigger: 壬水多+无戊制
Product_Meaning: 洪水冲垮田园

Name: **庚乙贪合**
Nature: 病格
Trigger: 二月庚乙俱透
Product_Meaning: 制煞工具被迷走

Name: **火少火晦**
Nature: 特殊机制
Trigger: 己土晦丁火
Product_Meaning: 你自己消解了偏印

Name: 争合
Nature: 病格
Trigger: 二癸透月时
Product_Meaning: 两个财源争一个你

## 己土与其他日主的格局交叉验证

### 己土是木日主的财星——反向验证
- 甲木偏财=己土 → 甲木"甲己合化土"=甲被己合走
- 乙木正财=己土 → 乙木"刲羊解牛"=乙木制己土

### 己土是火日主的食伤——反向验证
- 丙火食神=己土 → 丙火"土众生慈"=丙火见己多则失威
- 丁火伤官=己土 → 丁火"伤官伤尽"的土=戊土不是己土

### 己土是金日主的印绶——反向验证
- 庚金偏印=己土 → 庚金"土润则生"=己土润庚
- 辛金正印=己土 → 辛金"己为泥沙"=己土生辛的根基

### 己土是水日主的官煞——反向验证
- 壬水七杀=己土 → 壬水"不畏堤防"=己土不能制壬（需戊）
- 癸水正官=己土 → 癸水"不愁火土"=己土不能完全制癸

### Sam的盘（辛金）视角
Sam的辛金日主，己土是**正印**。

**己土正印对辛金Sam的作用：**
- 正印=知识/母亲/保护
- 己土"卑湿蓄藏"→对辛金来说是**温柔的滋养**（湿土润金="金多金光"）
- Sam月柱戊戌：戊土是偏印（高亢之山），己土是正印（卑湿之田）——Sam同时有山（戊）和田（己）
- 戊己一山一田="高低搭配的保护"：戊提供框架（堤防），己提供滋养（润金）

**CIPHER引擎应用：** 辛金用户遇到己土正印时，叙事方向="你的保护者不是大山（戊），是田园（己）——温柔的、湿润的、无声的滋养。"

# 第三部分：象法意象库

## 己土象法意象库

## 一、己土核心原型

### 古籍原始定位

Source: 滴天髓
Original: "己土卑湿，中正蓄藏。不愁木盛，不畏水狂。火少火晦，金多金光。若要物旺，宜助宜帮"
Core_Imagery: ⭐卑湿、蓄藏、不愁不畏

Source: 任铁樵注
Original: "己土为阴湿之地，中正蓄藏，贯八方而旺四季，有滋生不息之妙用焉"
Core_Imagery: ⭐滋生不息

Source: 任铁樵注
Original: "不愁木盛者，其性柔和，木藉以培养，木不克也"
Core_Imagery: ⭐柔和=木不克

Source: 任铁樵注
Original: "不畏水狂者，其体端凝，水得以纳藏，水不冲也"
Core_Imagery: ⭐端凝=水不冲

Source: 任铁樵注
Original: "火少火晦者，丁火也，阴土能敛火，晦火也。金多金光者，辛金也，湿土能生金，润金也"
Core_Imagery: 晦丁/润辛

Source: 穷通宝鉴
Original: "壬乃江湖之水，湖水一发，则田园洗荡"
Core_Imagery: ⭐壬水=己土的天敌

Source: 穷通宝鉴
Original: "无癸曰旱田，无丙曰孤阴"
Core_Imagery: ⭐癸丙=己土的生命线

### CIPHER核心原型定义

**己土 = THE FIELD**

一句话：**你是一片田园——不抵抗，只蓄藏。万物因你而生。**

核心物质意象（按场景）：
1. **田园/沃土** — 栽培禾稼的土地
2. **花圃** — 滋养花草的湿泥
3. **湿泥** — 卑湿蓄藏的原始状态
4. **堤内田** — 被戊土堤防保护的耕地
5. **沼泽** — 冬月极湿的状态

**己土核心动作：**
- **蓄藏**（纳水纳木）— 己土的本能
- **滋养**（培木润金）— 万物因己而生
- **晦火**（敛丁火）— 天然消解偏印
- **润金**（生辛金）— 湿土让金更亮
- **合化**（甲己合土）— 与规则合一保留本气

## 二、己土与戊土的原型对比（最终版）

Dimension: 物质
戊土 THE MOUNTAIN: 大山/城墙/高原
己土 THE FIELD: 田园/沃土/湿泥/花圃

Dimension: 本质
戊土 THE MOUNTAIN: **固重刚燥、万物司命**
己土 THE FIELD: **卑湿蓄藏、中正柔和**

Dimension: 对木
戊土 THE MOUNTAIN: "无甲疏劈戊土不灵"（需甲来松土）
己土 THE FIELD: ⭐ "不愁木盛"（木来了我培养它）

Dimension: 对水
戊土 THE MOUNTAIN: 需癸滋润（"无癸万物不长"）
己土 THE FIELD: ⭐ "不畏水狂"（水来了我蓄藏它）——但**忌壬水洪水**

Dimension: 对丙火
戊土 THE MOUNTAIN: "无丙照暖戊土不生"（需丙）
己土 THE FIELD: 同样需丙暖（"无丙曰孤阴"）

Dimension: 对丁火
戊土 THE MOUNTAIN: 丁火暖戊=好事
己土 THE FIELD: ⭐ "火少火晦"（己土会消解丁火）

Dimension: 对辛金
戊土 THE MOUNTAIN: 金多泄土（泄气）
己土 THE FIELD: ⭐ "金多金光"（湿土润金=越多越亮）

Dimension: 对戊比肩
戊土 THE MOUNTAIN: 稼穑格=极致承载
己土 THE FIELD: ⭐ **忌戊比肩**（"见戊透者主遭凶厄"）

Dimension: 对壬水
戊土 THE MOUNTAIN: 用壬（"君臣庆会"=壬甲两透）
己土 THE FIELD: ⭐ **忌壬**（"田园洗荡"）

Dimension: 核心合化
戊土 THE MOUNTAIN: 戊癸合化火（失土性→变火）
己土 THE FIELD: ⭐ **甲己合化土**（保留土性→不变）

Dimension: 阳刃
戊土 THE MOUNTAIN: 戊午月→奇确认走正印非阳刃
己土 THE FIELD: ⭐ **无**（五阴无阳刃）

Dimension: 从势性
戊土 THE MOUNTAIN: 弱（阳干不易从）
己土 THE FIELD: ⭐ **强**（五阴从势无情义）

Dimension: 核心美格
戊土 THE MOUNTAIN: 君臣庆会/稼穑格
己土 THE FIELD: ⭐ **水火既济/五福完人**

Dimension: THE HIT方向
戊土 THE MOUNTAIN: 你是大山——承载一切
己土 THE FIELD: ⭐ 你是田园——滋养万物

## 三、己土与十天干的关系意象

TenGod: ⭐正官·甲木
Stem: 克我之阳
NaturalImagery: **大树扎根田园——甲己合化土**
OneLine: ⭐ 你的规则扎根在你身上——然后你们变成了同一片土

TenGod: 七杀·乙木
Stem: 克我之阴
NaturalImagery: 花草扎根田园——"不愁木盛"
OneLine: 花草来了你就养它——柔和到连对手都变成了你的一部分

TenGod: ⭐正印·丙火
Stem: 生我之阳
NaturalImagery: **太阳暖田——"无丙曰孤阴"**
OneLine: ⭐ 你需要太阳——没有阳光的田园是孤阴

TenGod: 偏印·丁火
Stem: 生我之阴
NaturalImagery: **灯照田——"火少火晦"**
OneLine: 你会消解灯火——你的滋养源被你自己吸收了

TenGod: ⭐劫财·戊土
Stem: 同类之阳
NaturalImagery: **大山旁的田园**
OneLine: ⭐ 你需要戊做堤防——但戊比肩太多反而"遭凶厄"

TenGod: 比肩·己土
Stem: 同类之阴
NaturalImagery: 两片田——互相连接
OneLine: 同类让你更大但也更分散

TenGod: ⭐伤官·庚金
Stem: 我生之阳
NaturalImagery: 田里挖出粗金属
OneLine: 激烈的产出消耗你的肥力

TenGod: ⭐食神·辛金
Stem: 我生之阴
NaturalImagery: ⭐ **湿土润珠宝——"金多金光"**
OneLine: ⭐ 你的温柔产出让珠宝越来越亮

TenGod: ⭐正财·壬水
Stem: 我克之阳
NaturalImagery: ⭐ 🚫 **洪水冲田——"田园洗荡"**
OneLine: ⭐ 你最忌讳的财源——壬水洪水会冲垮你

TenGod: 偏财·癸水
Stem: 我克之阴
NaturalImagery: ⭐ **甘霖润田——"无癸曰旱田"**
OneLine: ⭐ 你最需要的财源——温柔的甘霖滋养田园

## 四、己土十二月意象库（季节变体）

### 春季（寅卯辰月）—— 冻田解冻

Month: 正月·寅
Scene: 田园犹冻——腊气未除
CoreConflict: 需丙暖+忌壬冲
Solution: 丙为尊+戊堤防壬

Month: 二月·卯
Scene: 万物出土——田园未展
CoreConflict: 需甲疏土但忌合
Solution: ⭐先甲后癸。甲己合=失甲

Month: 三月·辰
Scene: 春耕——栽培禾稼
CoreConflict: 三者齐备最美
Solution: 丙癸甲俱透=官居黄阁

**春季己土总方向：** 你在春天正在"解冻"——需要阳光（丙）和雨露（癸），还需要有人来松土（甲）。但别让松土的人跟你合体（甲己合）。

### 夏季（巳午未月）—— 旱田需水

Month: 四月·巳
Scene: 禾稼在田——需甘沛
CoreConflict: 旱田
Solution: ⭐癸为要+丙次。水火既济=鼎甲

Month: 五月·午
Scene: 极旱——丁己互晦
CoreConflict: 火晦己晦
Solution: 同四月。忌戊癸化合

Month: ⭐六月·未（建禄）
Scene: ⭐ 己土当令——田园极盛
CoreConflict: 旺但旱
Solution: ⭐水火既济最美。忌戊癸合

**夏季己土总方向：** 你在最旺的时候最渴——"无癸曰旱田"。癸水甘霖是夏季己土的生命线。

### 秋季（申酉戌月）—— 收藏润金

Month: 七月·申
Scene: 万物收藏——外虚内实
CoreConflict: 寒气渐升
Solution: 癸先丙后。辛辅癸

Month: ⭐八月·酉
Scene: ⭐ **金多金光——湿土润辛**
CoreConflict: 金泄土
Solution: ⭐丙透丁藏=五福完人

Month: 九月·戌
Scene: 土盛——需甲疏
CoreConflict: 土太厚
Solution: 甲疏九月土+癸丙

**秋季己土总方向：** 你在秋天"外虚内实"——金多不怕反而越润越亮。"金多金光"是你秋天独有的优势。

### 冬季（亥子丑月）—— 湿泥寒冻

Month: ⭐十月·亥
Scene: ⭐ **水浸湖田——壬水最忌**
CoreConflict: 洪水冲田
Solution: ⭐丙为尊+戊制壬

Month: 十一月·子
Scene: 湿泥寒冻
CoreConflict: 极寒
Solution: 丙为尊+从才路径

Month: 十二月·丑
Scene: 冻泥——极寒极湿
CoreConflict: 极寒
Solution: 丙为尊+甲佐

**冬季己土总方向：** 你在冬天最怕壬水（洪水）和极寒。丙火是唯一的解冻方式。从才格路径存在。

## 五、己土五行配置变体意象

### 木多（官煞重）

Imagery: ⭐不愁木盛
Scene: ⭐ 大树扎根田园=我培养它
Mapping: 你柔和到连对手都变成了养分

Imagery: 甲己合化
Scene: 大树跟田合为一体
Mapping: 你和对手合体=保留本气

Imagery: 官煞过重
Scene: 🚫 太多大树压垮田园
Mapping: 木虽"不愁"但太多仍需制

### 水多（财重）

Imagery: ⭐不畏水狂
Scene: ⭐ 水来了田园蓄藏
Mapping: 天性上你能纳水——但壬水例外

Imagery: ⭐壬水洗田
Scene: ⭐ 🚫 洪水冲垮田园
Mapping: 你最怕的财源=猛烈的大水

Imagery: 癸水润田
Scene: ⭐ 甘霖滋养=最美
Mapping: 温柔的财源才是你需要的

Imagery: 从才格
Scene: 一派癸无比劫=从财
Mapping: 你变成了水的一部分

### 火多（印重）

Imagery: 丙暖田
Scene: ⭐ 阳光暖田=万物生
Mapping: 你需要太阳——"无丙曰孤阴"

Imagery: 火少火晦
Scene: ⭐ 己土消解丁火
Mapping: 你天然会消化掉小火——灯烛不够

Imagery: 火炎土燥
Scene: 🚫 太阳太烈=田地焦裂
Mapping: 太多太阳把你烤焦了

### 金多（食伤重）

Imagery: ⭐金多金光
Scene: ⭐ ⭐ 湿土润辛金=越多越亮
Mapping: 你的产出越多越美——这是你独有的优势

Imagery: 土金伤官
Scene: 庚金泄己
Mapping: 激烈产出消耗你——但冬月异路功名

Imagery: 五福完人
Scene: ⭐ 八月金局+丙透丁藏
Mapping: 食神泄秀+印绶暖局=完美

### 土多（比劫重）

Imagery: ⭐忌戊比肩
Scene: ⭐ 🚫 大山压在田上
Mapping: 戊土比肩破坏你的柔和本质

Imagery: 稼穑格
Scene: 支全辰戌丑未=纯土
Mapping: 极致承载——同戊土叙事

Imagery: 一派戊己+甲制
Scene: 有甲疏土=富贵
Mapping: 太多土需要木来松

### 缺丙

Imagery: 孤阴
Scene: 🚫 "无丙曰孤阴"
Mapping: 没有太阳的田园=万物不长

### 缺癸

Imagery: 旱田
Scene: 🚫 "无癸曰旱田"
Mapping: 没有甘霖的田园=禾稼枯死

## 六、己土格局意象库

Pattern: 建禄格（未月）
Core_Imagery: 田园当令——极盛但旱
THE_HIT_Seed: 你在最旺时最需要水
BLIND_SPOT_Seed: 你以为旺=好。实际你渴死了

Pattern: ⭐**水火既济**
Core_Imagery: ⭐ ⭐ 阳光+甘霖=田园极美
THE_HIT_Seed: 丙+癸+辛=完美配置
BLIND_SPOT_Seed: 你以为你需要更多土。实际你需要水和光

Pattern: ⭐**五福完人**
Core_Imagery: ⭐ 食神泄秀+印绶双全
THE_HIT_Seed: 你在最好的配置下=名魁天下
BLIND_SPOT_Seed: —

Pattern: 正官格（寅月）
Core_Imagery: 大树扎根田园
THE_HIT_Seed: 规则扎在你身上——你们合体了
BLIND_SPOT_Seed: —

Pattern: 七杀格（卯月）
Core_Imagery: 花草扎根——不愁木盛
THE_HIT_Seed: 你柔和到连对手都养了
BLIND_SPOT_Seed: 你以为木是威胁。实际你能容纳

Pattern: ⭐财格（亥/子月）
Core_Imagery: 水来了——壬忌癸喜
THE_HIT_Seed: 同为水，洪水杀你甘霖救你
BLIND_SPOT_Seed: ⭐ 你以为所有钱都是好事。实际壬水会冲垮你

Pattern: 印绶格（巳/午月）
Core_Imagery: 阳光暖田/灯被晦
THE_HIT_Seed: 你需要太阳不是灯烛——丙>丁
BLIND_SPOT_Seed: —

Pattern: ⭐食神格（酉月）
Core_Imagery: ⭐ 金多金光——湿土润金
THE_HIT_Seed: 你的产出越多越亮
BLIND_SPOT_Seed: 你以为产出会消耗你。实际己土润金=双赢

Pattern: 伤官格（申月）
Core_Imagery: 粗金泄土
THE_HIT_Seed: 激烈产出消耗肥力
BLIND_SPOT_Seed: —

Pattern: **甲己合化土**
Core_Imagery: ⭐ 你和大树合为一片土
THE_HIT_Seed: 你的对手变成了你——而且你没有变
BLIND_SPOT_Seed: 你以为合体=失去自己。实际你保留了本气

Pattern: **从杀格**
Core_Imagery: 臣服于木
THE_HIT_Seed: 你臣服于最旺的木=大贵
BLIND_SPOT_Seed: —

Pattern: **从才格**
Core_Imagery: 变成水的一部分
THE_HIT_Seed: 你放弃做田——变成了水
BLIND_SPOT_Seed: —

Pattern: **稼穑格**
Core_Imagery: 极致承载（同戊土）
THE_HIT_Seed: 你的极致不是做自己——是承载一切
BLIND_SPOT_Seed: —

Pattern: ⭐**壬水洗田**
Core_Imagery: ⭐ 🚫 洪水冲垮田园
THE_HIT_Seed: 你最害怕的是"猛烈的钱"
BLIND_SPOT_Seed: —

## 七、己土专属古典名言映射

古籍名言: **"己土卑湿，中正蓄藏"**
现代CIPHER解读: ⭐ 你不高不猛——但你能蓄藏一切

古籍名言: **"不愁木盛"**
现代CIPHER解读: ⭐ ⭐ 木来了你就养它——你柔和到连对手都变成养分

古籍名言: **"不畏水狂"**
现代CIPHER解读: ⭐ 水来了你就蓄藏——天性能纳百川（但忌壬水洪水）

古籍名言: **"火少火晦"**
现代CIPHER解读: 你天然消解小火——丁火偏印被你吸收

古籍名言: **"金多金光"**
现代CIPHER解读: ⭐ ⭐ 湿土润金——你的产出越多越亮

古籍名言: **"若要物旺，宜助宜帮"**
现代CIPHER解读: 你需要帮助才能真正发力——丙火去湿+戊土助基

古籍名言: "壬乃江湖之水，田园洗荡"
现代CIPHER解读: 🚫 改写：洪水型财源会冲垮你的根基——需戊堤防

古籍名言: "无癸曰旱田"
现代CIPHER解读: ⭐ 没有甘霖的你=旱田=禾稼枯死

古籍名言: "无丙曰孤阴"
现代CIPHER解读: ⭐ 没有太阳的你=孤阴=万物不长

古籍名言: "水火既济，鼎甲之人"
现代CIPHER解读: ⭐ ⭐ 丙+癸+辛=田园最美配置

古籍名言: "名魁天下，五福完人"
现代CIPHER解读: ⭐ 八月丙透丁藏+金局=完美一生

古籍名言: "见戊透者主遭凶厄"
现代CIPHER解读: 🚫 改写：戊土比肩过重会破坏你的柔和——你不需要另一座山

古籍名言: "乙多者奸诈小人"
现代CIPHER解读: 🚫 改写：乙木不能替代甲木疏己的功能（安全过滤表处理）

古籍名言: "二癸争合"
现代CIPHER解读: 🚫 改写：两个财源争一个你=内耗

## 八、己土+用神组合的经典叙事

### 用神是丙火（正印）—— 最暖
- 场景：太阳暖田="无丙曰孤阴"
- 叙事：你没有太阳就是孤阴——万物不长。丙火是你的第一需求。
- 对象：需要"平台/背景/光环"才能发力的专业人士

### 用神是癸水（偏财）—— 最润
- 场景：甘霖润田="无癸曰旱田"
- 叙事：你需要的不是大河（壬）而是甘霖（癸）。温柔持续的财源比猛烈的暴富好一百倍。
- ⚠️ 壬水正财反为忌——叙事方向完全相反
- 对象：长期稳定收入型人才、厌恶暴富风险的保守投资者

### 用神是甲木（正官）—— 最疏
- 场景：大树疏土="先取甲木疏之"
- 叙事：你需要有人来"松土"——甲木是那个让你变活的人。但⚠️忌甲己合（合了就不疏了）。
- 对象：需要"mentor"来激活的人才、需要"外部冲击"才能行动的人

### 用神是辛金（食神）—— 最润
- 场景：湿土润珠宝="金多金光"
- 叙事：你的产出不消耗你——反而让你更美。辛金食神是你最天然的泄秀方式。
- 对象：手工艺/精品/教育——温和型创作者

### 用神是戊土（劫财）—— 最护（但双刃剑）
- 场景：大山做堤防="须戊作堤以保园圃"
- 叙事：你需要戊土做堤防挡壬水洪水——但⚠️戊透太多反而"遭凶厄"。适量的戊=保护，过量的戊=压垮。
- 对象：需要"框架/规则"保护但不能被框架限制的创业者

## 九、产品安全过滤（已查通用表v1.1）

AncientTerm: 残疾废人
Rewrite: 此配置官煞过重需庚制（+健康免责）
TableEntry: v1.1器官层级

AncientTerm: 奸诈小人
Rewrite: 此配置乙木不能替代甲木疏己
TableEntry: 基础过滤表

AncientTerm: 贫贱之徒
Rewrite: 此配置需特定用神才能发挥
TableEntry: 基础过滤表

AncientTerm: 僧道
Rewrite: 独处型创作路径
TableEntry: 基础过滤表

AncientTerm: 流俗之辈
Rewrite: 此配置需丙癸才能发挥
TableEntry: 基础过滤表

AncientTerm: 富屋贫人
Rewrite: 外在丰富但内在需被看见
TableEntry: 基础过滤表

AncientTerm: 孤苦
Rewrite: 此配置需火暖土止水
TableEntry: 基础过滤表

AncientTerm: 假道斯文终无诚实
Rewrite: 此配置有丙无癸=表面温暖内核干旱
TableEntry: 基础过滤表

AncientTerm: 狡诈之徒
Rewrite: 此配置庚乙贪合→制煞工具被迷走
TableEntry: 基础过滤表

AncientTerm: 遭凶厄且贫
Rewrite: 此配置忌戊比肩过重
TableEntry: 基础过滤表

AncientTerm: 目疾心肾肝脏之灾
Rewrite: 健康方面需关注（+免责声明。引用v1.1通用器官表：火=心血管/视力；水=泌尿/肾脏；木=肝胆）
TableEntry: v1.1器官层级

## 十、与其他日主的意象对偶

### 戊土视角 × 己土视角

Scenario: 戊己同见
戊土的意象: 大山旁的田园
己土的意象: 我在大山脚下

Scenario: 对木
戊土的意象: "无甲不灵"（需甲）
己土的意象: ⭐ "不愁木盛"（不怕木）

Scenario: 对壬水
戊土的意象: 用壬（君臣庆会）
己土的意象: ⭐ 🚫 忌壬（田园洗荡）

Scenario: 稼穑格
戊土的意象: 极致承载
己土的意象: 同——共享稼穑格

### 甲木视角 × 己土视角

Scenario: 甲己合
甲木的意象: 甲被己合走
己土的意象: ⭐ 我跟大树合体——保留本气

Scenario: 甲疏己
甲木的意象: 大树松土
己土的意象: 你来松土=我才能活

### 辛金视角 × 己土视角

Scenario: 己生辛
辛金的意象: 己土=正印=温柔滋养
己土的意象: ⭐ 我润你=金多金光

Scenario: 金白水清
辛金的意象: 辛金最美格
己土的意象: 我是让你美的根基

### 癸水视角 × 己土视角

Scenario: 癸润己
癸水的意象: 甘霖滋花
己土的意象: ⭐ 你是我最需要的水

Scenario: 戊癸合
癸水的意象: 戊把癸合走
己土的意象: ⭐ 戊合了癸=我的甘霖被大山抢了

### 壬水视角 × 己土视角

Scenario: 壬克己
壬水的意象: 大水冲土
己土的意象: ⭐ 🚫 洪水冲垮我的田

Scenario: 壬+戊
壬水的意象: 壬被戊堤防
己土的意象: 戊堤防救了我

### Sam的盘（辛金）视角
Sam的辛金日主，己土是**正印**。Sam月柱**戊戌**：戊是偏印，戌中藏戊辛丁。

**己土正印对辛金Sam的作用：**
- 正印=知识/母亲/滋养/保护
- 己土"卑湿蓄藏"→对辛金来说是"温柔的根基"
- "金多金光"=己土润辛金=Sam的知识底蕴让他的精致更亮
- Sam有戊（偏印=高山框架）+己（正印=田园滋养）=双重保护

**己土vs戊土对Sam的不同作用：**
- 戊土偏印：高亢的框架/规则/制度→给Sam"结构"
- 己土正印：卑湿的滋养/培育/蓄藏→给Sam"养分"
- 两者配合=Sam的辛金被"山上的田园"滋养——框架+养分双全

**CIPHER引擎应用：** 辛金用户遇到己土正印时：
- 叙事方向="你的根基不是大山——是温柔的田园。它无声地滋养你，让你越来越亮"
- 对比戊土偏印的"高亢框架"——己土正印是"沉默的培育"

# 🎉 10/10 日主规则提取全部完成
