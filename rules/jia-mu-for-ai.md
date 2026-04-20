# 甲木 完整规则库

# 第一部分：调候规则（穷通宝鉴）

## 甲木总论（跨月通则）

**核心定位（三来源）：**

Source: 滴天髓
Original: "甲木参天，脱胎要火。春不容金，秋不容土。火炽乘龙，水宕骑虎。地润天和，植立千古"
Core_Imagery: 参天大树、脱胎要火、不惧金也不被土困

Source: 穷通宝鉴
Original: "春月之木，余寒犹存，喜火温暖，则无盘屈之患"
Core_Imagery: 春天需要火暖才能舒展

Source: 穷通宝鉴
Original: "夏月之木，根干叶枯，欲得水盛，而成滋润之功"
Core_Imagery: 夏天需要水救

Source: 穷通宝鉴
Original: "秋月之木，气渐凋零……欲得刚金而修削"
Core_Imagery: 秋天需要金来修削成器

Source: 穷通宝鉴
Original: "冬月之木，盘屈在地，欲土多以培养，恶水盛而忘形"
Core_Imagery: 冬天需要土护根

Source: 神峰通考·体象
Original: "甲木若无根，全赖申子辰"
Core_Imagery: 甲木无根时靠水木扶持

### 象法核心意象

- 甲木 = 参天大树/栋梁之材/森林
- 庚金七杀 = 斧头劈甲→成器（不是被伤害，是被塑造）
- 丁火伤官 = 燃烧的木材→木火通明，最秀
- 壬水偏印 = 大河灌溉→可以但怕水多漂木
- 癸水正印 = 雨露滋养→温和
- 戊土偏财 = 山岗/硬土→甲木可以扎根但要疏土
- 己土正财 = 田园/软土→甲己合化土
- 丙火食神 = 太阳→木向阳，木火相生

### 甲木与乙木的核心区别

Dimension: 物质
甲木 THE PILLAR: 参天大树/栋梁
乙木 THE VINE: 花草/藤蔓

Dimension: 本质
甲木 THE PILLAR: 向上参天，刚直
乙木 THE VINE: 曲折攀附，柔韧

Dimension: 对金
甲木 THE PILLAR: "春不容金"——春天欺金；秋天需金劈成器
乙木 THE VINE: "秋乙逢金非贫即夭"——怕金克

Dimension: 对火
甲木 THE PILLAR: 火炽乘龙——坐辰泄火
乙木 THE VINE: 火炽不怕，反是"木火通明"

Dimension: 对水
甲木 THE PILLAR: 水宕骑虎——坐寅纳水
乙木 THE VINE: 水多"漂浮"——至怕

Dimension: 核心需求
甲木 THE PILLAR: 被劈成器（庚）+ 被点燃（丁）
乙木 THE VINE: 被滋养（癸）+ 被保护（丙/戊）

Dimension: THE HIT方向
甲木 THE PILLAR: 你需要被使用——不被使用就是浪费
乙木 THE VINE: 你需要被珍惜——不被珍惜就枯萎

## 正月甲木（寅月=建禄）

**原文核心：** "正月甲木，初春尚有余寒，得丙癸逢，富贵双全。癸藏丙透，名寒木向阳，主大富贵。"

**调候优先级：** 丙火为尊，癸水为辅。

**月令特征：** 寅月甲木当令（**建禄格**）。甲木本气。春初余寒未除，需要丙火暖局。

### 调候规则

[Rule]
ID: QT-甲-01-A
Condition: 丙透+癸透
Judgment: 富贵双全
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-01-B
Condition: 癸藏+丙透
Judgment: "寒木向阳"，大富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-01-C
Condition: 无丙癸
Judgment: 平常人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-01-D
Condition: 一派庚辛
Judgment: 🚫 "克子刑妻"→ 此配置压力过大，需甲木疏通环境
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-01-E
Condition: 一派庚辛+支会金局
Judgment: 🚫 "非贫即夭"→ 此配置需要特定环境才能发挥
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-01-F
Condition: 无火+一派壬癸+无戊制
Judgment: 🚫 "水泛木浮死无棺椁"→ 此配置能量四散需土镇定
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-01-G
Condition: 一派戊己+支会金局
Judgment: "财多身弱"，富屋贫人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-01-H
Condition: 无庚+丁透
Judgment: 伤官生财格，聪明雅秀
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-01-I
Condition: 多癸+伤丁
Judgment: 奸雄枭险（如曹操）——"言清行浊笑里藏刀"
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-01-J
Condition: 支成金局+多透庚辛
Judgment: 🚫 "木被金伤必主残疾"→ 健康方向需要特别留意
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-01-K
Condition: 支成火局+泄露太过
Judgment: 🚫 "愚懦+暗疾"→ 能量泄散，健康方向需要特别关注
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-01-L
Condition: 支成木局+得庚
Judgment: 为贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-01-M
Condition: 支成木局+无庚
Judgment: 🚫 "僧道/鳏孤/寡独"→ 独处型创作路径
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-01-N
Condition: 支成水局+戊透
Judgment: 为贵
Safety: ✅
Confidence: 中

**总结：** "甲木若无根，全赖申子辰，干得才杀透，平步上青云。"——甲木无根时靠水和印扶持；有根时用财杀成器。

**象法意象：**
- 正月甲木 = 初春的大树——余寒未尽，枝芽刚冒
- 丙火 = 太阳 = "寒木向阳"
- 庚金劈甲 = 斧头砍树 = 能把大树变成栋梁
- 癸水滋养 = 春雨 = 温和地让树生长

**CIPHER映射：**
- THE HIT方向：你是一棵刚冒芽的大树——现在还寒冷，最需要的是一束阳光。不是更多雨，是太阳。
- BLIND SPOT方向：你以为你需要更多水/资源。实际你缺的是温度——一个让你感到"被照亮"的人或方向。
- THE MOVE方向：找到你的丙火——让你感觉温暖、被看见的存在。在那附近待着。

## 二月甲木（卯月=阳刃）

**原文核心：** "二月甲木，庚金得所，名阳刃驾杀……书曰：木旺宜火之光辉。"

**调候优先级：** 庚金阳刃驾杀，兼用财资。

**月令特征：** 卯月乙木当令（**阳刃格**）。甲木极旺——"木旺宜火之光辉"。⭐甲木卯月=阳刃！

### 调候规则

[Rule]
ID: QT-甲-02-A
Condition: 庚金得所+财资
Judgment: "阳刃驾杀"，小贵，异途显达，或主武职
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-02-B
Condition: 柱中逢财
Judgment: "英雄独压万人"
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-02-C
Condition: 见癸水+困才杀
Judgment: 🚫 "光棍，重刃遭凶"→ 此配置需要财杀明透才能发挥
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-02-D
Condition: 性情凶暴警示
Judgment: 🚫 "性情凶暴"→ 能量强烈需要精确的出口
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-02-E
Condition: 庚丁两透
Judgment: 大富大贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-02-F
Condition: 木旺+火显辉
Judgment: "秋闱可试"，科甲可望
Safety: ✅
Confidence: 中

**⭐ 甲木卯月阳刃格。** 与庚金酉月阳刃、壬水子月阳刃并称三大阳刃。甲木极旺，必须用庚金七杀制刃（"阳刃驾杀"）。

**象法意象：**
- 二月甲木 = 春天茂盛的森林——枝繁叶茂，已经需要修剪
- 庚金阳刃驾杀 = 斧头砍掉多余的枝叶 = 让力量集中
- 丁火 = 点燃多余木材 = "木旺宜火之光辉"
- 癸水困住庚金 = 下雨让斧头生锈 = 工具没法用

**CIPHER映射：**
- THE HIT方向：你是一片茂盛过头的森林。你不缺力量——你缺一把斧头。
- BLIND SPOT方向：你以为你需要更多滋养。实际你需要被修剪。
- THE MOVE方向：找一个能"砍你"的对手或导师。不是让你舒服的人——是让你变精的人。

## 三月甲木（辰月）

**原文核心：** "三月甲木，木气相竭。先取庚金，次用壬水。"

**调候优先级：** 先庚后壬。

**月令特征：** 辰月戊土当令。春末木气将竭——能量开始消耗。

### 调候规则

[Rule]
ID: QT-甲-03-A
Condition: 庚壬两透
Judgment: 一榜堪图
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-03-B
Condition: 一二庚金+独取壬水
Judgment: 壬透，清秀之人，才学必富
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-03-C
Condition: 天干透二丙+庚藏
Judgment: "钝斧无钢"，富贵难求
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-03-D
Condition: 柱中全无水+戊己透+支成土局
Judgment: 弃命从财格，因人致富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-03-E
Condition: 见戊己+比劫多
Judgment: "杂气夺财"，劳碌到老
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-03-F
Condition: 支成金局+可用丁
Judgment: 成立
Safety: ✅
Confidence: 中

**总结：** "甲乙生寅卯，庚辛干上逢，离南推富贵，坎地却为凶。"

**象法意象：**
- 三月甲木 = 春末的大树——叶开始舒展，但根部的能量已经用了一半
- 庚金 = 修枝的园丁 = 让树形有方向
- 壬水 = 深井水 = 补充消耗

**CIPHER映射：**
- THE HIT方向：你正在把前半段积累的能量用光——现在要么找到新的源头，要么被修剪成型。
- THE MOVE方向：庚（修剪）和壬（补水）同时做。不是要不要的问题，是顺序问题——先剪再补。

## 四月甲木（巳月）

**原文核心：** "四月甲木退气，丙火司权，先癸後丁。"

**调候优先级：** 先癸后丁。庚金太多甲反受病。

**月令特征：** 巳月丙火当令。甲木退气——火太旺，木被烤。

### 调候规则

[Rule]
ID: QT-甲-04-A
Condition: 癸丁与庚齐透
Judgment: 可言科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-04-B
Condition: 癸水不出+有庚丁
Judgment: 富中取贵，异途官职
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-04-C
Condition: 壬透
Judgment: 一富
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-04-D
Condition: 全无水+无庚丁+一派丙戊
Judgment: 🚫 "无用之人"→ 此配置需要水火平衡才能发挥
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-04-E
Condition: 庚金太多
Judgment: "甲反受病"
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-04-F
Condition: 一庚二丙
Judgment: 稍有富贵
Safety: ✅
Confidence: 中

**象法意象：**
- 四月甲木 = 初夏的大树——枝繁叶茂但根部发热
- 癸水 = 地下泉 = 最精准的滋润
- 丁火 = 适度的火 = 让木材发挥价值
- 丙火太旺 = 烈日 = 把叶子都烤蔫了

**CIPHER映射：**
- THE HIT方向：你很繁盛——但繁盛正在消耗你。你需要一口深井水，不是更多阳光。
- THE MOVE方向：癸水=安静的滋养源。不是团体活动，是一对一的深度交谈。

## 五月甲木（午月）

**原文核心：** "五月先癸後丁庚金次之……木化成灰必死（行火运）。"

**调候优先级：** 先癸后丁，庚金次之。运行北地为佳。

**月令特征：** 午月丁火当令。甲木死地——木性虚焦。

### 调候规则

[Rule]
ID: QT-甲-05-A
Condition: 癸透+丁庚相配
Judgment: 中和为贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-05-B
Condition: 五月乏癸+用丁
Judgment: 要运行北地
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-05-C
Condition: 行火运
Judgment: 🚫 "木化成灰必死"→ 此配置下火运会消耗根基，健康方向需要特别留意
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-05-D
Condition: 行西方金运
Judgment: 🚫 "伤官遇杀不测灾来"→ 此配置下金运会造成结构压力
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-05-E
Condition: 运行东方
Judgment: 吉
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-05-F
Condition: 运行北方
Judgment: 次吉
Safety: ✅
Confidence: 中

**总结：** "五六月用丁火，虽运行北地，不致於死。却不利运行火地，号曰木化成灰必死。"

**象法意象：**
- 五月甲木 = 盛夏的大树——表面茂盛，内部虚焦
- 癸水 = 救命的井水 = 防止"木化成灰"
- 行北方水运 = 把树移到凉爽的地方 = 活下来
- 行火运 = 再把火烧到树下 = 死

**CIPHER映射：**
- THE HIT方向：你在最热的环境里。现在不是冲锋，是保命。
- THE MOVE方向：避开高热的人和环境。找一个"凉快"的地方休养。

## 六月甲木（未月）

**原文核心：** "六月三伏生寒，丁火退气。先丁後庚，无癸亦可……木火通明格。"

**调候优先级：** 先丁后庚。五六月本质相同，但六月开始转凉。

**月令特征：** 未月己土当令。三伏生寒，火退气，但土燥。

### 调候规则

[Rule]
ID: QT-甲-06-A
Condition: 丁庚两透
Judgment: 木火通明+金水相济，上上之格
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-06-B
Condition: 满柱丙丁+无官煞
Judgment: "伤官伤尽最为奇"，清贵，才学过人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-06-C
Condition: 柱中多金
Judgment: 🚫 "杀重身轻，先富后贫"→ 此配置压力过大，需印比帮身
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-06-D
Condition: 四柱多土+乙木透
Judgment: ⚠️ 切勿作弃命从才（有比劫不能从）
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-06-E
Condition: 辰支+二己二甲
Judgment: 名利双全，大富大贵（逢时化合格）
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-06-F
Condition: 二己一甲争合
Judgment: 取支中比劫为用
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-06-G
Condition: 木火伤官者
Judgment: "聪明智巧"，但"人同心异，多见多疑"
Safety: ⚠️
Confidence: 中

**⭐ "木火伤官"是甲木夏月的核心美格。** "伤官伤尽最为奇"——丁火发挥甲木全部能量，干净利落。

**总结：** "木火伤官者，聪明智巧，却是人同心异，多见多疑。"

**象法意象：**
- 六月甲木 = 夏末的大树——已经成熟，开始转型
- 丁火 = 精确的火 = 让木材变成能量的形式
- 庚金 = 斧头 = 劈甲引丁
- 甲己合化土 = 合适的土壤 = 大树扎根最深

**CIPHER映射：**
- THE HIT方向：你在转型期。你不再是"长大"的阶段——是"成为某种东西"的阶段。
- BLIND SPOT方向：你以为你的聪明是天赋。实际你的聪明带着防御——"人同心异，多见多疑"。
- THE MOVE方向：找到你的丁火——一个能让你"燃烧"的项目或使命。木火通明=你最美的状态。

## 七月甲木（申月）

**原文核心：** "七月甲木，丁火为尊，庚金次之……七月甲丙，申中有庚。"

**调候优先级：** 丁火为尊，庚金次之。

**月令特征：** 申月庚金当令。甲木被金克——秋木枯槁。

### 调候规则

[Rule]
ID: QT-甲-07-A
Condition: 丁庚两透
Judgment: 科甲定然
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-07-B
Condition: 丁透+庚藏
Judgment: 富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-07-C
Condition: 庚透+丁藏
Judgment: 富
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-07-D
Condition: 有癸水阻隔
Judgment: "便灭丁火"，平常
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-07-E
Condition: 壬水+戊制
Judgment: 可制水存火
Safety: ✅
Confidence: 中

**总结：** "三秋甲庚丙并用……非丁火不能造庚，非庚不能造甲。"——甲木七月需要同时有庚（塑造工具）和丁（点燃能量）。

**象法意象：**
- 七月甲木 = 秋天的大树——叶开始黄，但树干已经成材
- 庚金 = 斧头 = 正是劈甲的时候（"七月甲堪为戟"）
- 丁火 = 炉火 = 把劈好的木材点燃发挥价值
- 庚禄居申 = "杀印相生"——压力和知识互相滋养

**CIPHER映射：**
- THE HIT方向：你已经成材了。现在是被劈开、被点燃、变成某种有用东西的时候。
- THE MOVE方向：接受"被塑造"。不是被伤害——是被使用。

## 八月甲木（酉月）

**原文核心：** "八月甲木，木囚金旺。丁火为先，次用丙火，庚金再次。一丁一庚，科甲定显。"

**调候优先级：** 丁火为先，丙火次之，庚金再次。

**月令特征：** 酉月辛金当令。正官月——甲木被辛金精细克制。

### 调候规则

[Rule]
ID: QT-甲-08-A
Condition: 一丁一庚
Judgment: 科甲定显
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-08-B
Condition: 丙庚两透
Judgment: 富大贵小
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-08-C
Condition: 癸水一透
Judgment: 科甲不全（癸伤丁）
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-08-D
Condition: 丙透无癸
Judgment: 富贵双全
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-08-E
Condition: 丙丁全无
Judgment: 🚫 "僧道之命"→ 独处型路径
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-08-F
Condition: 支成金局+庚露+木被金伤
Judgment: 🚫 "必主残疾"→ 健康方向需要特别留意
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-08-G
Condition: 支成火局
Judgment: 可许假贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-08-H
Condition: 支成木局+干透比劫
Judgment: 反取庚金为先
Safety: ✅
Confidence: 中

**象法意象：**
- 八月甲木 = 深秋的大树——叶落，但材质最硬
- 丁火 = 点燃硬木 = "已经成熟的生命变成有用的火焰"
- 辛金正官 = 小刀精细修剪 = 不是砍，是雕
- 癸水伤丁 = 下雨浇灭炉火 = 你的冷静消解了你的热情

**CIPHER映射：**
- THE HIT方向：你已经硬了。现在不是让你更硬——是让你被精确地塑形。
- THE MOVE方向：找一个丁火——让你那份硬度变成"燃烧的美"。

## 九月甲木（戌月）

**原文核心：** "九月甲木，木星凋零，独爱丁火，壬癸滋扶……甲辰甲戌甲辰甲戌='天元一气'。"

**调候优先级：** 独爱丁火+壬癸滋扶。戊己也可辅。

**月令特征：** 戌月戊土当令。甲木凋零——树叶落尽，根也开始休眠。

### 调候规则

[Rule]
ID: QT-甲-09-A
Condition: 丁壬癸+戊己透+中和
Judgment: 一榜
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-B
Condition: 庚金得所
Judgment: 科甲定然
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-C
Condition: 甲辰甲戌甲辰甲戌
Judgment: **"天元一气"**，身伴明君，富贵寿考
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-D
Condition: 见一二比肩+无庚
Judgment: 平常
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-E
Condition: 四柱木多+端用庚金
Judgment: 为妙
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-F
Condition: 多见戊己
Judgment: 弃命从财格
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-G
Condition: 一派丙丁伤金+有壬癸破丙丁
Judgment: 技艺之流
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-H
Condition: 假伤官+得地逢生
Judgment: "甲乙秋生贵元武"——用水制伤
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-I
Condition: 丁戊俱多+无水
Judgment: 伤官生财格，富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-J
Condition: 甲多庚透
Judgment: 大贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-09-K
Condition: 柱中多庚+丁为奇
Judgment: 富贵
Safety: ✅
Confidence: 中

**⭐ 天元一气格：** 甲辰甲戌甲辰甲戌——四柱天干全甲、地支辰戌冲。这是甲木的最高格局之一，"一才一用"。

**象法意象：**
- 九月甲木 = 深秋的大树——准备冬眠，但最后一次展示价值
- 丁火 = 最后的火光 = 在凋零之前燃烧最亮
- 壬癸 = 地下水 = 维持最后的生命力
- 甲辰甲戌天元一气 = 四棵同样的大树，在两块地轮流生长 = 纯粹之极

**CIPHER映射：**
- THE HIT方向：你在凋零。不是衰败——是收敛。你在准备进入下一个周期。
- BLIND SPOT方向：你以为你应该继续扩张。实际这个月份要你"收"不要"放"。
- THE MOVE方向：丁火+壬癸=热情+深度。在收敛期做一件最能代表你的事。

## 十月甲木（亥月=长生）

**原文核心：** "十月甲木，庚丁为要，丙火次之。忌壬水泛身，须戊土制之。"

**调候优先级：** 庚丁为要，丙火次之。

**月令特征：** 亥月壬水当令。甲木**长生**在亥——进入冬月但开始积蓄新生命力。

### 调候规则

[Rule]
ID: QT-甲-10-A
Condition: 庚丁两透+戊出干
Judgment: **"去浊留清"**，富贵之极
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-10-B
Condition: 乏丁火+庚戊透
Judgment: 稍有富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-10-C
Condition: 甲多制戊+庚金无根
Judgment: 平常人
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-10-D
Condition: 庚戊若透+有比劫
Judgment: 必定富而寿
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-10-E
Condition: 多比劫+只一庚出+坐禄逢生
Judgment: "舍丁从庚"，略富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-10-F
Condition: 支见申亥+戊己得所
Judgment: 可许科甲
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-10-G
Condition: 单己透
Judgment: 贡监而已
Safety: ✅
Confidence: 中

**⭐ 长生与偏印同宫：** 甲木长生在亥，亥中藏壬+甲。壬是甲的偏印——长生处就是生气处。

**象法意象：**
- 十月甲木 = 冬初的大树——表面凋零，地下根在积蓄
- 庚金 = 修剪工具 = 让树的形状更明确
- 丁火 = 小火苗 = 冬天里的温暖
- 壬水泛身 = 洪水淹树 = 需要戊土堤坝

**CIPHER映射：**
- THE HIT方向：表面上你在休息，实际上你在地下生长。
- THE MOVE方向：别被"冬天"的感觉骗了——这是长生的开始，不是终结。

## 十一月甲木（子月）

**原文核心：** "十一月甲木，木性生寒，丁先庚后，丙火佐之。癸水司权，为火金之病。"

**调候优先级：** 丁先庚后，丙火佐之。

**月令特征：** 子月癸水当令。癸水是正印——但冬月癸水=冰水，反而害甲。

### 调候规则

[Rule]
ID: QT-甲-11-A
Condition: 庚丁两透+支见巳寅
Judgment: 科甲有准
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-11-B
Condition: 癸透+伤丁+无戊己辅救
Judgment: 🚫 "残疾之人"→ 健康方向需要特别留意
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-11-C
Condition: 壬水重出+丁火全无
Judgment: 庸人，得丙方妙
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-11-D
Condition: 支成水局+壬透
Judgment: 🚫 **"水泛木浮死无棺木"**→ 此配置能量四散，健康方向需要特别留意
Safety: ⚠️
Confidence: 中

**总结：** "十一月甲木为寒枝，不比春木清茂，端取庚丁。"

**象法意象：**
- 十一月甲木 = 寒冬的大树——真的冷了
- 丁火 = 篝火 = 救命的温暖
- 庚金 = 劈柴的斧头 = 把自己劈开才能燃烧
- 癸水冻木 = 冰雨 = 即使是印（滋养），在冬天也变成负担

**CIPHER映射：**
- THE HIT方向：你现在真的冷。需要的不是安慰（癸水印）——是烈火（丁火伤官）。
- THE MOVE方向：庚+丁=自我牺牲+燃烧。你需要把自己劈开一部分，让剩下的部分烧起来。

## 十二月甲木（丑月）

**原文核心：** "十二月甲木，天寒气冻，木性极寒……先用庚劈甲，方引丁火始得木火有通明之象。"

**调候优先级：** 先庚后丁。

**月令特征：** 丑月己土当令。寒到极点。

### 调候规则

[Rule]
ID: QT-甲-12-A
Condition: 庚丁两透
Judgment: 科甲恩封
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-12-B
Condition: 庚透丁藏
Judgment: 小贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-12-C
Condition: 丁透庚藏
Judgment: 小富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-12-D
Condition: 无庚
Judgment: 🚫 "贫贱"→ 物质积累需要配合特定运程
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-12-E
Condition: 无丁
Judgment: 🚫 "寒儒"→ 此配置需要温暖才能发挥
Safety: ⚠️
Confidence: 中

[Rule]
ID: QT-甲-12-F
Condition: 丁透重重+有比肩
Judgment: "发丁之焰"，富贵
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-12-G
Condition: 丁透+无比肩
Judgment: 稍有衣食
Safety: ✅
Confidence: 中

[Rule]
ID: QT-甲-12-H
Condition: 支多见水+即有比肩
Judgment: 平常
Safety: ⚠️
Confidence: 中

**核心诗：** "甲木无根，男女夭寿。"——十二月甲木必须有根（支见寅卯）才能立业。

**总结：** "乏庚略可，乏丁无用。"——庚可以没有（会很难），但丁是必须的。

**象法意象：**
- 十二月甲木 = 极冬的枯木——冻到要死
- 庚劈甲+丁点火 = 砍下一部分自己当柴烧 = "先庚劈甲方引丁"
- 丁火燃甲 = **"木火通明"** = 甲木十二月唯一的生路

**CIPHER映射：**
- THE HIT方向：最冷的时候。活下去的方式不是保存——是燃烧。
- THE MOVE方向：把"多余的自己"劈开，让必要的部分燃烧。不要所有部分都保住。

## 甲木十二月总览表

Month: ⭐正月（寅）
月令: 甲木·建禄
核心问题: 春寒+余寒
Priority: 丙癸为主
Imagery_OneLine: 初春刚冒芽的大树
THE_HIT: 你需要阳光，不是更多雨
Sensitive: 01-D/E/F/J/K/M

Month: ⭐二月（卯）
月令: 乙木·阳刃
核心问题: 木旺需剪
Priority: 庚金驾杀
Imagery_OneLine: 茂盛过头的森林
THE_HIT: 你缺的是斧头
Sensitive: 02-C/D

Month: 三月（辰）
月令: 戊土
核心问题: 木气相竭
Priority: 先庚后壬
Imagery_OneLine: 春末的大树
THE_HIT: 先剪再补
Sensitive: —

Month: 四月（巳）
月令: 丙火
核心问题: 火旺木焦
Priority: 先癸后丁
Imagery_OneLine: 初夏繁盛但根发热
THE_HIT: 你需要一口深井水
Sensitive: 04-D

Month: 五月（午）
月令: 丁火
核心问题: 木死地
Priority: 癸为用
Imagery_OneLine: 盛夏虚焦的大树
THE_HIT: 保命比冲锋重要
Sensitive: 05-C/D

Month: 六月（未）
月令: 己土
核心问题: 三伏生寒
Priority: 丁庚为主
Imagery_OneLine: 夏末开始转型
THE_HIT: 你在"成为某种东西"
Sensitive: 06-C

Month: 七月（申）
月令: 庚金
核心问题: 秋金克木
Priority: 丁庚并用
Imagery_OneLine: 秋天已经成材
THE_HIT: 接受被塑造
Sensitive: —

Month: 八月（酉）
月令: 辛金
核心问题: 木囚金旺
Priority: 丁先丙后
Imagery_OneLine: 深秋最硬的木
THE_HIT: 被精确地塑形
Sensitive: 08-E/F

Month: 九月（戌）
月令: 戊土
核心问题: 木星凋零
Priority: 丁火为主
Imagery_OneLine: 凋零前最后一次燃烧
THE_HIT: 收敛期做最能代表你的事
Sensitive: —

Month: 十月（亥）
月令: 壬水·长生
核心问题: 水泛木浮
Priority: 庚丁戊为要
Imagery_OneLine: 冬初表面凋零地下生长
THE_HIT: 表面休息实际长生
Sensitive: —

Month: 十一月（子）
月令: 癸水
核心问题: 寒枝
Priority: 丁先庚后
Imagery_OneLine: 寒冬的大树
THE_HIT: 你需要烈火不是安慰
Sensitive: 11-B/D

Month: 十二月（丑）
月令: 己土
核心问题: 极寒
Priority: 先庚后丁
Imagery_OneLine: 冻到要死的枯木
THE_HIT: 活下去的方式是燃烧
Sensitive: 12-D/E

# 第二部分：格局规则（子平真诠）

## 甲木十神对照表

Stem: 甲
TenGod: 比肩

Stem: 乙
TenGod: 劫财

Stem: 丙
TenGod: 食神

Stem: 丁
TenGod: 伤官

Stem: 戊
TenGod: 偏财

Stem: 己
TenGod: 正财

Stem: 庚
TenGod: 七杀

Stem: 辛
TenGod: 正官

Stem: 壬
TenGod: 偏印（枭神）

Stem: 癸
TenGod: 正印

## 甲木十二月格局映射表

Month: ⭐正月
Branch: 寅
HiddenStem: 甲丙戊
MainGod: 甲(比肩)
Patterns: **建禄格**
Notes: 甲禄在寅。丙透→食神格；戊透→偏财格

Month: ⭐二月
Branch: 卯
HiddenStem: 乙
MainGod: 乙(劫财)
Patterns: **阳刃格**
Notes: 甲阳刃在卯

Month: 三月
Branch: 辰
HiddenStem: 戊乙癸
MainGod: 戊(偏财)
Patterns: **杂气格**
Notes: 戊透→偏财格；癸透→正印格；乙透→劫财

Month: 四月
Branch: 巳
HiddenStem: 丙庚戊
MainGod: 丙(食神)
Patterns: **食神格**
Notes: 庚透→七杀格；戊透→偏财格

Month: 五月
Branch: 午
HiddenStem: 丁己
MainGod: 丁(伤官)
Patterns: **伤官格**
Notes: 己透→正财格

Month: 六月
Branch: 未
HiddenStem: 己丁乙
MainGod: 己(正财)
Patterns: **杂气格**
Notes: 己透→正财格；丁透→伤官格；乙透→劫财

Month: 七月
Branch: 申
HiddenStem: 庚壬戊
MainGod: 庚(七杀)
Patterns: **七杀格**
Notes: 壬透→偏印格；戊透→偏财格

Month: 八月
Branch: 酉
HiddenStem: 辛
MainGod: 辛(正官)
Patterns: **正官格**
Notes: 专气

Month: 九月
Branch: 戌
HiddenStem: 戊辛丁
MainGod: 戊(偏财)
Patterns: **杂气格**
Notes: 戊透→偏财格；辛透→正官格；丁透→伤官格

Month: ⭐十月
Branch: 亥
HiddenStem: 壬甲
MainGod: 壬(偏印)
Patterns: **偏印格**
Notes: 甲长生在亥。甲透→比肩

Month: 十一月
Branch: 子
HiddenStem: 癸
MainGod: 癸(正印)
Patterns: **正印格**
Notes: 专气

Month: 十二月
Branch: 丑
HiddenStem: 己辛癸
MainGod: 己(正财)
Patterns: **杂气格**
Notes: 己透→正财格；辛透→正官格；癸透→正印格

**甲木核心特殊性（全10日主最复杂）：**

1. **三个关键月位**：寅月建禄、卯月阳刃、亥月长生——甲木在命理结构上"最有根"
2. **甲己合** — 化土成**稼穑格**（甲失去自己变成土）
3. **曲直格** — 甲木专旺格（春天支全寅卯辰或亥卯未）
4. **木火通明** — 木生火伤官的最秀配置（格局配置的形容词，非独立格局）
5. **"甲木无从化"** — 子平真诠特别指出：甲不易从化（除甲己合化土外，甲不易作弃命）

> **⚠️ 三重根的真正含义：** 寅/卯/亥三月生甲木"得地"机会高，但这只意味着"有底气"，不等于"身强"。最终强弱要综合四柱。例如亥月甲木长生，如果年月时三柱全是金水克泄，依然身弱。"有根"是结构层面的判断，"身强身弱"是五行力量的判断——两者不能混为一谈。

## 甲木可成格局详细规则

### 一、建禄格 ⭐（甲木寅月）

**出现月份：** 寅月（甲禄在寅）

**核心原则：** "月令为命局之提纲，日干得禄，先得月令之旺气，日主必不甚衰"——建禄格的甲木必不弱，用神另取于财官食伤。

[Rule]
ID: ZP-甲-禄-成01
Condition: 寅月+辛金正官透+财印相随
Judgment: 官印双全
Narrative: 你有天然的舞台——规则和资源都在等你

[Rule]
ID: ZP-甲-禄-成02
Condition: 寅月+庚金七杀透+食神制+戊己财生
Judgment: 煞生食制
Narrative: 你的力量配得上最大的压力

[Rule]
ID: ZP-甲-禄-成03
Condition: 寅月+丙丁食伤透+财接
Judgment: 食伤生财
Narrative: 你是天生的创造者——表达直接变钱

[Rule]
ID: ZP-甲-禄-成04
Condition: 寅月+戊己财透+食伤化劫
Judgment: 财格
Narrative: 你的力量需要经过才华变成财富

[Rule]
ID: ZP-甲-禄-败01
Condition: 寅月+无财官食伤
Judgment: 孤禄无用
Narrative: 一身力气不知往哪使

[Rule]
ID: ZP-甲-禄-败02
Condition: 寅月+比劫重透+无官煞食伤
Judgment: 争财
Narrative: 你的同类太多——力量互相抵消

**取运喜忌：**
- 财多身弱者：喜比劫
- 财多身强者：喜官杀，或食伤
- 官杀多身强者：喜财
- 伤食多身强者：喜财
- 比劫多者：喜官杀

### 二、阳刃格 ⭐（甲木卯月）

**出现月份：** 卯月（甲阳刃在卯）

**核心原则：** "阳刃者，劫我正财之神，乃正财之七煞也。刃宜伏制，官煞皆宜，财印相随，尤为贵显。"——甲木阳刃必须用庚金制伏（阳刃驾杀）。

[Rule]
ID: ZP-甲-刃-成01
Condition: 卯月+庚金七杀透+财印相助
Judgment: ⭐ **煞刃格**（"阳刃驾杀"最大贵）
Narrative: 你的力量需要最硬的对手来磨砺

[Rule]
ID: ZP-甲-刃-成02
Condition: 卯月+辛金正官透+戊土印生
Judgment: **官印护刃**（次贵，需更多支援）
Narrative: 温和的规则+爆发的力量=文化型权威

[Rule]
ID: ZP-甲-刃-成03
Condition: 卯月+丁火伤官透+木火通明
Judgment: 刃用伤官泄
Narrative: 你的力量只能通过最激烈的创造释放

[Rule]
ID: ZP-甲-刃-成04
Condition: 卯月+戊己财旺+食伤通关
Judgment: 刃用财
Narrative: 你的野心需要先通过才华才能变成资源

[Rule]
ID: ZP-甲-刃-败01
Condition: 卯月+无官煞+无食伤
Judgment: 刃旺无制
Narrative: 力量无处可去——内爆或外伤

[Rule]
ID: ZP-甲-刃-败02
Condition: 卯月+官煞被合或被冲
Judgment: 制失效
Narrative: 能制住你的人被挪走了——你失控

[Rule]
ID: ZP-甲-刃-败03
Condition: 卯月+见癸水印+困了庚金
Judgment: 🚫 "困了才杀，主为光棍"→ 印化煞不利财杀发挥
Narrative: 你的学问/保护消解了你的对手

**⚠️ 甲卯阳刃格的制刃优先级（庚 > 辛）：**
- **庚金七杀（首选）**：穷通宝鉴"阳刃驾杀"专指庚透——斧砍大树，力度匹配。配合财星（戊己）生煞为最大贵。
- **辛金正官（次选）**：辛金克甲力度不够（小刀刮大树），不能独立制刃。必须配合戊土印生辛金，形成"官印相生"结构才能成格。这条路径的贵度低于成01。
- **两者不平权**——遇到辛金正官透干时，必须核查是否有戊土相生；仅有辛金无戊土则不成"官印护刃"，只能走其他路径。

**⭐ 三大阳刃格差异（与庚金/壬水对比）：**

Dimension: 制刃优先
甲木卯月阳刃: 庚金七杀（驾杀）
庚金酉月阳刃: 丁火正官/丙火七杀
壬水子月阳刃: 戊土七杀

Dimension: 核心美格
甲木卯月阳刃: 煞刃格+木火通明
庚金酉月阳刃: 煞刃格+金水相涵
壬水子月阳刃: 煞刃格+丙戊并用

Dimension: 驱动方式
甲木卯月阳刃: 用对手锻造自己
庚金酉月阳刃: 用火把自己炼成器
壬水子月阳刃: 用堤坝给洪水方向

**取运喜忌：**
- 阳刃用官：喜助官运、印运。忌伤食运（克官）
- 煞刃格：煞轻→喜助煞；煞重→喜身旺印运
- 刃用伤官：喜财运。忌印运（夺伤）

### 三、七杀格（甲木见庚金为七杀）

**出现月份：** 申月（庚金当令→七杀格）、巳月（杂气庚透）、戌月（杂气戊+辛）

**核心原则：** 甲木七杀=斧头劈大树。不是伤害，是成器。

[Rule]
ID: ZP-甲-煞-成01
Condition: 月令庚七杀+丁伤官制+身强
Judgment: 伤官驾煞（最美）
Narrative: 你用最激烈的创造力驯服了最大的对手

[Rule]
ID: ZP-甲-煞-成02
Condition: 七杀+壬水偏印化+身弱
Judgment: 煞印相生
Narrative: 高压通过你的知识变成养分

[Rule]
ID: ZP-甲-煞-成03
Condition: 七杀+戊己财生+身煞两停
Judgment: 财生煞
Narrative: 你的资源和对手都在变强——平衡中前进

[Rule]
ID: ZP-甲-煞-败01
Condition: 七杀+财党煞+无制
Judgment: 财滋煞
Narrative: 你在喂大一个已经太强的对手

[Rule]
ID: ZP-甲-煞-救01
Condition: 煞逢食制+印护煞+财去印
Judgment: 去印存食
Narrative: 回到最直接的对抗——别依赖保护

**⭐ 七月甲木核心诗：** "非丁火不能造庚，非庚不能造甲"——甲木必须有庚（对手）+丁（创造力），缺一不可。

### 四、正官格（甲木见辛金为正官）

**出现月份：** 酉月（辛金当令→正官格）、戌月（杂气辛透）、丑月（杂气辛透）

**核心原则：** 甲木正官=小刀精雕大树。细腻、有序、规范。

[Rule]
ID: ZP-甲-官-成01
Condition: 酉月辛金正官+财印相随不碍
Judgment: 官清印正
Narrative: 你在规则里有位置——规则也在保护你

[Rule]
ID: ZP-甲-官-成02
Condition: 正官+戊己财生官
Judgment: 财旺生官
Narrative: 你的资源为你换来地位

[Rule]
ID: ZP-甲-官-败01
Condition: 正官+丁火伤官透
Judgment: 伤官见官（非金水冬月）
Narrative: 你的反叛直接冲击你的位置

[Rule]
ID: ZP-甲-官-败02
Condition: 正官+庚七杀混
Judgment: 官煞混杂
Narrative: 温和的规则和严厉的规则同时作用——你被撕裂

[Rule]
ID: ZP-甲-官-救01
Condition: 官逢伤+壬癸印制伤
Judgment: 印护官
Narrative: 你的学识帮你控制住了叛逆

[Rule]
ID: ZP-甲-官-救02
Condition: 官煞混杂+合去七杀
Judgment: 取清
Narrative: 你学会了只接受一种规则

### 五、财格（甲木见戊土偏财/己土正财）

**出现月份：** 辰月（戊土当令→偏财格）、戌月（杂气戊透）、未月（己土当令→正财格）、丑月（杂气己透）

**⚠️ 甲己合化土：** 甲木为日主，见己土合。合化土成功→稼穑格。合不化→财格变质。

[Rule]
ID: ZP-甲-财-成01
Condition: 月令戊/己财+辛金正官透
Judgment: 财旺生官
Narrative: 你赚的钱直接换来地位

[Rule]
ID: ZP-甲-财-成02
Condition: 财星+丙丁食伤生财+身强
Judgment: 食伤生财
Narrative: 你的才华直接变钱

[Rule]
ID: ZP-甲-财-成03
Condition: 弃命从财格（身弱无根+财极旺+无比劫）
Judgment: 从财格
Narrative: 你不是积累者——你是放大器

[Rule]
ID: ZP-甲-财-败01
Condition: 财星+甲乙比劫争财
Judgment: 群劫争财
Narrative: 同行太多——蛋糕被分光

[Rule]
ID: ZP-甲-财-败02a
Condition: **甲己合化土成立**（条件全满足）
Judgment: 稼穑格（变格）
Narrative: 你在关系中变成了另一个人——不是失去，是转型

[Rule]
ID: ZP-甲-财-败02b
Condition: **甲己合不化**（大多数情况）
Judgment: 正财被绊，格变
Narrative: 你和你追求的东西互相牵制——谁都动不了

**⚠️ 甲己合化土的四条件（必须同时满足）：**
1. 月令是土月（辰戌丑未）或地支土局，且日主坐土支
2. 日主甲木**无强根**（不见寅卯当月令、不见甲乙比劫透干；地支杂气木余气不算强根）
3. **化神戊土透干**（合化必须有化神出现）
4. **无金透干克化神**（庚辛透干会破化——甲己合化土的阻化主要不是木来阻，是金来克化神）

四条件缺一 → 合不化 → ZP-甲-财-败02b处理。

### 六、印绶格（甲木见壬水偏印/癸水正印）

**出现月份：** 亥月（壬水当令→偏印格）、子月（癸水当令→正印格）、辰月（杂气癸透）

**⚠️ 亥月特殊性：甲长生在亥。** 甲木亥月既是偏印格又是长生——壬水生甲木，甲在亥藏干。甲木亥月较旺。

[Rule]
ID: ZP-甲-印-成01
Condition: 亥月+庚丁两透+戊出干
Judgment: **"去浊留清"**（富贵之极）
Narrative: 你的根基+对手+创造力三者完美配合

[Rule]
ID: ZP-甲-印-成02
Condition: 子月+身印两旺+丁火伤官泄秀
Judgment: 泄秀
Narrative: 你的学识太多需要出口

[Rule]
ID: ZP-甲-印-成03
Condition: 印轻+庚七杀生印
Judgment: 煞印相生
Narrative: 压力反哺你的学识

[Rule]
ID: ZP-甲-印-败01
Condition: 印重+戊己财破印
Judgment: 财破印
Narrative: 追钱的过程中破坏了你的根基

[Rule]
ID: ZP-甲-印-败02
Condition: **水泛木浮**（通用病格）
Judgment: 🚫 **"水泛木浮死无棺木"**→ 此配置印过旺漂浮日主，需戊土堤防
Narrative: 你的知识和情绪淹没了你自己

**⭐ 水泛木浮（通用病格）：**
- **通用条件**：壬癸水透干≥2 + 申子辰水局或亥月 + 无戊土制水
- **应用月份分级**：
  - **冬月（亥子丑）**：最严重，调候+格局双重病
  - **春月（寅卯）**：木已得令，水泛但木有根，损伤较轻
  - **其他月份**：单纯水泛木浮病，按格局法处理
- **本质机制**：印（生我者）过旺，反而漂浮日主。这不是月份特定，是配置特定。冬月水当令更容易触发，所以穷通宝鉴在冬月特别强调。

### 七、食神格/伤官格（甲木见丙火食神/丁火伤官）

**出现月份：** 巳月（丙火当令→食神格）、午月（丁火当令→伤官格）、未月（杂气丁透）

**⭐ 核心美格"木火通明"：** 甲木生丁火=大树燃烧=最秀的创造力释放。

[Rule]
ID: ZP-甲-食-成01
Condition: 月令丙食神+戊己财透
Judgment: 食神生财
Narrative: 你的创造力直接变收入——自然流通

[Rule]
ID: ZP-甲-食-成02
Condition: 食神+庚七杀透+无财
Judgment: 食神制煞
Narrative: 你用温和的才华驯服了最大的压力

[Rule]
ID: ZP-甲-伤-成01
Condition: 月令丁伤官+戊己财+身强
Judgment: **伤官生财格**（传统称"木火通明"，甲木夏月最秀的子类）
Narrative: 你的叛逆+才华=财富（最秀配置之一）

[Rule]
ID: ZP-甲-伤-成02
Condition: 伤官+壬癸印有根+身弱
Judgment: 伤官佩印
Narrative: 叛逆被学问收敛——有深度的不羁

[Rule]
ID: ZP-甲-伤-成03
Condition: 伤官+庚七杀+身强
Judgment: 伤官驾杀
Narrative: 你的创造力+对手=成就

[Rule]
ID: ZP-甲-食-败01
Condition: 食神+壬偏印透（枭神夺食）
Judgment: 破格
Narrative: 旧体系在扼杀你的创造力

[Rule]
ID: ZP-甲-伤-败01
Condition: 伤官+辛正官透（非冬月水木伤官）
Judgment: 伤官见官
Narrative: 你的叛逆正在冲击你唯一的规则

**⚠️ 甲木没有"水木伤官见官不忌"的例外** — 那是壬水的特例。甲木是木日主，木生火，火克金（官）——甲木伤官见官仍然是破格。

### 八、曲直格 ⭐（甲木专旺格）

**出现月份：** 春月（寅卯辰月），支全寅卯辰东方或亥卯未木局。

**成立条件（引用从格判定通用规则）：**
1. 甲乙日主
2. 生于春月
3. 地支全寅卯辰或亥卯未
4. 天干无庚辛申酉冲克
5. 天干有壬癸甲乙资生比辅

[Rule]
ID: ZP-甲-曲-成01
Condition: 春月+支全寅卯辰+无庚辛
Judgment: **曲直仁寿格**
Narrative: 你最强的状态是做纯粹的自己——任何平衡都会削弱你

[Rule]
ID: ZP-甲-曲-成02
Condition: 春月+亥卯未木局+天干无金克
Judgment: 曲直格（局）
Narrative: 同上

[Rule]
ID: ZP-甲-曲-败01
Condition: 支局全+庚辛透干克木
Judgment: 曲直破格
Narrative: 你本该一路向上但被一个"对手"打断

**取运喜忌（专旺格通用）：**
- 喜：水（印）、木（比劫）、火（食伤）
- 忌：金（官煞克木最忌）、土（财为中性，原局有食伤化则吉）
- 大运最忌西方金运

**⭐ 曲直格的CIPHER叙事：** 这是五种专旺格中最"正向"的一种（仁寿格——中华传统里木主仁，代表生长）。用户看到"你是曲直格"会感觉被认可。

### 九、稼穑格（甲己合化土的特例）

**甲日干不直接成稼穑格** — 稼穑格是"戊己日主"的专旺格。但甲木通过甲己合化土，可以"变成"稼穑格的一部分。

[Rule]
ID: ZP-甲-化-01
Condition: 甲己合化土四条件全满足+月令土当令
Judgment: 化气格（甲化土）

**CIPHER叙事方向：** "你在一段特定的关系里，不是你自己了——你变成了'我们'。这不是失去自己，是你的一种形态。"

### 十、杂气格

[Rule]
ID: ZP-甲-杂-01
Condition: 辰月+戊透
Judgment: 偏财格

[Rule]
ID: ZP-甲-杂-02
Condition: 辰月+癸透
Judgment: 正印格

[Rule]
ID: ZP-甲-杂-03
Condition: 辰月+乙透
Judgment: 劫财格

[Rule]
ID: ZP-甲-杂-04
Condition: 戌月+戊透
Judgment: 偏财格

[Rule]
ID: ZP-甲-杂-05
Condition: 戌月+辛透
Judgment: 正官格

[Rule]
ID: ZP-甲-杂-06
Condition: 戌月+丁透
Judgment: 伤官格

[Rule]
ID: ZP-甲-杂-07
Condition: 未月+己透
Judgment: 正财格

[Rule]
ID: ZP-甲-杂-08
Condition: 未月+丁透
Judgment: 伤官格

[Rule]
ID: ZP-甲-杂-09
Condition: 未月+乙透
Judgment: 劫财格

[Rule]
ID: ZP-甲-杂-10
Condition: 丑月+己透
Judgment: 正财格

[Rule]
ID: ZP-甲-杂-11
Condition: 丑月+辛透
Judgment: 正官格

[Rule]
ID: ZP-甲-杂-12
Condition: 丑月+癸透
Judgment: 正印格

## 甲木核心美格/病格标注

Name: 建禄格
Nature: 美格
Trigger: 寅月
Product_Meaning: 天然的舞台

Name: 阳刃格
Nature: 中性（需制）
Trigger: 卯月
Product_Meaning: 强大但需要出口

Name: 阳刃驾杀
Nature: 美格（最大贵）
Trigger: 卯月+庚透
Product_Meaning: 力量被完美使用

Name: 官印护刃
Nature: 美格（次贵）
Trigger: 卯月+辛透+戊印
Product_Meaning: 温和规则+印护

Name: 木火通明（配置标签）
Nature: 伤官生财格的子类
Trigger: 丁透+身强+夏月
Product_Meaning: 甲木最美的状态（传统称呼）

Name: **曲直仁寿**
Nature: **美格（专旺）**
Trigger: 春月支全寅卯辰或亥卯未
Product_Meaning: 纯粹的自我

Name: 去浊留清
Nature: 美格
Trigger: 亥月庚丁戊透
Product_Meaning: 三者完美配合

Name: **水泛木浮**
Nature: **病格（通用）**
Trigger: 水透干≥2+水局/亥月+无戊
Product_Meaning: 印过旺漂浮日主

Name: 伤官见官
Nature: 破格
Trigger: 辛官+丁伤
Product_Meaning: 叛逆冲击位置

Name: 财多身弱
Nature: 病格
Trigger: 支成金局+多透庚辛
Product_Meaning: 压力超载

## 甲木特殊配置（非标准格局）

Name: **天元一气**
Nature: 罕见配置，象征意义大于实战意义
Trigger: 四柱天干全甲（如甲辰、甲戌、甲辰、甲戌）
说明: 干支组合的雅称，不是术数意义上的独立格局。古籍多以历史人物的命例引用此种配置，实战中CIPHER用户遇到的概率极低。象征"极致纯粹"的存在状态。

## 甲木与其他日主的格局交叉验证

### 甲木是金日主的财星——反向验证
- 庚金偏财=甲木 → 庚金"铁锤砸藤蔓"意象中的"砸"对应甲木被劈
- 辛金偏财=甲木 → 辛金"雕木"意象对应甲木被精细加工
- 甲木的"被劈成器"视角与庚金的"挥斧成型"视角互为镜像

### 甲木是水日主的食神——反向验证
- 壬水食神=甲木 → 壬水"灌溉大河"对应甲木"接收灌溉"
- 癸水食神=甲木 → 癸水"雨露滋润"对应甲木"被温柔滋养"

### Sam的盘（辛金）视角
Sam的辛金日主，甲木是偏财。甲木"被劈成器"=辛金"劈出甲木"=Sam通过输出让别人"成器"的模式。

# 第三部分：象法意象库

## 甲木象法意象库

## 一、甲木核心原型

### 古籍原始定位

Source: 滴天髓
Original: "甲木参天，脱胎要火。春不容金，秋不容土。火炽乘龙，水宕骑虎。地润天和，植立千古"
Core_Imagery: 参天大树、需要火脱胎、春不怕金、秋不被土困

Source: 任铁樵注
Original: "甲为纯阳之木，体本坚固，参天之势，又极雄壮"
Core_Imagery: 纯阳之木、雄壮、坚固

Source: 穷通宝鉴
Original: "春月之木，余寒犹存，喜火温暖，则无盘屈之患"
Core_Imagery: 春木需要火来舒展

Source: 穷通宝鉴
Original: "夏月之木，根干叶枯，欲得水盛，而成滋润之功"
Core_Imagery: 夏木需要水救

Source: 穷通宝鉴
Original: "秋月之木，气渐凋零……欲得刚金而修削"
Core_Imagery: 秋木需要金来修削成器

Source: 穷通宝鉴
Original: "冬月之木，盘屈在地，欲土多以培养，恶水盛而忘形"
Core_Imagery: 冬木需要土护根

Source: 神峰通考
Original: "甲木若无根，全赖申子辰"
Core_Imagery: 甲木无根时靠水木扶持

Source: 三命通会
Original: "甲乙为木，主仁"
Core_Imagery: 木主仁，生长向上

### CIPHER核心原型定义

**甲木 = THE PILLAR**

一句话：**你是一棵参天大树——生来就是要被看见、被使用、被成就的。**

核心物质意象（按优先级）：
1. **参天大树/栋梁** — 雄壮、向上、刚直
2. **森林** — 甲木成林时的集体形态
3. **古树** — 天元一气格时的原型（百年大树，纯粹无杂）
4. **萌芽** — 正月甲木的状态
5. **春生嫩芽** — 甲木的生命力本源

**甲木核心动作：**
- **参天**（向上）— 甲木的本能
- **脱胎**（成型）— 需要火来转化
- **植立**（稳固）— 最终状态
- **成器**（被用）— 被庚金劈、被丁火燃

### 甲木与乙木的原型对比

Dimension: 物质
甲木 THE PILLAR: 参天大树/栋梁/古树
乙木 THE VINE: 花草/藤蔓/禾稼

Dimension: 本质
甲木 THE PILLAR: 刚直向上，"参天"
乙木 THE VINE: 曲折攀附，"刲羊解牛"

Dimension: 对金
甲木 THE PILLAR: "春不容金"/秋天用金修削
乙木 THE VINE: "秋乙逢金非贫即夭"——怕金

Dimension: 对火
甲木 THE PILLAR: "火炽乘龙"（坐辰泄火）
乙木 THE VINE: 火多"阳焦木性"

Dimension: 对水
甲木 THE PILLAR: "水宕骑虎"（坐寅纳水）
乙木 THE VINE: 水多"漂浮"

Dimension: 核心需求
甲木 THE PILLAR: 被劈成器（庚）+ 被点燃（丁）
乙木 THE VINE: 被滋养（癸）+ 被保护（丙）

Dimension: 运动方向
甲木 THE PILLAR: 向上、直接、扩张
乙木 THE VINE: 曲折、攀附、延展

Dimension: 成长方式
甲木 THE PILLAR: 靠自己的结构（木质）
乙木 THE VINE: 靠环境的支撑（藤蔓攀树）

Dimension: THE HIT方向
甲木 THE PILLAR: 你需要被使用——不被使用就是浪费
乙木 THE VINE: 你需要被珍惜——不被珍惜就枯萎

## 二、甲木与十天干的关系意象

TenGod: 比肩·甲木
Stem: 同类之阳
NaturalImagery: 两棵大树并立——一起成林但争阳光
OneLine: 你的同类是战友也是对手——空间不够两个都参天

TenGod: 劫财·乙木
Stem: 同类之阴
NaturalImagery: **"藤萝系甲"**——藤蔓缠绕大树，互相扶持
OneLine: 你身边的"柔软"同伴其实在帮你——春可秋可

TenGod: ⭐食神·丙火
Stem: 我生之阳
NaturalImagery: 太阳照大树——"寒木向阳"
OneLine: 你最好的状态是有一个温暖的方向让你伸展

TenGod: ⭐伤官·丁火
Stem: 我生之阴
NaturalImagery: 大树燃烧——**"木火通明"**
OneLine: 你最美的状态是燃烧自己照亮别人

TenGod: 偏财·戊土
Stem: 我克之阳
NaturalImagery: 大树扎根山岗——硬土需要疏通
OneLine: 你的财富靠"疏土"——扎根在硬的地方

TenGod: 正财·己土
Stem: 我克之阴
NaturalImagery: 大树扎根田园——**甲己合化土**
OneLine: 你对钱的关系最深——甚至能让你失去自己的形状

TenGod: ⭐七杀·庚金
Stem: 克我之阳
NaturalImagery: **斧头劈大树——成器**
OneLine: 你的对手不是伤害你的——是把你变成栋梁的

TenGod: 正官·辛金
Stem: 克我之阴
NaturalImagery: 小刀雕大树——精细加工
OneLine: 温和的规则让你变成艺术品

TenGod: 偏印·壬水
Stem: 生我之阳
NaturalImagery: 大河灌溉——怕水多"漂浮"
OneLine: 你的资源太多反而让你失去重心

TenGod: 正印·癸水
Stem: 生我之阴
NaturalImagery: 雨露滋润——春天的甘霖
OneLine: 你需要的滋养是细而持续的，不是大河

## 三、甲木十二月意象库（季节变体）

### 春季（寅卯辰月）—— 春木复苏

Month: ⭐正月·寅
Scene: 刚冒芽的大树——枝芽嫩绿但余寒未尽
CoreConflict: 有力量但没温度
Solution: 丙火太阳=让它舒展开；癸水=温和的春雨

Month: ⭐二月·卯
Scene: 茂盛过头的森林——枝条乱伸
CoreConflict: 力量太多需要修剪
Solution: 庚金阳刃驾杀=斧头修剪；丁火=燃烧多余木材

Month: 三月·辰
Scene: 春末的大树——叶舒展但根部能量用了一半
CoreConflict: 开始消耗
Solution: 庚金修枝+壬水补根

**春季甲木总方向：** 你有天然的力量——但需要方向（庚）和温度（丁）。光有力量不够。

### 夏季（巳午未月）—— 夏木枯槁

Month: 四月·巳
Scene: 初夏繁盛的大树——但根部发热
CoreConflict: 火太旺，木被烤
Solution: 癸水（深井水）+ 丁火（适度的火）

Month: 五月·午
Scene: 盛夏虚焦的大树——"木化成灰必死"
CoreConflict: 死地——最危险的月份
Solution: 运行北方水地=活；运行火地=死

Month: 六月·未
Scene: 夏末转型的大树——开始成熟
CoreConflict: 火退气但土燥
Solution: **木火通明**=丁庚两透=最秀

**夏季甲木总方向：** 你在受考验。不是"冲刺"，是"活下去"——找到水源，避开烈火。

### 秋季（申酉戌月）—— 秋木成材

Month: 七月·申
Scene: 秋天的大树——叶开始黄但树干已经成材
CoreConflict: 准备被劈成器
Solution: 丁庚两透=**"秋甲堪为戟"**

Month: 八月·酉
Scene: 深秋最硬的木——叶落但质地最好
CoreConflict: 被正官精细修剪
Solution: 丁火点燃+辛金雕琢=艺术品

Month: 九月·戌
Scene: 凋零前最后一次燃烧——叶几乎落光
CoreConflict: 收敛期
Solution: 丁火+壬癸=最后的辉煌；或**天元一气**=最纯粹的存在

**秋季甲木总方向：** 你在"成型"。不是被伤害——是被塑造。接受被劈、被雕、被燃烧。

### 冬季（亥子丑月）—— 冬木归根

Month: ⭐十月·亥
Scene: 冬初的大树——表面凋零地下生长（长生月）
CoreConflict: 积蓄新生命力
Solution: **"去浊留清"**=庚丁戊透=完美配置

Month: 十一月·子
Scene: 寒冬的大树——真的冷了
CoreConflict: 寒枝
Solution: 丁火先+庚金后=烈火让自己活过冬

Month: 十二月·丑
Scene: 冻到要死的枯木——极寒
CoreConflict: 活不活过冬的问题
Solution: 先庚劈甲+丁火燃甲=**木火通明**

**冬季甲木总方向：** 你在过冬。活下去的方式不是保存——是燃烧。把多余的自己劈开，让必要的部分烧起来。

## 四、甲木五行配置变体意象

### 木多（比劫重）

Imagery: 成林
Scene: 一片森林——每棵树都是你
Mapping: 你的同类太多=力量互相抵消

Imagery: 两树争阳
Scene: 两棵大树挤在一起抢阳光
Mapping: 你身边的"战友"也是对手

Imagery: 曲直仁寿
Scene: 一片纯粹的森林——只有木没有别的
Mapping: ⭐ 支全寅卯辰=专旺格=纯粹的你

### 金多（官煞重）

Imagery: 斧头围树
Scene: 四面八方的斧头指着你——还没劈
Mapping: 压力超载，还没转化成成就

Imagery: 钝斧无钢
Scene: 斧头太多但都钝了
Mapping: 对手很多但没有真能磨你的

Imagery: 秋甲堪为戟
Scene: ⭐ 一柄好斧头+一棵好木=最好的武器
Mapping: 一个真正的对手+一个好的自己=成就

### 水多（印重）

Imagery: 水泛木浮
Scene: 洪水中漂浮的大树——"死无棺木"
Mapping: ⭐ 病格——情绪/知识淹没了你自己

Imagery: 孤舟
Scene: 一棵树漂在海上——没有方向
Mapping: 你有很多资源但没有根

Imagery: 地润天和
Scene: 适量的水让你植立千古
Mapping: ⭐ 水不多不少=最稳定

### 火多（食伤重）

Imagery: 木火通明
Scene: ⭐ 大树燃烧照亮天地
Mapping: 你的创造力在最美的状态

Imagery: 焚烧
Scene: 木被烧成灰——"木化成灰必死"
Mapping: 输出过度=自焚

Imagery: 寒木向阳
Scene: ⭐ 春天的大树向阳舒展
Mapping: 你有温度有方向

### 土多（财重）

Imagery: 财多身弱
Scene: 一棵树埋在厚土里——"富屋贫人"
Mapping: 钱很多但你没精力享用

Imagery: 甲己合化
Scene: ⭐ 大树和土融为一体
Mapping: 在关系中变成"我们"——不是失去自己

Imagery: 扎根山岗
Scene: 树扎根在硬土上——稳固
Mapping: 你的财富靠扎根在硬的地方

### 缺火

Imagery: 寒木无花
Scene: 春天的大树但没有阳光——不开花
Mapping: 你有能力但没被点燃

Imagery: 不能脱胎
Scene: 木不能变成有用的东西
Mapping: ⭐ 缺火=甲木最核心的缺陷

### 缺土

Imagery: 无根浮木
Scene: 一棵树漂在水面——没有土扎根
Mapping: 你没有归属感

Imagery: 散漫
Scene: 没有方向的生长
Mapping: 你的力量四散没有聚焦

### 缺金

Imagery: 无斧之材
Scene: 好木头但没有斧头劈
Mapping: 你是栋梁之材但没人会用你

Imagery: 终生不成器
Scene: 大树老死在森林里
Mapping: 没有对手=没有成就

## 五、甲木格局意象库

Pattern: ⭐建禄格（寅月）
Core_Imagery: 在自己地盘上的大树——地利人和
THE_HIT_Seed: 你有天然的舞台——问题是你上不上去
BLIND_SPOT_Seed: 你以为你要等待机会。实际机会一直在，是你在犹豫

Pattern: ⭐阳刃格（卯月）
Core_Imagery: 茂盛过头需要修剪的森林
THE_HIT_Seed: 你不缺力量——你缺一把斧头
BLIND_SPOT_Seed: 你以为你需要更多滋养。实际你需要被挑战

Pattern: 阳刃驾杀
Core_Imagery: ⭐ 大树被精准劈成栋梁
THE_HIT_Seed: 你的力量终于有了对手——威权显赫
BLIND_SPOT_Seed: 你以为你讨厌对手。实际没有对手你会腐烂

Pattern: 七杀格（申月）
Core_Imagery: 秋天被劈的大树——成器
THE_HIT_Seed: 你的对手不是伤害你的——是成就你的
BLIND_SPOT_Seed: 你以为你在被攻击。实际你在被塑造

Pattern: 正官格（酉月）
Core_Imagery: 秋末被精细修剪的大树
THE_HIT_Seed: 规则不是限制你——是让你变精
BLIND_SPOT_Seed: 你以为你天生要反叛。实际你天生适合有规矩的环境

Pattern: 财格（辰/未/戌/丑月）
Core_Imagery: 扎根在土地的大树
THE_HIT_Seed: 你的钱来自"扎根"，不是"飘浮"
BLIND_SPOT_Seed: 你以为你要灵活。实际你需要深扎

Pattern: 偏印格（亥月）
Core_Imagery: 长生月的大树——表面凋零地下生长
THE_HIT_Seed: 你在表面休息但实际在长生
BLIND_SPOT_Seed: 你以为你停滞了。实际你在积蓄

Pattern: 正印格（子月）
Core_Imagery: 被雨露滋养的大树
THE_HIT_Seed: 你需要细而持续的滋养——不是大河
BLIND_SPOT_Seed: 你以为你需要更多。实际你需要更精

Pattern: ⭐食神格（巳月）
Core_Imagery: 向阳生长的大树
THE_HIT_Seed: 你的创造力是自然流动的——不用逼自己
BLIND_SPOT_Seed: 你以为你要更努力。实际你要更放松

Pattern: ⭐伤官格（午月）
Core_Imagery: **木火通明**——燃烧的大树
THE_HIT_Seed: 你最美的状态是燃烧自己
BLIND_SPOT_Seed: 你以为燃烧是消耗。实际燃烧是你的存在方式

Pattern: ⭐曲直格
Core_Imagery: 一整片森林——纯粹无杂
THE_HIT_Seed: 你最强的状态是做纯粹的自己
BLIND_SPOT_Seed: 你以为"平衡"是智慧。实际对你来说纯粹才是最优

Pattern: 天元一气（特殊配置）
Core_Imagery: ⭐ 四棵甲辰/甲戌大树——极致纯粹
THE_HIT_Seed: 你是极少数的"纯粹形态"——用这个去做一件大事
BLIND_SPOT_Seed: 干支雅称，非独立格局。古籍多以历史人物命例引用，实战罕见

## 六、甲木专属古典名言映射

古籍名言: "甲木参天，脱胎要火"
现代CIPHER解读: 你天生向上，但需要火才能"脱胎"——转化为有用的东西

古籍名言: "春不容金"
现代CIPHER解读: 春天你不怕金——生命力正盛

古籍名言: "秋不容土"
现代CIPHER解读: 秋天你不被土困——已经成材

古籍名言: "火炽乘龙，水宕骑虎"
现代CIPHER解读: 火太多坐辰（水库）；水太多坐寅（火土）=你懂得调节

古籍名言: "地润天和，植立千古"
现代CIPHER解读: 湿度温度刚好=你能长期稳定

古籍名言: "甲木若无根，全赖申子辰"
现代CIPHER解读: 没根的时候，水能救你

古籍名言: "藤萝系甲，可春可秋"
现代CIPHER解读: 乙木（劫财）像藤蔓一样帮你——一年四季都可

古籍名言: "木火通明"
现代CIPHER解读: ⭐ 你燃烧时最美

古籍名言: "寒木向阳"
现代CIPHER解读: ⭐ 寒冷的你需要阳光

古籍名言: "水泛木浮死无棺木"
现代CIPHER解读: 🚫 改写：水太多没有土镇定=你被资源淹没失去方向

古籍名言: "木化成灰必死"
现代CIPHER解读: 🚫 改写：过度燃烧会消耗根基=需要降温

古籍名言: "能赢甲兄，输于乙妹"
现代CIPHER解读: ⭐ 庚金视角：打得过硬木（甲），被软藤（乙）缠住

## 七、甲木+用神组合的经典叙事

### 用神是丁火（伤官）—— 最美
- 场景：大树在燃烧，照亮整片森林
- 叙事：你最美的状态是"输出"。创造、表达、燃烧。不是保存——是释放。
- 对象：艺术家、创作者、老师、意见领袖

### 用神是庚金（七杀）—— 最刚
- 场景：大树被劈成栋梁
- 叙事：你的对手不是你的敌人——是雕塑家。你需要一个配得上你的"斧头"。
- 对象：企业家、改革者、硬核技术人员

### 用神是壬水（偏印）—— 最智
- 场景：大树被大河灌溉
- 叙事：你的根部在吸收源源不断的资源——但水太多会浮，需要戊土堤防。
- 对象：学者、研究者、策略家

### 用神是丙火（食神）—— 最向阳
- 场景：大树向着太阳生长
- 叙事：你天生是向光的——找到你的"太阳"比任何事都重要。
- 对象：品牌经营者、布道者、正能量人物

### 用神是戊己土（财）—— 最扎根
- 场景：大树在山岗/田园扎根
- 叙事：你和钱的关系是"扎根"——不是投机，是深耕。
- 对象：实业家、开发商、长期价值投资人

## 八、产品安全过滤（已查通用表）

本文件已按奇的第一条执行提示，遇敏感词直接查表：

AncientTerm: 水泛木浮死无棺木
Rewrite: 此配置能量四散，需土堤防
TableEntry: 基础过滤表

AncientTerm: 木化成灰必死
Rewrite: 过度燃烧会消耗根基，需要降温
TableEntry: 基础过滤表

AncientTerm: 克子刑妻
Rewrite: 此配置压力过大，需甲木疏通
TableEntry: 基础过滤表

AncientTerm: 非贫即夭
Rewrite: 此配置需要特定环境才能发挥
TableEntry: 基础过滤表

AncientTerm: 残疾
Rewrite: 健康方向需要特别留意
TableEntry: 基础过滤表

AncientTerm: 僧道
Rewrite: 独处型创作路径
TableEntry: 基础过滤表

AncientTerm: 奸雄枭险
Rewrite: 配置复杂，需精确分辨心性与手段
TableEntry: ⚠️ 待新增条目

⚠️ 新增候补条目（建议奇审核加入通用表）：
- "奸雄枭险/言清行浊/笑里藏刀"→ 此配置下心性与表达之间有张力，需精确分辨

## 九、与其他日主的意象对偶

### 庚金视角 × 甲木视角

Scenario: 庚金劈甲
庚金的意象: 挥斧成型
甲木的意象: 被劈成器

Scenario: 甲木遇庚
庚金的意象: 斧头来了
甲木的意象: 对手来了

Scenario: 木火通明
庚金的意象: 见不到
甲木的意象: ⭐ 我燃烧

Scenario: 金水相涵
庚金的意象: ⭐ 我最美
甲木的意象: 见不到

**引擎应用：** 甲木用户见到庚金透干时，可以反向引用庚金文案中的"斧头意象"——但要反转视角（从"挥斧"变成"被劈"）。

### 辛金视角 × 甲木视角

Scenario: 辛金雕甲
辛金的意象: 精细雕刻
甲木的意象: 被精细加工

Scenario: 甲木遇辛
辛金的意象: 小刀来了
甲木的意象: 规则来了

### 壬水视角 × 甲木视角

Scenario: 壬水生甲
壬水的意象: 灌溉大树
甲木的意象: 被灌溉生长

Scenario: 水泛木浮
壬水的意象: 洪水太大
甲木的意象: ⭐ 被淹没
