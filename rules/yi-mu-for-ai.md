# 乙木 完整规则库

# 第一部分：调候规则（穷通宝鉴）

## 乙木总论（跨月通则）

**核心定位（三来源）：**

Source: 滴天髓
Original: "乙木虽柔，刲羊解牛。怀丁抱丙，跨凤乘猴。虚湿之地，骑马亦忧。藤萝系甲，可春可秋"
Core_Imagery: ⭐柔而能克刚、怀丁抱丙、藤萝系甲

Source: 任铁樵注
Original: "乙木者，甲之质，而承甲之生气也。春如桃李，夏如禾稼，秋如桐桂，冬如奇葩"
Core_Imagery: 四季变形——每季一种植物

Source: 穷通宝鉴
Original: 三春用丙癸、三夏专用癸水、三秋先丙后癸、三冬用丙火
Core_Imagery: 各季调候差异大

Source: 渊海子平
Original: "活木忌埋根之铁，支下有庚辛，戕贼其根，木则朽矣"
Core_Imagery: 活木忌金埋根

Source: 子平真诠
Original: "乙木虽柔……怀丁抱丙，跨凤乘猴"
Core_Imagery: 有丙丁则不怕庚辛

### 象法核心意象

- 乙木 = 花草/藤萝/桃李/禾稼/桐桂/奇葩（四季各不同）
- 丙火 = 太阳（温暖乙木）
- 癸水 = 雨露（滋润乙木）
- 甲木 = 大树/乔木（"藤萝系甲"=乙木依附甲木）
- 庚金 = 斧头（克乙，但乙庚合化金）
- 辛金 = 剪刀（七杀，秋金最忌）

**乙木的独特性（跟甲木对比）：**

Dimension: 物质
甲木 THE PILLAR: 大树/栋梁/参天巨木
乙木 THE VINE: 花草/藤萝/桃李/禾稼

Dimension: 本质
甲木 THE PILLAR: **纯阳猛烈、参天雄壮**
乙木 THE VINE: **阴柔至弱、柔中有刚**

Dimension: 对金
甲木 THE PILLAR: "春不容金"（怕金）
乙木 THE VINE: ⭐ "怀丁抱丙，跨凤乘猴"（有火则不怕金）

Dimension: 对土
甲木 THE PILLAR: 甲克戊（大树劈山）
乙木 THE VINE: ⭐ "刲羊解牛"（柔木能制柔土——丑未月乙木能克）

Dimension: 核心机制
甲木 THE PILLAR: 庚劈甲=斧砍大树
乙木 THE VINE: ⭐ **乙庚合化金**=藤缠斧头

Dimension: 依附性
甲木 THE PILLAR: 独立自主
乙木 THE VINE: ⭐ **藤萝系甲**=依附甲木才能"可春可秋"

Dimension: 从势性
甲木 THE PILLAR: 甲木不易从（三春甲木"素无从才从杀从化之理"）
乙木 THE VINE: ⭐ **从势性强**（五阴从势无情义）

Dimension: 阳刃
甲木 THE PILLAR: 有（甲卯月）
乙木 THE VINE: ⭐ **无**（五阴无阳刃）

Dimension: THE HIT方向
甲木 THE PILLAR: 你是参天大树——直立不弯
乙木 THE VINE: ⭐ 你是藤萝——柔软但能绞杀

## 三春乙木总论

**穷通宝鉴核心：** 三春乙木以丙癸为用。正月先丙后癸，二月端用丙癸，三月先癸后丙。

**春乙=桃李**——春如桃李，金克则凋。春月乙木得令但柔弱，需要阳光（丙）和雨露（癸）。

## 正月乙木（寅月）

**原文核心：** "正月乙木……先用丙火解寒，但不可缺癸水。"（正月与甲木同论，但乙木更需丙暖）

**调候优先级：** 先丙后癸。

**月令特征：** 寅月甲木当令。乙木在寅有余气——但寅月余寒未除。

### 调候规则

[Rule]
ID: QT-乙-01-A
Condition: 丙癸齐透
Judgment: 富贵双全
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-01-B
Condition: 癸藏丙透
Judgment: 名寒木向阳
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-01-C
Condition: 无丙癸
Judgment: 平常人
Safety: ⚠️
Confidence: 中

**象法意象：** 正月乙木=早春的桃树——还冻着，需要阳光融雪。

## 二月乙木（卯月=建禄）

**原文核心：** "二月乙木，端用丙癸，或支成木局，有癸透乃作贵命，更得丙泄木气，上上之命。"

**调候优先级：** 丙癸并用。

**月令特征：** 卯月乙木当令（**乙木建禄月**）。木旺，需要丙泄秀+癸滋润。

### 调候规则

[Rule]
ID: QT-乙-02-A
Condition: 支成木局+癸透+丙泄
Judgment: 上上之命
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-02-B
Condition: 癸透但须透
Judgment: 贵命
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-02-C
Condition: 水多困丙+多戊化癸
Judgment: 🚫 下格→此配置水土干扰了用神
Safety: ⚠️
Confidence: 中

## 三月乙木（辰月）

**原文核心：** "三月乙木，阳气愈炽，先癸后丙。癸丙两透，不见己庚，玉堂之客。"

**调候优先级：** 先癸后丙。忌见己庚。

**月令特征：** 辰月戊土当令。乙木在辰有余气（辰中乙木余气）。

### 调候规则

[Rule]
ID: QT-乙-03-A
Condition: 癸丙两透+不见己庚
Judgment: 玉堂之客
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-03-B
Condition: 见己庚
Judgment: 平常之人
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-03-C
Condition: 一乙逢庚+不见己
Judgment: 小富贵但不显达
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-03-D
Condition: 庚己混杂+丙癸全
Judgment: 下格
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-03-E
Condition: 水局+丙戊高透
Judgment: 科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-03-F
Condition: 全无丙戊+支合水局
Judgment: 离乡之命
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-03-G
Condition: 一派壬水
Judgment: 🚫 "不特贫贱，而且夭折"→ 此配置需戊己制水
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-03-H
Condition: 庚辰时月="二庚争合"
Judgment: 🚫 "贫贱之辈"→ 两庚争合一乙
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-03-I
Condition: 年干见丁破庚+从化
Judgment: 武职之权
Safety: ✅
Confidence: 中

**⭐ "二庚争合"：** 三月乙木遇两个庚金同时合乙——争合反而破格。但如果年干丁火破一庚，则从化有功。

## 三夏乙木总论

**穷通宝鉴核心：** "三夏乙木，木性枯焦。四月专尚癸水。五六月先丙后癸。"

**夏乙=禾稼**——夏如禾稼，水滋得生。夏月乙木最需要水。

## 四月乙木（巳月）

**原文核心：** "四月乙木，自有丙火，端取癸水为尊。四月乙木专用癸水，丙火酌用，虽以庚辛佐癸，须辛透为清。"

**调候优先级：** **专用癸水**。辛透为清。

**月令特征：** 巳月丙火当令。乙木枯焦——专需水救。

### 调候规则

[Rule]
ID: QT-乙-04-A
Condition: 癸透+庚辛又透
Judgment: 科甲定然
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-04-B
Condition: 独一点癸水+无金
Judgment: 水无根，秀才小富
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-04-C
Condition: 土多困癸
Judgment: 🚫 "贫贱"→ 此配置用神被困
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-04-D
Condition: 丙戊太多+支成火局
Judgment: 🚫 "瞽目之流"→ 健康方面，眼目方向值得长期关注（+强制免责声明）
Safety: ⚠️
Confidence: 中

**⭐ 四月乙木"瞽目之流"：** 跟丙火五月的眼目警示类似——火旺木焦伤眼。已查通用安全过滤表v1.1处理。

## 五月乙木（午月）

**原文核心：** "五月乙木，丁火司权，禾稼俱旱……癸透有根，富贵双全。"

**调候优先级：** 上半月用癸水，下半月丙癸齐用。

**月令特征：** 午月丁火当令。乙木"气散之文"——火泄乙精。

### 调候规则

[Rule]
ID: QT-乙-05-A
Condition: 癸透有根
Judgment: 富贵双全
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-05-B
Condition: 庚辛年上+癸透时干
Judgment: 科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-05-C
Condition: 无癸
Judgment: 常人
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-05-D
Condition: 丙透+支成火局
Judgment: 🚫 "阳焦木性，残疾，无癸必夭"→ 此配置火过旺需水救（+健康免责）
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-05-E
Condition: 火土太多
Judgment: 🚫 "僧道门下闲人"→ 独处型路径
Safety: ⚠️
Confidence: 中

## 六月乙木（未月）

**原文核心：** "六月乙木，木性且寒，柱多金水，丙火为尊。"

**调候优先级：** 丙火为尊。癸水亦需。

**月令特征：** 未月己土当令+火库。⭐ "刲羊解牛"——乙木坐未月=割宰羊（未=羊）。

### 调候规则

[Rule]
ID: QT-乙-06-A
Condition: 支成水局+乙得无伤+癸水透干
Judgment: 大富大贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-06-B
Condition: 无癸
Judgment: 常人，运不行北困苦一生
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-06-C
Condition: 甲木高透制伏土神
Judgment: "去浊留清"，俊秀
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-06-D
Condition: 土多乏甲
Judgment: 🚫 "庸人而已"→ 此配置需甲制土
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-06-E
Condition: 无水+无比劫出干
Judgment: **弃命从才**，富大贵小，贤妻
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-06-F
Condition: 一派戊土+不见比肩
Judgment: 🚫 "才多身弱，富屋贫人"→ 此配置需比劫帮身
Safety: ⚠️
Confidence: 中

**⭐ 六月用癸忌戊己：** "凡五六月乙木，气退枯焦，用癸水切忌戊己杂乱，则为下格。"——夏月癸水被戊己克是大忌。

## 三秋乙木总论

**穷通宝鉴核心：** "三秋乙木，金神司令，先丙后癸，惟九月端用癸水。"

**秋乙=桐桂**——秋如桐桂，金旺火制。

**⭐ "秋乙逢金，非贫即夭"——秋金克木最危险。**

## 七月乙木（申月）

**原文核心：** "七月乙木，庚金乘令，庚虽输情于乙妹，怎奈干乙难合支金。"

**调候优先级：** 丙火为先。己土亦用。

**月令特征：** 申月庚金当令。⭐ **乙庚合**——庚"输情于乙"但"干乙难合支金"。

### 调候规则

[Rule]
ID: QT-乙-07-A
Condition: 丙透干+巳出埋金
Judgment: 科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-07-B
Condition: 己透+加丙
Judgment: 上命
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-07-C
Condition: 庚多+无丙己
Judgment: 平常人物
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-07-D
Condition: 生辰时
Judgment: ⭐ **乙庚合化金（从化）**，反主富贵
Safety: ✅
Confidence: 中

**⭐ 乙庚合化金：** "凡化合格皆以所生之神为用。化金者，戊为用神，特忌丙丁煅炼破格。"——乙庚合化金用戊土，忌火。

## 八月乙木（酉月）

**原文核心：** "八月乙木，芝兰禾稼均退。以丹桂为乙木。白露后桂蕊未开，端用癸水以滋桂萼。秋分后桂花已开，却喜向阳，又宜用丙。"

**调候优先级：** 白露后先癸，秋分后先丙。

**月令特征：** 酉月辛金当令。⭐ **辛金七杀克乙木**——秋金最危险。

### 调候规则

[Rule]
ID: QT-乙-08-A
Condition: 丙癸两透
Judgment: 科甲名臣
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-08-B
Condition: 支成金局+宜暗藏丁
Judgment: 丁制金（暗制）
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-08-C
Condition: 无水火
Judgment: 🚫 "劳碌"→ 此配置需丙癸才能发挥
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-08-D
Condition: 癸在年干+丙透时干
Judgment: ⭐ **"木火文星"**，定主上达
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-08-E
Condition: 四柱不见丙癸
Judgment: 🚫 下格
Safety: ⚠️
Confidence: 中

**⭐ "以丹桂为乙木"：** 八月乙木=丹桂（桂花树）。白露前桂蕊未开需癸水滋养；秋分后桂花已开需丙火向阳——同一个月份前后调候不同。

## 九月乙木（戌月）

**原文核心：** "九月乙木，根枯叶落，必赖癸水滋养。如见甲申时，名为藤萝系甲，可秋可冬。"

**调候优先级：** 癸水为尊。辛金发水之源。

**月令特征：** 戌月戊土当令。乙木**根枯叶落**——最弱的状态。

### 调候规则

[Rule]
ID: QT-乙-09-A
Condition: 癸水+辛金发水之源
Judgment: 科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-09-B
Condition: 有癸无辛
Judgment: 常人
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-09-C
Condition: 有辛无癸
Judgment: 🚫 "贫贱"→ 此配置有源无水
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-09-D
Condition: 四柱壬多
Judgment: 🚫 "寻常之辈"→ 壬水难生乙（壬大水不养小草）
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-09-E
Condition: 支多戊土+天干戊土+无比劫
Judgment: **从才格**
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-09-F
Condition: ⭐ 见甲申时
Judgment: ⭐ **"藤萝系甲，可秋可冬"**
Safety: ✅
Confidence: 中

**⭐ "藤萝系甲"：** 九月乙木最经典的意象——枯萎的藤萝攀附在大树（甲木）上=可秋可冬。这是乙木"依附性"的核心体现。

**⭐ 壬水难生乙：** "四柱壬多，水难生乙"——壬水是江河洪水，浇不了小花草。癸水（甘霖）才是乙木需要的水。这跟癸水日主"辛金优于庚金"的逻辑一致——阴干需要阴性的资源。

## 三冬乙木总论

**穷通宝鉴核心：** "三冬乙木用丙火解冻。十月先丙后戊；十一月端用丙火（不宜癸）；十二月先丙后壬。"

**冬乙=奇葩**——冬如奇葩，火湿土培。

## 十月乙木（亥月）

**原文核心：** "十月乙木，木不受气，而壬水司令，取丙为用，戊土次之。"

**调候优先级：** 先丙后戊。

**月令特征：** 亥月壬水当令。乙木在亥"木不受气"——壬水太旺反而泡坏乙木。

### 调候规则

[Rule]
ID: QT-乙-10-A
Condition: 丙戊两透
Judgment: 科甲定然
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-10-B
Condition: 有丙无戊
Judgment: 不科甲亦入儒林
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-10-C
Condition: 水多无戊
Judgment: 🚫 "乙性漂浮，流荡之徒"→ 此配置需戊土制水
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-10-D
Condition: 支成木局+癸出+戊为尊+丙透
Judgment: 科甲之人
Safety: ✅
Confidence: 中

## 十一月乙木（子月）

**原文核心：** "十一月乙木，花木寒冻，一阳来复，喜用丙火解冻，则花木有向阳之意，**不宜用癸以冻花木**，故端用丙火。"

**调候优先级：** **端用丙火。忌癸水**（癸水反而冻花木）。

**月令特征：** 子月癸水当令。乙木被冻——**十一月乙木不用癸水**（全年唯一忌癸的月份）。

### 调候规则

[Rule]
ID: QT-乙-11-A
Condition: 一二丙火出干+无癸制
Judgment: 科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-11-B
Condition: 丙藏支内
Judgment: 选拔恩封
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-11-C
Condition: 壬癸出干+有戊制
Judgment: 能人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-11-D
Condition: 壬透无戊
Judgment: 🚫 "贫贱"→ 此配置需戊土制水
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-11-E
Condition: 支成水局+丙丁全无+虽有戊制
Judgment: 🚫 "贫乏到老"→ 此配置无火无温度
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-11-F
Condition: 丁火有亦如无
Judgment: **丁乃灯烛之火，岂能解严寒之冻**
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-11-G
Condition: 一派丁火
Judgment: 🚫 "大奸大诈"→ 此配置丁火不能解冻反而虚假
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-乙-11-H
Condition: 丁火见甲
Judgment: ⭐ "麟趾振振，芝兰绕膝"（丁火有甲引=真正的温暖）
Safety: ✅
Confidence: 中

[Rule]
ID: QT-乙-11-I
Condition: 成水局+壬癸两透+则木浮
Judgment: 🚫 "不特贫贱，且夭折"→ 需戊救
Safety: ⚠️
Confidence: 中

**⭐ 十一月乙木"不宜癸水"：** 这是全10日主中极罕见的"忌自己的印星"的情况。癸水对乙木通常是甘霖——但冬月花木已冻，再加癸水反而"以冻花木"。引擎需标注此特例。

**⭐ "丁乃灯烛之火，岂能解严寒之冻"：** 乙木十一月明确指出丁火不能替代丙火。丙=太阳=能解冻；丁=灯烛=不够。这是丙丁差异在调候层面最清晰的表述。

## 十二月乙木（丑月）

**原文核心：** 与十一月同理——丙火为尊。但十二月更寒。

**调候优先级：** 丙火为尊。甲木为佐。

### 调候规则

（穷通宝鉴把十一月十二月合论，具体处理同QT-乙-11系列）

## 乙木十二月总览表

Month: 正月（寅）
月令: 甲木
核心问题: 余寒未除
Priority: 先丙后癸
Imagery_OneLine: 早春桃树
THE_HIT: 阳光+雨露
Sensitive: —

Month: ⭐二月（卯·建禄）
月令: 乙木
核心问题: 木旺需泄
Priority: 丙癸并用
Imagery_OneLine: 盛放桃李
THE_HIT: 有花有果需要阳光雨露
Sensitive: 02-C

Month: 三月（辰）
月令: 戊土
核心问题: 阳气炽
Priority: 先癸后丙
Imagery_OneLine: 暮春残花
THE_HIT: 忌庚己混杂
Sensitive: 03-G/H

Month: 四月（巳）
月令: 丙火
核心问题: 枯焦
Priority: **专用癸水**
Imagery_OneLine: 旱禾
THE_HIT: 癸水是唯一救星
Sensitive: 04-C/D

Month: 五月（午）
月令: 丁火
核心问题: 气散
Priority: 上半月癸下半月丙癸
Imagery_OneLine: 枯禾
THE_HIT: 癸透有根=富贵双全
Sensitive: 05-D/E

Month: 六月（未）
月令: 己土
核心问题: 木性且寒
Priority: 丙火为尊
Imagery_OneLine: ⭐刲羊解牛
THE_HIT: 柔木制柔土
Sensitive: 06-D/F

Month: 七月（申）
月令: 庚金
核心问题: 庚乘令克
Priority: 丙火+己土
Imagery_OneLine: 秋风残草
THE_HIT: ⭐乙庚合化金路径
Sensitive: —

Month: ⭐八月（酉）
月令: 辛金
核心问题: 七杀最危
Priority: 白露前癸/秋分后丙
Imagery_OneLine: ⭐丹桂=桂花
THE_HIT: 木火文星
Sensitive: 08-C/E

Month: ⭐九月（戌）
月令: 戊土
核心问题: 根枯叶落
Priority: 癸水+辛源
Imagery_OneLine: ⭐藤萝系甲
THE_HIT: 攀附大树可春可秋
Sensitive: 09-C

Month: 十月（亥）
月令: 壬水
核心问题: 木不受气
Priority: 先丙后戊
Imagery_OneLine: 冬前奇葩
THE_HIT: 壬水泡坏乙木需戊制
Sensitive: 10-C

Month: ⭐十一月（子）
月令: 癸水
核心问题: 花木冻
Priority: **端用丙火忌癸**
Imagery_OneLine: 冰花
THE_HIT: ⭐唯一忌癸的月份
Sensitive: 11-D/E/G/I

Month: 十二月（丑）
月令: 己土
核心问题: 极寒
Priority: 丙火为尊
Imagery_OneLine: 冻奇葩
THE_HIT: 丙火解冻
Sensitive: —

# 第二部分：格局规则（子平真诠）

## 乙木十神对照表

Stem: 甲
乙木的十神: 劫财

Stem: 乙
乙木的十神: 比肩

Stem: 丙
乙木的十神: 伤官

Stem: 丁
乙木的十神: 食神

Stem: 戊
乙木的十神: 正财

Stem: 己
乙木的十神: 偏财

Stem: 庚
乙木的十神: 正官

Stem: 辛
乙木的十神: 七杀

Stem: 壬
乙木的十神: 正印

Stem: 癸
乙木的十神: 偏印（枭神）

## 乙木十二月格局映射表

Month: 正月
Branch: 寅
HiddenStem: 甲丙戊
MainGod: 甲(劫财)
Patterns: **伤官格（借取）**
Notes: 丙透→伤官格；戊透→正财格

Month: ⭐二月
Branch: 卯
HiddenStem: 乙
MainGod: 乙(比肩)
Patterns: **建禄格**
Notes: 五阴无阳刃。专气

Month: 三月
Branch: 辰
HiddenStem: 戊乙癸
MainGod: 戊(正财)
Patterns: **杂气正财**
Notes: 癸透→偏印格；乙透→比肩

Month: 四月
Branch: 巳
HiddenStem: 丙庚戊
MainGod: 丙(伤官)
Patterns: **伤官格**
Notes: 庚透→正官格；戊透→正财格

Month: 五月
Branch: 午
HiddenStem: 丁己
MainGod: 丁(食神)
Patterns: **食神格**
Notes: 己透→偏财格

Month: ⭐六月
Branch: 未
HiddenStem: 己丁乙
MainGod: 己(偏财)
Patterns: **杂气偏财**
Notes: ⭐"刲羊解牛"。丁透→食神格

Month: 七月
Branch: 申
HiddenStem: 庚壬戊
MainGod: 庚(正官)
Patterns: **正官格**
Notes: ⭐乙庚合化金。壬透→正印格

Month: ⭐八月
Branch: 酉
HiddenStem: 辛
MainGod: 辛(七杀)
Patterns: **七杀格**
Notes: ⭐秋乙逢金最危。专气

Month: 九月
Branch: 戌
HiddenStem: 戊辛丁
MainGod: 戊(正财)
Patterns: **杂气正财**
Notes: ⭐藤萝系甲。辛透→七杀格

Month: 十月
Branch: 亥
HiddenStem: 壬甲
MainGod: 壬(正印)
Patterns: **正印格**
Notes: 甲透→劫财。亥中壬甲

Month: ⭐十一月
Branch: 子
HiddenStem: 癸
MainGod: 癸(偏印)
Patterns: **偏印格**
Notes: ⭐忌癸水冻花木。端用丙火

Month: 十二月
Branch: 丑
HiddenStem: 己辛癸
MainGod: 己(偏财)
Patterns: **杂气偏财**
Notes: ⭐"刲羊解牛"（丑=牛）。辛透→七杀格

**乙木格局特殊性（阴干第二个）：**

1. **五阴无阳刃**：卯月是建禄格，不是阳刃格
2. **乙庚合化金**：乙遇庚合——"庚虽输情于乙妹"。化金用戊土，忌丙丁
3. **藤萝系甲**：四柱有甲木透干+地支见寅或亥（甲禄/长生）=可春可秋——依附性的核心。穷通宝鉴"甲申时"是最经典案例，滴天髓宽定义为"天干甲透，地支寅藏"
4. **刲羊解牛**：未月（羊）/丑月（牛）=柔木能制柔土
5. **从势性强**：五阴从势无情义——比甲木更容易走从格
6. **四季变形**：春桃李/夏禾稼/秋桐桂/冬奇葩
7. **壬水难生乙**：壬水（大水）不能生小花草——癸水（甘霖）才合适
8. **十一月忌癸**：全年唯一忌自己印星的月份
9. **"秋乙逢金，非贫即夭"**：秋金克木最危险——需丙丁火制金

## 乙木可成格局详细规则

### 一、建禄格 ⭐（乙木卯月）

**出现月份：** 卯月（乙禄在卯）

**⚠️ 注意：** 卯月乙木是建禄格，**不是**阳刃格。五阴干没有阳刃。

**核心原则：** 卯月乙木木旺，建禄格需另取用神（财官煞食）。

[Rule]
ID: ZP-乙-禄-成01
Condition: 卯月+丙癸并用+支成木局
Judgment: 上上之命
Narrative: 你的花盛开了——阳光和雨露都到位

[Rule]
ID: ZP-乙-禄-成02
Condition: 卯月+庚官透+财印相随
Judgment: 官禄双清
Narrative: 温柔的力量遇到温和的规则

[Rule]
ID: ZP-乙-禄-成03
Condition: 卯月+丁食神泄秀
Judgment: 食神制煞或泄秀
Narrative: 温和的创造释放旺气

[Rule]
ID: ZP-乙-禄-败01
Condition: 卯月+水多困丙+戊化癸
Judgment: 🚫 下格→用神被干扰
Narrative: 雨太多把阳光遮了

[Rule]
ID: ZP-乙-禄-败02
Condition: 卯月+无丙癸
Judgment: 常人
Narrative: 花开了但没人看见

**⭐ 乙木建禄与甲木阳刃的差异：**
- 甲卯月=阳刃格→需七杀制刃→煞刃格路径
- 乙卯月=建禄格→另取用神→温和路径
- 同一个卯月，甲乙日主的处理完全不同

**取运喜忌（乙木建禄）：**
- 喜：财运（戊己）、官运（庚，但忌辛混）
- 忌：水旺运（冬月）——水多困丙冻木

### 二、七杀格 ⭐（乙木见辛金为七杀）

**出现月份：** 酉月（辛金当令→七杀格）、戌月（杂气辛透）、丑月（杂气辛透）

**⭐ "秋乙逢金，非贫即夭"——乙木遇辛金七杀最危险。**

**核心原则：** 乙木柔弱，辛金锋利。七杀必须有制有化。

[Rule]
ID: ZP-乙-煞-成01
Condition: 酉月+丁火食神制煞+身有根
Judgment: 食神制煞
Narrative: 你的温和创造驯服了锋利的对手

[Rule]
ID: ZP-乙-煞-成02
Condition: 酉月+壬癸印化煞+身弱
Judgment: 煞印相生
Narrative: 知识把锋利变成了养分

[Rule]
ID: ZP-乙-煞-成03
Condition: 酉月+丙癸两透
Judgment: 科甲名臣
Narrative: 阳光+雨露=秋桂最美

[Rule]
ID: ZP-乙-煞-成04
Condition: 酉月+支成金局+暗藏丁
Judgment: 丁制金（暗制）
Narrative: 暗中的温暖保护了你

[Rule]
ID: ZP-乙-煞-败01
Condition: 酉月+无水火
Judgment: 🚫 "劳碌"→此配置需丙癸
Narrative: 秋金克木无保护

[Rule]
ID: ZP-乙-煞-败02
Condition: 酉月+四柱不见丙癸
Judgment: 🚫 下格
Narrative: —

**⭐ "木火文星"独家美格：**

[Rule]
ID: ZP-乙-煞-美01
Condition: **八月酉月+癸在年干+丙透时干**
Judgment: ⭐ **"木火文星，定主上达"**

### 三、正官格（乙木见庚金为正官）

**出现月份：** 申月（庚金当令→正官格）、辰月（杂气戊中无庚但申月庚当令）

**⭐ 乙庚合：** 乙木日主遇庚金合——"庚虽输情于乙妹"。

[Rule]
ID: ZP-乙-官-成01
Condition: 申月+庚官+丙火制金+巳出埋金
Judgment: 科甲
Narrative: 对手被你的阳光驯服

[Rule]
ID: ZP-乙-官-成02
Condition: 申月+己透+加丙
Judgment: 上命
Narrative: 财+火=温暖的官场

[Rule]
ID: ZP-乙-官-败01
Condition: 申月+庚多+无丙己
Judgment: 平常人物
Narrative: 对手太多你没有武器

[Rule]
ID: ZP-乙-官-败02
Condition: 辛煞+庚官并透
Judgment: 官煞混杂
Narrative: 规则撕裂

[Rule]
ID: ZP-乙-官-救01
Condition: 官逢伤+壬印制伤
Judgment: 印护官
Narrative: 知识保护了规则

**⭐ 乙庚合化金的条件（引用月份反向判断清单）：**

[Rule]
ID: ZP-乙-化-01
Condition: 申月+生辰时+乙庚合化金条件满足
Judgment: **化气格（乙庚化金）**

**乙庚合化金的四条件：**
1. 月令是金月（巳酉丑申）或地支金局
2. 日主乙木无强根（不见寅卯当令）
3. 化神庚金透干且通根（申酉巳任一——申酉为庚禄旺地，巳为庚长生）
4. 无丙丁火透干克化神（"特忌丙丁煅炼破格"）

**化金后的用神：** "化金者，戊为用神"——用戊土生金。

**CIPHER叙事：** "你的对手不是你的敌人——他是你的另一个自己。乙庚合化金=藤缠斧=你和对手变成了同一件东西。"

### 四、财格（乙木见戊土正财/己土偏财）

**出现月份：** 辰月（杂气戊透→正财格）、未月（己土当令→偏财格）、丑月（杂气己透→偏财格）、戌月（杂气戊透→正财格）

**⭐ 刲羊解牛：** 乙木在丑未月能制柔土——"刲羊（未）解牛（丑）"。

[Rule]
ID: ZP-乙-财-成01
Condition: 未丑月+乙木坐未/丑
Judgment: 偏财格（此配置传统上称⭐ "刲羊解牛"——柔木制柔土的美名，非独立格局）
Narrative: 柔能克刚——你用温柔制服了对方

[Rule]
ID: ZP-乙-财-成02
Condition: 财星+庚官透+食伤通关
Judgment: 伤官生财+财旺生官
Narrative: 才华→钱→地位

[Rule]
ID: ZP-乙-财-成03
Condition: **六月无水+无比劫出干**
Judgment: **弃命从才**，富大贵小
Narrative: 你不做花草了——变成了土地的一部分

[Rule]
ID: ZP-乙-财-成04
Condition: 九月支多戊土+天干戊+无比劫
Judgment: **从财格**
Narrative: 同上

[Rule]
ID: ZP-乙-财-败01
Condition: 财星+甲乙比劫争财
Judgment: 群劫争财
Narrative: 同类太多蛋糕被分光

[Rule]
ID: ZP-乙-财-败02
Condition: 一派戊土+不见比肩
Judgment: 🚫 "才多身弱，富屋贫人"→需比劫帮身
Narrative: 钱太多你拿不动

### 五、印绶格（乙木见壬水正印/癸水偏印）

**出现月份：** 亥月（壬水当令→正印格）、子月（癸水当令→偏印格）

**⭐ 十一月偏印格的特殊处理：** 子月癸水当令→偏印格。但穷通宝鉴明确"不宜用癸以冻花木"——忌自己的偏印！

[Rule]
ID: ZP-乙-印-成01
Condition: 亥月+丙戊两透
Judgment: 科甲
Narrative: 温暖+堤防=冬木得生

[Rule]
ID: ZP-乙-印-成02
Condition: 亥月+有丙无戊
Judgment: 入儒林
Narrative: 有温度就能活

[Rule]
ID: ZP-乙-印-特01
Condition: ⭐ **子月+丙火出干+无癸制**
Judgment: ⭐ **端用丙火（忌癸偏印）**
Narrative: 你不需要更多"滋养"——你需要温度

[Rule]
ID: ZP-乙-印-特02
Condition: 子月+丁火见甲
Judgment: "麟趾振振，芝兰绕膝"
Narrative: 灯烛遇大树=真正的温暖

[Rule]
ID: ZP-乙-印-败01
Condition: 亥月+水多无戊
Judgment: 🚫 "乙性漂浮，流荡"→水泡烂木
Narrative: 太多滋养反而淹没你

[Rule]
ID: ZP-乙-印-败02
Condition: 子月+壬透无戊
Judgment: 🚫 "贫贱"→大水泡小花
Narrative: 同上

[Rule]
ID: ZP-乙-印-败03
Condition: 子月+支成水局+壬癸两透
Judgment: 🚫 "木浮，且夭折"→需戊救
Narrative: 彻底被淹

**⭐ 十一月乙木的核心矛盾（全10日主最独特）：**
- 癸水是乙木的偏印——通常是"生我者"=好事
- 但子月花木已冻→癸水反而"以冻花木"=坏事

**引擎处理（奇审核确认）：**
- **子月（十一月）：硬编码——癸水偏印为忌**（癸当令最旺，冻花最烈）
- **丑月（十二月）：软编码——癸水偏印偏忌**（癸透干则忌，仅藏干不忌。丑月己土当令，癸只是藏干，力度不如子月）
- **亥月（十月）：不忌**（亥月壬水当令，壬是正印不是偏印，且亥月甲木长生可引丁暖局）

### 六、食神格/伤官格（乙木见丁火食神/丙火伤官）

**出现月份：** 午月（丁火当令→食神格）、巳月（丙火当令→伤官格）、未月（杂气丁透）

[Rule]
ID: ZP-乙-食-成01
Condition: 午月+丁食神+戊己财
Judgment: 食神生财
Narrative: 温和的创造变钱

[Rule]
ID: ZP-乙-伤-成01
Condition: 巳月+丙伤官+癸水滋身
Judgment: 伤官佩印
Narrative: 激烈创造被滋润收敛

[Rule]
ID: ZP-乙-食-败01
Condition: 午月+支成火局+无癸
Judgment: 🚫 "阳焦木性"→火泄木精
Narrative: 输出过度烧焦自己

[Rule]
ID: ZP-乙-伤-败01
Condition: 巳月+丙戊太多+火局
Judgment: 🚫 "瞽目之流"→眼目方向需关注（v1.1+免责）
Narrative: 火过旺伤眼

### 七、从格系列（乙木从势性强）

**⚠️ 奇的提示："五阴从势无情义"——阴干从势性强。**

**但乙木有特殊性：** "藤萝系甲"——如果四柱有甲木透干+地支见寅或亥（甲禄/长生），即使乙木身弱也不算"无依"。从格判断需扣除此情况。

[Rule]
ID: ZP-乙-从-01
Condition: 六月/九月+财星极旺+无水无比劫
Judgment: **从财格**
Narrative: 你变成了大地的一部分

[Rule]
ID: ZP-乙-从-02
Condition: 七月+生辰时+乙庚合化金
Judgment: **化气格（乙庚化金）**
Narrative: 藤缠斧=你和对手合为一体

[Rule]
ID: ZP-乙-从-03
Condition: 秋月+金局极旺+无印比
Judgment: **从杀格**
Narrative: 臣服于最锋利的力量

[Rule]
ID: ZP-乙-从-04
Condition: 春月+支全寅卯辰+无金
Judgment: **曲直格**（借取甲木专旺）
Narrative: 木极旺=纯粹生长

[Rule]
ID: ZP-乙-从-05
Condition: **夏月（午未月）+丙丁火食伤极旺+无水印+无金杀**
Judgment: **从儿格**（从火）
Narrative: 你的输出变成你的主人（罕见但存在）

**⚠️ 乙木的曲直格判断：**
- 严格来说，曲直格是甲乙日主+支全寅卯辰或亥卯未
- 乙木也能成曲直格，但更常走"从势"路径（比甲木更容易从）
- 引擎判断顺序：先查从格条件 → 再查专旺格条件

### 八、杂气格

[Rule]
ID: ZP-乙-杂-01
Condition: 辰月+戊透
Judgment: 正财格

[Rule]
ID: ZP-乙-杂-02
Condition: 辰月+癸透
Judgment: 偏印格

[Rule]
ID: ZP-乙-杂-03
Condition: 辰月+乙透
Judgment: 比肩

[Rule]
ID: ZP-乙-杂-04
Condition: 戌月+戊透
Judgment: 正财格

[Rule]
ID: ZP-乙-杂-05
Condition: 戌月+辛透
Judgment: 七杀格

[Rule]
ID: ZP-乙-杂-06
Condition: 戌月+丁透
Judgment: 食神格

[Rule]
ID: ZP-乙-杂-07
Condition: 未月+己透
Judgment: 偏财格

[Rule]
ID: ZP-乙-杂-08
Condition: 未月+丁透
Judgment: 食神格

[Rule]
ID: ZP-乙-杂-09
Condition: 未月+乙透
Judgment: 比肩

[Rule]
ID: ZP-乙-杂-10
Condition: 丑月+己透
Judgment: 偏财格

[Rule]
ID: ZP-乙-杂-11
Condition: 丑月+辛透
Judgment: 七杀格

[Rule]
ID: ZP-乙-杂-12
Condition: 丑月+癸透
Judgment: 偏印格

## 乙木核心美格/病格标注

Name: 建禄格
Nature: 中性
Trigger: 卯月
Product_Meaning: 花盛开但需阳光雨露

Name: ⭐**藤萝系甲**
Nature: **美格（独家）**
Trigger: 甲透干+地支见寅或亥（宽定义）。"甲申时"为最经典案例
Product_Meaning: 攀附大树可春可秋

Name: ⭐**刲羊解牛**
Nature: **配置标签（偏财格子类）**
Trigger: 未丑月乙木坐未/丑
Product_Meaning: 柔能克刚（同"木火通明"处理——描述性标签非独立格局）

Name: ⭐**木火文星**
Nature: **美格**
Trigger: 八月+癸年+丙时
Product_Meaning: 秋桂最美

Name: **乙庚合化金**
Nature: 变格
Trigger: 申月+辰时+条件满足
Product_Meaning: 藤缠斧

Name: **从财格**
Nature: 变格
Trigger: 六/九月财旺无印比
Product_Meaning: 变成大地

Name: **从杀格**
Nature: 变格
Trigger: 秋金极旺无印比
Product_Meaning: 臣服锋利

Name: 曲直格（借取）
Nature: 专旺格
Trigger: 春月支全木方
Product_Meaning: 纯粹生长

Name: 二庚争合
Nature: **病格**
Trigger: 三月+两庚争合一乙
Product_Meaning: 两个追求者让你破碎

Name: 秋乙逢金
Nature: **病格**
Trigger: 秋月金重无丙丁
Product_Meaning: 非贫即夭

Name: 十一月忌癸
Nature: **特殊病格**
Trigger: 子月+癸水透干
Product_Meaning: 偏印反为害

Name: 木浮
Nature: 病格
Trigger: 冬月水多无戊
Product_Meaning: 被淹没

## 乙木与其他日主的格局交叉验证

### 乙木是金日主的财星——反向验证
- 庚金正财=乙木 → 庚金"赢甲兄输于乙妹"→庚金被乙木合走
- 辛金偏财=乙木 → 辛金对乙木是七杀（最危险关系）

### 乙木是火日主的印绶——反向验证
- 丙火正印=乙木 → 丙火"怀丁抱丙"中丙是乙的伤官
- 丁火偏印=乙木 → 丁火"抱乙而孝"=丁火护乙不被辛伤

### 乙木是水日主的食伤——反向验证
- 壬水伤官=乙木 → 壬水泄乙（但壬水大水难生乙）
- 癸水食神=乙木 → 癸水滋乙（甘霖滋花草=最合适）

### 乙木是土日主的官煞——反向验证
- 戊土正官=乙木 → 戊土"恶木太过"=乙木温柔但太多也烦
- 己土七杀=乙木 → 己土"不愁木盛"=己土不怕乙木

### Sam的盘（辛金）视角
Sam的辛金日主，乙木是偏财。

**乙木偏财对辛金Sam的作用：**
- 偏财=偏妻、额外收入源
- 乙木柔弱但能"输情于庚妹"——辛金遇乙木是自然的吸引
- "乙庚合化金"不适用于辛金日主——辛见乙是偏财关系，不合

**CIPHER引擎应用：** 辛金用户遇到乙木元素（偏财）时，叙事方向是"温柔的额外收入"而非"正面的资源获取"。

# 第三部分：象法意象库

## 乙木象法意象库

## 一、乙木核心原型

### 古籍原始定位

Source: 滴天髓
Original: "乙木虽柔，刲羊解牛。怀丁抱丙，跨凤乘猴。虚湿之地，骑马亦忧。藤萝系甲，可春可秋"
Core_Imagery: ⭐柔、刲羊、怀火、藤萝系甲

Source: 任铁樵注
Original: "乙木者，甲之质，而承甲之生气也。春如桃李，夏如禾稼，秋如桐桂，冬如奇葩"
Core_Imagery: ⭐四季四形态

Source: 任铁樵注
Original: "割羊解牛者，生于丑未月……丑乃湿土，可以受气也"
Core_Imagery: 柔制柔土的机制

Source: 任铁樵注
Original: "怀丁抱丙……生于申酉月，只要干有丙丁，不畏金旺"
Core_Imagery: 有火则不怕金

Source: 穷通宝鉴
Original: "秋乙逢金，非贫即夭"
Core_Imagery: 秋金最忌

Source: 穷通宝鉴
Original: "十一月乙木……不宜用癸以冻花木"
Core_Imagery: ⭐全年唯一忌偏印

Source: 穷通宝鉴
Original: "丁乃灯烛之火，岂能解严寒之冻"
Core_Imagery: 丙丁差异最清晰

### CIPHER核心原型定义

**乙木 = THE VINE**

一句话：**你是一根藤——柔软，但能绞杀。**

核心物质意象（按季节变化）：
1. **春=桃李** — 花开盛放，需阳光雨露
2. **夏=禾稼** — 田间庄稼，需水滋润
3. **秋=桐桂** — 八月丹桂，需火制金
4. **冬=奇葩** — 寒中奇花，需火解冻
5. **跨季=藤萝** — 攀附大树，可春可秋

**乙木核心动作：**
- **攀附**（藤萝系甲）— 乙木的生存策略
- **柔克**（刲羊解牛）— 柔能制刚的能力
- **变形**（四季变形）— 随环境改变形态
- **合化**（乙庚合金）— 与对手合为一体
- **依附**（怀丁抱丙）— 有火护身则不怕金

### 乙木与甲木的原型对比（最终版）

Dimension: 物质
甲木 THE PILLAR: 大树/栋梁/参天巨木
乙木 THE VINE: 花草/藤萝/桃李/禾稼/桐桂/奇葩

Dimension: 本质
甲木 THE PILLAR: **纯阳猛烈、参天雄壮**
乙木 THE VINE: **阴柔至弱、柔中有刚**

Dimension: 对金
甲木 THE PILLAR: "春不容金"（怕金）
乙木 THE VINE: ⭐ "怀丁抱丙，跨凤乘猴"（有火不怕金）

Dimension: 对土
甲木 THE PILLAR: 甲克戊（大树劈山）
乙木 THE VINE: ⭐ "刲羊解牛"（柔木制柔土）

Dimension: 对水
甲木 THE PILLAR: 壬水生甲（大水养大树）
乙木 THE VINE: ⭐ "壬水难生乙"（大水泡烂小花草）

Dimension: 对火
甲木 THE PILLAR: 木火通明（甲生丁）
乙木 THE VINE: ⭐ "抱乙而孝"（丁护乙不被辛伤）

Dimension: 核心合化
甲木 THE PILLAR: 甲己合化土
乙木 THE VINE: ⭐ **乙庚合化金**（藤缠斧）

Dimension: 依附性
甲木 THE PILLAR: 独立自主
乙木 THE VINE: ⭐ **藤萝系甲**=依附甲才能四季

Dimension: 从势性
甲木 THE PILLAR: 弱（"素无从才从杀从化之理"）
乙木 THE VINE: ⭐ **强**（五阴从势无情义）

Dimension: 阳刃
甲木 THE PILLAR: 有（甲卯月）
乙木 THE VINE: ⭐ **无**（五阴无阳刃）

Dimension: 建禄处理
甲木 THE PILLAR: 寅月建禄+卯月阳刃
乙木 THE VINE: ⭐ 卯月建禄（非阳刃）

Dimension: 冬月印星
甲木 THE PILLAR: 壬癸水生甲=好事
乙木 THE VINE: ⭐ 十一月忌癸水=印星反害

Dimension: THE HIT方向
甲木 THE PILLAR: 你是参天大树——直立不弯
乙木 THE VINE: ⭐ 你是藤萝——柔软但能绞杀

## 二、乙木与十天干的关系意象

TenGod: 劫财·甲木
Stem: 同类之阳
NaturalImagery: ⭐ **大树旁的藤萝——"藤萝系甲"**
OneLine: 你依附的那棵大树=你的生命线

TenGod: 比肩·乙木
Stem: 同类之阴
NaturalImagery: 花草丛——互相遮挡
OneLine: 同类让你不孤单但也抢光

TenGod: ⭐伤官·丙火
Stem: 我生之阳
NaturalImagery: **太阳晒花——"怀丁抱丙"的"丙"**
OneLine: ⭐ 你的阳光是你的武器（有丙不怕金）

TenGod: ⭐食神·丁火
Stem: 我生之阴
NaturalImagery: **灯火护花——"抱乙而孝"**
OneLine: ⭐ 丁火保护你不被辛金伤害

TenGod: 正财·戊土
Stem: 我克之阳
NaturalImagery: 花草扎根山岗
OneLine: 你能制住大山——但要柔着来

TenGod: ⭐偏财·己土
Stem: 我克之阴
NaturalImagery: **花草扎根田园——"刲羊解牛"**
OneLine: ⭐ 你和田园是天然配对——柔制柔

TenGod: ⭐正官·庚金
Stem: 克我之阳
NaturalImagery: **斧头砍藤——"庚虽输情于乙妹"**
OneLine: ⭐ 你的对手被你迷住了——乙庚合

TenGod: ⭐七杀·辛金
Stem: 克我之阴
NaturalImagery: **剪刀修花——"秋乙逢金非贫即夭"**
OneLine: ⭐ 最锋利的敌人——必须有丙丁才能活

TenGod: 正印·壬水
Stem: 生我之阳
NaturalImagery: 大河泡花——壬水难生乙
OneLine: 你不需要大河——你需要甘霖

TenGod: ⭐偏印·癸水
Stem: 生我之阴
NaturalImagery: **甘霖滋花——但冬月反冻花**
OneLine: ⭐ 春夏秋=最好的滋养；冬月=最大的伤害

## 三、乙木十二月意象库（季节变体）

### 春季（寅卯辰月）—— 桃李盛放

Month: 正月·寅
Scene: 早春桃树——含苞待放
CoreConflict: 余寒未除
Solution: 丙火阳光+癸水雨露

Month: ⭐二月·卯（建禄）
Scene: 盛放的桃李——花团锦簇
CoreConflict: 木旺需泄
Solution: 丙癸并用=上上

Month: 三月·辰
Scene: 暮春残花——阳气渐炽
CoreConflict: 先需水润再需阳光
Solution: 先癸后丙。忌庚己混杂

**春季乙木总方向：** 你在最美的季节——但美需要维护。阳光（丙）和雨露（癸）都不能少。

### 夏季（巳午未月）—— 禾稼需水

Month: 四月·巳
Scene: 旱禾——被晒干
CoreConflict: 枯焦
Solution: ⭐专用癸水（辛透为清）

Month: 五月·午
Scene: 枯禾——"气散之文"
CoreConflict: 火泄精
Solution: 癸透有根=富贵双全

Month: ⭐六月·未
Scene: ⭐ **刲羊——柔木制柔土**
CoreConflict: 木性且寒
Solution: 丙火为尊+癸亦需

**夏季乙木总方向：** 你在最渴的时候——癸水甘霖是唯一的救星。用癸忌戊己杂乱。

### 秋季（申酉戌月）—— 桐桂逢金

Month: 七月·申
Scene: 秋风中的草——庚金乘令
CoreConflict: ⭐乙庚合的暧昧
Solution: 丙制金或⭐从化路径

Month: ⭐八月·酉
Scene: ⭐ **丹桂——白露滋蕊秋分开花**
CoreConflict: 七杀辛金最危
Solution: 白露前癸滋/秋分后丙暖

Month: ⭐九月·戌
Scene: ⭐ **枯藤——根枯叶落**
CoreConflict: 最弱状态
Solution: ⭐"藤萝系甲"=攀附大树

**秋季乙木总方向：** 你在最危险的季节——秋金克木。"怀丁抱丙"是你的护身法则。

### 冬季（亥子丑月）—— 奇葩冻花

Month: 十月·亥
Scene: 冬前奇葩——壬水泡花
CoreConflict: 木不受气
Solution: 先丙后戊（戊制水）

Month: ⭐十一月·子
Scene: ⭐ **冰花——花木寒冻**
CoreConflict: ⭐忌癸水冻花
Solution: ⭐**端用丙火。癸水反为害**

Month: 十二月·丑
Scene: ⭐ 解牛——冻中牛土
CoreConflict: 极寒
Solution: 丙火解冻+甲木佐

**冬季乙木总方向：** 你在冰冻中——丙火（太阳）是唯一的解冻方式。丁火（灯烛）不够。癸水（雨露）在冬月反而冻死你。

## 四、乙木五行配置变体意象

### 木多（比劫重）

Imagery: 藤萝系甲
Scene: ⭐ 藤蔓攀附大树=四季不倒
Mapping: 依附对的人=你的生存策略

Imagery: 乱臣无主
Scene: 🚫 一堆花草无主干
Mapping: 此配置同类太多但没有领导

Imagery: 曲直格
Scene: 支全木方=纯粹生长
Mapping: 极致的木=你只做一件事

### 金多（官煞重）

Imagery: 秋乙逢金
Scene: 🚫 ⭐ 剪刀修花修到断
Mapping: "非贫即夭"——必须有火制金

Imagery: 乙庚合化金
Scene: ⭐ 藤缠斧头=变成金属
Mapping: 你和对手合为一体

Imagery: 怀丁抱丙
Scene: ⭐ 花有火护=不怕金
Mapping: 有温度就不怕锋利

### 水多（印重）

Imagery: 壬水泡花
Scene: 🚫 大水泡烂小花
Mapping: 壬水不能生乙——太猛了

Imagery: 癸水滋花
Scene: ⭐ 甘霖滋润花草
Mapping: 癸水才是乙木需要的印

Imagery: ⭐冬月癸冻花
Scene: 🚫 ⭐ 十一月雨水结冰冻死花
Mapping: ⭐ 唯一"偏印反为害"的情况

Imagery: 木浮
Scene: 🚫 水多木浮——跟甲木同病
Mapping: 但乙木更脆弱更快被泡烂

### 火多（食伤重）

Imagery: 木秀火明
Scene: ⭐ 花开灿烂=木火通明（乙木版）
Mapping: 温和版的创造力释放

Imagery: 阳焦木性
Scene: 🚫 火太多烧焦花草
Mapping: 输出过度自伤

Imagery: 气散之文
Scene: 🚫 五月火泄乙精
Mapping: 你的精华被泄光了

### 土多（财重）

Imagery: 刲羊解牛
Scene: ⭐ ⭐ 柔木制柔土=温柔的胜利
Mapping: 你的柔软就是你的力量

Imagery: 才多身弱
Scene: 🚫 花草被太多土埋
Mapping: 钱太多你拿不动

Imagery: 从财格
Scene: 一派土+无比劫=从财
Mapping: 你变成了大地的一部分

### 缺火

Imagery: 秋乙无火
Scene: 🚫 ⭐ "非贫即夭"——金克木无保护
Mapping: 你需要温度作为铠甲

Imagery: 冬乙无丙
Scene: 🚫 花冻死
Mapping: 没有太阳就没有生路

### 缺水（夏月）

Imagery: 旱禾
Scene: 🚫 庄稼枯死
Mapping: 你需要甘霖（癸）不是大河（壬）

## 五、乙木格局意象库

Pattern: 建禄格（卯月）
Core_Imagery: 盛放的花园
THE_HIT_Seed: 你在最美的时候——但美需要维护
BLIND_SPOT_Seed: 你以为自己够强。实际需要阳光雨露

Pattern: ⭐**藤萝系甲**
Core_Imagery: ⭐ **枯藤攀大树**
THE_HIT_Seed: 你的力量不在自己——在你选择依附谁
BLIND_SPOT_Seed: 你以为独立=好。实际你是"附生型"——找对树才是关键

Pattern: ⭐**刲羊解牛**
Core_Imagery: ⭐ **柔草割宰硬土**
THE_HIT_Seed: 你的柔软就是你的武器——别试图变硬
BLIND_SPOT_Seed: 你以为你弱。实际柔能制刚

Pattern: ⭐**木火文星**
Core_Imagery: ⭐ 秋桂+阳光=文星
THE_HIT_Seed: 你在最危险的季节开出最美的花
BLIND_SPOT_Seed: —

Pattern: **乙庚合化金**
Core_Imagery: ⭐ 藤缠斧=变成同一件东西
THE_HIT_Seed: 你和对手不是对立的——你们会合体
BLIND_SPOT_Seed: 你以为你要打败对手。实际你会变成对手

Pattern: 七杀格（酉月）
Core_Imagery: 剪刀修花
THE_HIT_Seed: 最锋利的对手要用最温暖的方式应对
BLIND_SPOT_Seed: 你以为硬碰硬。实际要用火制金

Pattern: 正官格（申月）
Core_Imagery: 庚金输情于乙
THE_HIT_Seed: 对手被你迷住了
BLIND_SPOT_Seed: —

Pattern: 财格（未丑月）
Core_Imagery: 柔草扎根
THE_HIT_Seed: 你和土地是天然配对
BLIND_SPOT_Seed: —

Pattern: 偏印格（子月）
Core_Imagery: ⭐ 冰花——偏印反害
THE_HIT_Seed: 你最熟悉的滋养反而冻死你
BLIND_SPOT_Seed: ⭐ 你以为你需要更多"支持"。实际冬月你需要温度不是水

Pattern: 正印格（亥月）
Core_Imagery: 大河泡花
THE_HIT_Seed: 壬水太猛——你需要的是甘霖不是洪水
BLIND_SPOT_Seed: —

Pattern: 食神格（午月）
Core_Imagery: 温和的创造
THE_HIT_Seed: 你的产出方式应该温和——别猛烈
BLIND_SPOT_Seed: —

Pattern: 伤官格（巳月）
Core_Imagery: 烈日晒花
THE_HIT_Seed: 你的才华在消耗你——需要癸水补
BLIND_SPOT_Seed: —

Pattern: **从财格**
Core_Imagery: 变成大地
THE_HIT_Seed: 你放弃做花草——变成了土地的一部分
BLIND_SPOT_Seed: —

Pattern: **从杀格**
Core_Imagery: 臣服锋利
THE_HIT_Seed: 你放弃抵抗——锋利变成你的形状
BLIND_SPOT_Seed: —

Pattern: 曲直格（借取）
Core_Imagery: 纯粹生长
THE_HIT_Seed: 不需要其他——只做一棵生长的植物
BLIND_SPOT_Seed: —

Pattern: 二庚争合
Core_Imagery: 两把斧头争一根藤
THE_HIT_Seed: 两个追求者让你撕裂
BLIND_SPOT_Seed: —

## 六、乙木专属古典名言映射

古籍名言: **"乙木虽柔，刲羊解牛"**
现代CIPHER解读: ⭐ ⭐ 你看起来柔弱——但你能制服比你大得多的对手

古籍名言: **"怀丁抱丙，跨凤乘猴"**
现代CIPHER解读: ⭐ 只要有温度（丙丁），你就能在最危险的地方存活（申酉）

古籍名言: "虚湿之地，骑马亦忧"
现代CIPHER解读: 冬月水多（虚湿），即使有午火（马）也难发生

古籍名言: **"藤萝系甲，可春可秋"**
现代CIPHER解读: ⭐ ⭐ 攀附对的人——你就能四季常青

古籍名言: "秋乙逢金，非贫即夭"
现代CIPHER解读: 🚫 改写：秋月金旺时此配置需火护身

古籍名言: **"不宜用癸以冻花木"**
现代CIPHER解读: ⭐ 你最熟悉的滋养在冬月反而是毒药

古籍名言: **"丁乃灯烛之火，岂能解严寒之冻"**
现代CIPHER解读: ⭐ 你需要太阳（丙）不是灯烛（丁）来解冻

古籍名言: "庚虽输情于乙妹"
现代CIPHER解读: ⭐ 你的对手被你迷住了——合的力量大于克

古籍名言: "以丹桂为乙木"
现代CIPHER解读: ⭐ 八月的你=桂花——白露滋蕊秋分开花

古籍名言: "春如桃李，夏如禾稼，秋如桐桂，冬如奇葩"
现代CIPHER解读: ⭐ 你是变形者——每个季节你是不同的植物

古籍名言: "木火文星，定主上达"
现代CIPHER解读: ⭐ 八月的你有癸年丙时=文学之星

古籍名言: "甲之质，而承甲之生气"
现代CIPHER解读: 你从甲木继承了生命力——但用了完全不同的方式

古籍名言: "活木忌埋根之铁"
现代CIPHER解读: 🚫 改写：活的你最怕被金属深埋

## 七、乙木+用神组合的经典叙事

### 用神是丙火（伤官）—— 最护
- 场景：太阳照花="怀丁抱丙"的丙
- 叙事：丙火是你的铠甲——有阳光你就不怕任何锋利。秋生乙木有丙="跨凤乘猴"。
- 对象：需要"温度保护"的创业者、在强敌环境中的小企业

### 用神是癸水（偏印）—— 最滋（春夏秋限定）
- 场景：甘霖滋花——露珠养桃李
- 叙事：你需要的不是大河（壬）而是甘霖（癸）。温柔持续的滋养比猛烈的浇灌好一百倍。
- ⚠️ **冬月不适用此叙事**——冬月癸水反为害
- 对象：需要精细滋养的人才、初创企业的种子轮

### 用神是甲木（劫财）—— 最依附
- 场景：藤萝系甲="找到你的大树"
- 叙事：你不是独立型——你的力量来自你选择攀附的那棵大树。找对人比自己强更重要。
- 对象：合伙人模式的创业者、需要平台的专业人士

### 用神是丁火（食神）—— 最孝
- 场景：灯火护花="抱乙而孝"
- 叙事：丁火保护你不被辛金伤害——"明使辛金不伤乙木"。你需要的不是猛烈（丙），而是贴心（丁）。
- 对象：需要"近身保护"的场景、亲密关系中的守护

### 用神是庚金（正官）—— 最合
- 场景：斧头被藤缠住=乙庚合
- 叙事：你不是跟对手打——你是跟对手合。"输情于乙妹"=对手被你的柔软征服。
- 对象：谈判专家、以柔克刚的领导者

## 八、产品安全过滤（已查通用表v1.1）

AncientTerm: 非贫即夭
Rewrite: 此配置需火护身（+健康免责）
TableEntry: v1.1器官层级

AncientTerm: 瞽目之流
Rewrite: 健康方面，眼目方向值得长期关注（+免责）
TableEntry: v1.1器官层级

AncientTerm: 残疾
Rewrite: 此配置火过旺需水救（+健康免责）
TableEntry: v1.1器官层级

AncientTerm: 贫贱之辈
Rewrite: 此配置需特定配置才能发挥
TableEntry: 基础过滤表

AncientTerm: 僧道
Rewrite: 独处型创作路径
TableEntry: 基础过滤表

AncientTerm: 庸人
Rewrite: 此配置需甲制土
TableEntry: 基础过滤表

AncientTerm: 流荡之徒
Rewrite: 此配置需戊土制水
TableEntry: 基础过滤表

AncientTerm: 富屋贫人
Rewrite: 外在丰富但内在需被看见
TableEntry: 基础过滤表

AncientTerm: 大奸大诈
Rewrite: 🚫 此配置丁火不能替代丙火——表象温暖内核虚假
TableEntry: 基础过滤表

AncientTerm: 孤鳏到老
Rewrite: 关系模式需非标准配置
TableEntry: 基础过滤表

AncientTerm: 木浮夭折
Rewrite: 此配置需戊救（+健康免责）
TableEntry: v1.1器官层级

AncientTerm: 离乡之命
Rewrite: 此配置适合远方发展
TableEntry: ⭐ 中性化（非贬义）

## 九、与其他日主的意象对偶

### 甲木视角 × 乙木视角

Scenario: 甲乙同见
甲木的意象: 大树旁的藤萝
乙木的意象: ⭐ 我攀附大树=四季常青

Scenario: 甲克戊
甲木的意象: 大树劈山
乙木的意象: 我"刲羊解牛"=柔克柔

Scenario: 春月
甲木的意象: 参天雄壮
乙木的意象: 桃李盛放

Scenario: 秋月
甲木的意象: 不容金
乙木的意象: ⭐ 有火则不怕金

### 庚金视角 × 乙木视角

Scenario: 庚克乙
庚金的意象: 斧砍藤
乙木的意象: 我被砍

Scenario: ⭐乙庚合
庚金的意象: ⭐ "输情于乙妹"——被迷住
乙木的意象: ⭐ 我缠住了斧头——合为一体

Scenario: 化金
庚金的意象: —
乙木的意象: 我变成了金属

### 辛金视角 × 乙木视角

Scenario: 辛克乙
辛金的意象: 剪刀修花
乙木的意象: 🚫 最锋利的敌人——必须有火

Scenario: 秋月
辛金的意象: 辛金当令
乙木的意象: ⭐ "秋乙逢金非贫即夭"

### 丁火视角 × 乙木视角

Scenario: 丁护乙
丁火的意象: "抱乙而孝"——丁保护乙
乙木的意象: ⭐ 你是我最贴心的保护者

Scenario: 乙生丁
丁火的意象: 乙是丁的嫡母
乙木的意象: 我滋养了灯火

### 癸水视角 × 乙木视角

Scenario: 癸生乙
癸水的意象: 甘霖滋花
乙木的意象: ⭐ 你是我最好的滋养（春夏秋）

Scenario: ⭐冬月癸冻乙
癸水的意象: 雨变冰
乙木的意象: ⭐ 你在冬月反而冻死我

### Sam的盘（辛金）视角
Sam的辛金日主，乙木是**偏财**。

**乙木偏财对辛金Sam的作用：**
- 偏财=偏妻、额外收入源、非主业收入
- 乙木柔弱——对辛金来说是"温柔的财源"
- 但"辛克乙"=七杀关系（从乙木视角看）——Sam对乙木型资源有天然的"锋利"
- CIPHER引擎应用：辛金用户的偏财（乙木）叙事方向="温柔的额外收入，但你要小心别伤害它"
