# Technische Thermodynamik 当前交接

更新日期：2026-10-22

## 课程与考试定位

- 课程：`Technische Thermodynamik I`（6 CP）
- 教师：Prof. Dr.-Ing. Peter Stephan
- 资料目录：`ws/tt/`
- 讲义目录：`ws/tt/vl/`
- 当前讲义：`ws/tt/vl/TTD1_V2_2026.pdf`（34 页）；V1/V2 主要知识完成第一轮学习，V3 尚未归档。
- 讲义标注考试日期：2027-03-19
- 考试形式：计算题，2 小时 30 分钟
- 允许材料：教研组公式表、计算器、带 ISBN 的书；不允许题集等资料。

## 历年试卷与长期结论

- 当前保留 2015_F 至 2024_H 共 20 份试卷。
- 用户明确要求删除的 2015 年以前试卷（2002-2014，共 26 份）已移入 Windows 回收站，仍可在回收站未清空时恢复。
- 对早期卷、2019-2021 卷及新增的 2021_H-2024_H 进行比较后，考试结构变化很小，约为 2-3/10。
- 试卷长期稳定为 3 道大题、总分 100 分，每题约 32-35 分：
  1. `Aufgabe 1`：非稳态封闭/开放系统、变质量、理想气体、质量/能量/熵平衡及 Exergie；
  2. `Aufgabe 2`：理想气体动力循环，Verdichter、Turbine、Wärmeübertrager、`T,s-Diagramm` 与效率；
  3. `Aufgabe 3`：真实工质和两相区，Kältemaschine、Wärmepumpe、Dampfkraftprozess、Dampfgehalt 与 Exergieverlust。
- 2023-2024 的主要变化是流程图更复杂，更多 Mischstelle、Kondensatabscheider、Regenerator 及多级压缩/膨胀；基础定律和解题方法没有换代。
- `Entropieproduktion` 与 `Exergieverlust` 已是固定重点；2024_F 出现变化比热容，2024_H 出现 `Kaskadenkältemaschine` 与最小温差，属于轻微难度提升。
- 当前做题优先级：2023_F、2023_H、2024_F、2024_H 必做；2021_H、2022_F、2022_H 用于补充装置背景；2019-2021_F 用于重复基本模板；2015-2018 仅作次级强化。

## Vorlesung 1 已完成内容

- 已完整读取 40 页 `TTD1_V1_2026.pdf`。
- 前 33 页主要是课程组织、考试规则、资料和全课程预告；真正的新知识集中在第 34-39 页。
- 已学习：
  - `mikroskopische Betrachtung（微观视角）` 与 `makroskopische Betrachtung（宏观视角）`；
  - `System（系统）`、`Umgebung（环境）`、`Systemgrenze（系统边界）`；
  - `Systemgrenze = Bilanzraumgrenze`；
  - `Zustand（状态）`、`Zustandsgröße（状态量）`、`Zustandsgleichung（状态方程）`；
  - `Prozess（过程）`、`Zustandsänderung（状态变化）`、`Prozessgröße（过程量）`；
  - 活塞压缩/加热例子的初步质量与能量平衡。
- 讲义给出的全课程主线为：Grundbegriffe、Temperatur、1. Hauptsatz、Zustandsgleichungen、2. Hauptsatz、Exergie/Anergie、Phasenwechsel、Kreisprozesse。

## 当前掌握状态

- V1/V2 主要内容完成第一轮讲解，部分概念有作答证据；不等于整章稳定独立掌握。
- 旧有证据：能把 p,T,V 归为 Zustandsgrößen，把 Q,L 归为 Prozessgrößen。
- 本次正确判断：密封容器加热是 geschlossen、nicht adiabat；给全微分式时能判断 p 恒定使第二项为零、v 恒定使第一项为零；温升 20 K 正确。
- 纠错后理解：绝热压缩无热传递但有功传入，温度仍可升高；Einstoff 与 Einphase 是两个判断，单物质可多相；机械平衡一般看受力，不能一概等同压力相等。
- 易错点：绝热压缩最初仍认为 Wärme 增大；温标综合题中 40°C 的终温答“231”，助手纠正为 313.15 K；不能记作独立换算正确。本课尚未做定律计算题。
- offene Systeme 的变质量应用、starr 与无所有形式功的区别，仍需要迁移检验。用户表示理解 intensive/extensive、spezifisch/molar、状态方程与路径无关性、平衡和温标，但多数未独立测试。

## 全科通用学习规则

- 题目、提问和模拟考试现场表述使用德语。
- 解题思路、概念解释、推理和纠错使用中文。
- 重要术语首次出现使用“德语（中文）”双语形式，后续以德语为主。
- 该规则已写入根目录 `通用考试复习项目模板.md`，适用于所有课程。
- 图示先用课件/原题图，缺适用图时再生成，不使用字符画；公式以分量含义、条件和应用为主，不主动展开推导；已理解简单概念合并推进，避免逐词确认拖慢节奏。

## 未完成事项与下一步入口

1. 不重讲整个 V2；先短测一次 Celsius/Kelvin 换算和 Wärme/Arbeit 区别，必要时补 starr/offen 的实际边界判断。
2. 下一教学主线为 V3 的 1. Hauptsatz；本次检查 `vl/` 仅有 V1/V2，V3 尚未归档，需取得讲义再按当学期材料推进。
3. 最新知识笔记：`notes/V1-V2-概念与易错点.md`；本次记录：`handoff/sessions/2026-10-18-2148-V2基础概念收尾.md`。

## 历史：2026-10-16 Vorlesung 2 归档

- 新增 `vl/TTD1_V2_2026.pdf`（34 页），从 Downloads 复制并经 SHA256 校验，原件保留。
- 已提取全篇正文、视觉核对第 6 页目录；公式文本提取较差，正式讲解公式前须视觉核对相关页。尚未完整逐页视觉核验或开展第二讲教学。
- 内容：V1 回顾、系统分类、Stoff/Phase、intensive/extensive/spezifische/molare Zustandsgrößen、状态方程与偏导/全微分、状态量路径无关性、机械/热平衡、Nullter Hauptsatz 和温标。末页仅预告 V3 的第一定律。
- 用户确认当前提供的 PPT 基本对应第一周已开课内容；本轮按难到易巩固，先 TM3，再回 TT。第二讲掌握状态为未学。

本次收尾记录：`handoff/sessions/2026-10-16-2306-第二讲归档与复习安排.md`。

## 最新更新：2026-10-18 21:48（Europe/Berlin）

- 已接上 V1 基础并讲完 V2 的主要概念：系统分类、Stoff/Phase、intensive/extensive/spezifische/molare Zustandsgrößen、t=f(p,v)、偏导固定条件/全微分、状态量路径无关性、机械/热平衡、Nullter Hauptsatz、Celsius/Kelvin。温标历史和 Fahrenheit 仅概览，未做计算训练；不默认追求历史推导。
- 本次读取 V2 相关正文并视觉核对第 7、8、13、15–18、20、23、25、26、32 页；公式以可见页面为准，不依赖乱码文本。并非完整逐页视觉验读。
- 综合题：密封刚性容器中纯液态水由 20°C 加热至 40°C，用户正确答 geschlossen、nicht adiabat，认为单相；助手补充区分 Einstoff/Einphase。Delta T=20 K 用户答对；终温由助手纠正为 313.15 K。
- 用户希望加快已懂的简单概念，优先物理含义和应用；全科配图、符号和公式教学偏好已同步项目模板。
- 2026-10-16 的“V2 未学”仅为历史状态，现已被本次进度取代。没有新确认的考试日期、时段或考试规则；沿用原有资料，未在线更新核验。

## 2026-10-21 最新状态：V3阅读与三天学习计划

本节为当前优先入口；上文相冲突的“尚未取得/读取”及下一步安排为历史状态，以本节为准。

- TTD1_V3_2026（25页）：前7页回顾V2；主体为 1. Hauptsatz、质量与总能量平衡，E=U+动能+势能，Wärme/Arbeit及物质携能。
- 本课程能量输入取正；一般平衡先看系统边界，再判断质量、热、功和动能/势能项。Volumenänderungsarbeit使用 L_V=-∫p dV；Nutzarbeit需扣除环境排挤功。
- 末页为V4预告，不能把 Wellenarbeit、Enthalpie 等后续展开计作V3已经学完。已读资料未见作业作为考试准入的明确要求，不代表已获得完整当学期准入公告。

### 资料与实际学习状态

- `vl/TTD1_V3_2026.pdf`（25页）。

V3仅助手阅读与关键平衡公式视觉抽查；用户仍为V1/V2第一轮学习状态，既有易错点和掌握证据保持不变。

长期阅读索引：`notes/2026-10-21-本周讲义阅读索引.md`。

三天计划按课程分组，每组两门：第一组 PFM → TT；第二组 TM3 → TdF；第三组 MM1 → SRT。用户明确因 Physik 有待交作业而优先 PFM。2026-10-21 因 Moodle 再次无法打开而收工，三组学习均未开始；恢复后从第一组继续，不自动按日历跳至下一组。

### 下一步与风险

位于第一组PFM之后。先短测Celsius/Kelvin和Wärme/Arbeit区别，再学习V3第一定律与边界判断；不用重新讲完整V2。

本次会话记录：`handoff/sessions/2026-10-21-1801-V3阅读与三天学习计划.md`。


## 2026-10-22 最新入口：V3第一定律与质量平衡

今天按新要求选最快推进的两门，安排 TT V3→TdF；实际仅开展 TT。第一定律、能量输入取正、体积变化功、总能量及简化、质量平衡已作初步讲解。给公式后答对200 J、500 J、300 J和6 kg；Expansion功号曾错，静止条件曾误读，经纠正后答对压缩功正、恒速动能不变。尚非稳定独立掌握；ṁ和稳态尚无作答证据。

关键文件：本课程 CURRENT、10-21 session、V3阅读索引、V1/V2易错点笔记；新增长期笔记 notes/V3-第一定律与质量平衡.md。本次未重新读取PDF正文或视觉核验公式。

下一步：从尚未回答的题继续：Ein Behälter hat einen Zulauf von 3 kg/s und einen Ablauf von 2 kg/s. Nimmt die gespeicherte Masse zu, nimmt sie ab oder bleibt sie konstant? 附 dm/dt=Σṁ_ein−Σṁ_aus，不先给答案。之后复测功符号与温标，按V3核对剩余内容；物质携能仅概念介绍、Nutzarbeit未教，不能写成V3全部完成。

最新记录：handoff/sessions/2026-10-22-2019-V3第一定律与质量平衡.md。

## 2026-10-28 暂停：V3补课与第一周练习

用户表示今天TT学完，准备切换下一门；该暂停时点不是整门课程或V3/V4全部完成。随后用户于同日明确“收工”，已授权本次安全确认内容提交推送指定origin/main。

- 归档：V3与Downloads同版不重复复制；新增vl/TTD1_V4_2026.pdf、ue/WiSe26-27_TTD1_VUe01_A.pdf、ue/WiSe26-27_TTD1_GUe01_A.pdf。公告、日历、截图未归档。官方公式表已读C:/Users/thinkbook/Downloads/formelsammlung_TTD1.pdf（3页，标注2020-10-13），尚未归档；后续按该表范围和符号给公式，额外力学/几何关系明确标注。
- V3新增教学：一般平衡源项与总质量/能量守恒；质量流率与稳态；能量总量/速率、搅拌器96%例题；三种传热公式、条件及对流代算应用；体积功p,V图、准静态、Nutzarbeit及环境功例题。未做完整覆盖收尾，V4未系统展开；焓和开放系统能量式为练习临时补充，不计V4完整教学。
- VL暂停在Nutzarbeit应用检查；恢复先核对notes/V3-V4-教学覆盖清单.md与本次记录，不把今天“学完”误记为全讲义完成。
- VUe01：Aufgabe1–3均已讨论并由助手完成机械计算。跳伞：初末动能/势能变化，用户判断开伞时机对给定初末状态的总摩擦功无影响正确；泵站：用户P正、Q负正确，询问如何选式；弹簧活塞：用户受力平衡正确，压力p曾误当内能、p1/p2与N到bar转换需澄清。结果：p2=2.273bar，ΔU≈1.936kJ。
- GUe01：Aufgabe1(a,b)、2(a,b)、3(a,b)已做；3(c)未做。用户经纠正理解活塞移动仍可封闭，正确选−∫p dV并判断环境受功为正；滑翔机正确识别动能/势能项，ΔU=0与U=0曾混淆；自行车(a)正确判断只剩内能变化、500kJ为25%故消耗2000kJ，(b)正确用25%机械功率，计算由助手处理。
- 稳态曾错：流入3kg/s流出2kg/s正确答质量增加但误判稳态；内能持续增大时误认为还需看温度。已纠正，待间隔检验。给公式/引导作答不计无提示稳定掌握。
- 用户明确纠正交互：原题有图就给原图，否则给德语原题；先解释任务和词汇，提供官方公式表相关式；不提前把整题列式计算全写完；用户负责方法/物理判断，移项、面积、积分和机械运算由助手做，单位转换完整展示。不要反复让用户回答简单移项。
- 核对2024_F/H真题第1–2页：同类第一律用于储气库、电影院冷却/送风、涡轮功率；未开始真题训练，不提高整卷掌握评价。
- 下次TT：GUe01 Aufgabe3(c)未做；或按用户要求回VL，先核对V3剩余覆盖，再系统学V4。随后已转PFM，见该课当日交接。


收工会话记录：handoff/sessions/2026-10-28-1245-V3补课与第一周练习.md。下一设备从本课最新2026-10-28节及该session继续，公式表仍在Downloads未归档。
