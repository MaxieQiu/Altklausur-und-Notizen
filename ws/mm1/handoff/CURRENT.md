# MM1 当前交接

更新日期：2026-10-22

## 课程与资料

- Maschinenelemente und Mechatronik I，WiSe 2026/27，Prof. Dr. Debora Clever。
- 已归档并完整读取 vl/MM1_Kap.0_Einführung.pdf（47 页）、vl/MMI_Kap.1_Moderne-Lehre.pdf（20 页）；关键框图已视觉核对，Downloads 原件保留。

## 课程与考试

- 笔试 120 分钟、120 分，40%（48 分）及格；日期尚未确认。
- 机械部件与储能 30 分、Aktorik 30 分、Sensorik 10 分、控制与调节 20 分、系统理解与建模 30 分。
- 课件为考试重点，Skript 辅助；导论列出不可编程计算器。
- 9 次 Hörsaalübung、5 次 Rechnerübung，练习自愿但知识与考试相关。电脑练习通过 4/5 可在考试通过后获得一档 Bonus。
- 分班报名：2026-10-19 10:00 至 10-30 23:59，Bonus 要求登记；10-19 HÜ1 介绍 Live Script。
- 用户明确 Bonus 不重要：优先通过和必需任务，不把取得 Bonus 设为必做目标。

## Kapitel 1 知识与掌握状态

- 五大组成：Grundsystem、Aktorik、Sensorik、Steuerung/Prozessrechner、Mensch-Maschine-Schnittstelle。
- 从手动变速器到 AMT，理解传感、控制、执行的配合；补偿式电子秤作为反馈实例。
- 执行器：Energiesteller 调节供能；Energiewandler 改变能量种类；Energieumformer 在同类能量中改变参数（例如齿轮传动）。
- 已讲解章节重点，尚未无提示验证，不能记为独立掌握。完整数学建模尚未展开，尚无旧卷支持具体题型频率。

## 下一步

- 先复测五大组成、执行器三环节、电子秤反馈原理，再读取 Kapitel 2。
- 核对本学期笔试日期；无需优先追求练习 Bonus。

## 2026-10-16 本次复核与下一步

- 重读导论中的MATLAB/Simulink、选组和日程页，确认19日是报名开放日。
- MM1使用 MATLAB/Simulink。选组10-19 10:00至10-30 23:59，19日HÜ1介绍Live Script；没有确认19日前的硬性截止任务。练习Bonus优先级低，仍需基础建模知识。知识掌握状态未变化。
- 下一步：核对当学期软件/练习要求和考试日期；复测五大组成、执行器环节与反馈，再进下一章。
- 本次记录：`handoff/sessions/2026-10-16-2306-MATLAB与选组提醒.md`。


## 2026-10-19 今日收尾

第一章即时练习已进行，但不是稳定独立掌握；补偿秤反馈量误答质量，纠正为位置后未复测。新部件德语先解释，可中文作答。两份考试 PDF 已归档；2018 Rinderknecht，当前 Clever，2026回忆无署名。核心题型延续但不可推定每年难度。详见 `notes/Kapitel1与试卷对照.md`。Moodle打不开，Kapitel2未取得；下次短测反馈量，再随新课件推进，不反复刷简单分类。

最新记录：`handoff/sessions/2026-10-19-2053-第一章复测与试卷对照.md`。

## 2026-10-21 最新状态：第二章建模资料阅读

本节为当前优先入口；上文相冲突的“尚未取得/读取”及下一步安排为历史状态，以本节为准。

- Kapitel 2 Systemmodellierung（147页）：理论/实验建模，V-SMS流程：实际系统→Ersatzmodell→平衡/运动DGL→Blockschaltbild→模拟与验证。
- 机械平动/转动的弹簧、阻尼和惯性，刚度串并联、折算质量/惯量；电路R/L/C及Kirchhoff规则；液压容抗/阻抗/惯性。
- Potentialgröße×Flussgröße=Leistung的跨领域类比；一/二自由度系统，摩擦与Stribeck曲线，PID初步；被动/主动座椅、提升系统等综合模型。
- 这是 ohne Antworten 的留白版；空白框为原件内容，后续补出的方程须标明是教学推导。9次Hörsaalübung/5次Rechnerübung自愿；4/5电脑练习用于考试通过后的Bonus，不是考试准入。

### 资料与实际学习状态

- `vl/MMI_Kap.2_Systemmodellierung IRM ohne Antworten V1.pdf`（147页）。

助手已读第二章正文并抽查关键框图；未展开第二章教学，第一章掌握度仍沿用10-19记录，补偿秤反馈量Position尚需复测。

长期阅读索引：`notes/2026-10-21-本周讲义阅读索引.md`。

三天计划按课程分组，每组两门：第一组 PFM → TT；第二组 TM3 → TdF；第三组 MM1 → SRT。用户明确因 Physik 有待交作业而优先 PFM。2026-10-21 因 Moodle 再次无法打开而收工，三组学习均未开始；恢复后从第一组继续，不自动按日历跳至下一组。

### 下一步与风险

第三组先MM1再SRT，围绕共同建模/DGL/框图内容衔接学习，避免重复。先短测补偿秤反馈量，新部件德语先解释，可先中文作答。

本次会话记录：`handoff/sessions/2026-10-21-1801-第二章建模资料阅读.md`。


## 2026-10-22 最新入口：19日选组事项复核

用户询问此前说的19日开始事项；根据本课程交接与10-16记录回答：MM1分组选组10-19 10:00开放、10-30 23:59截止，10-19 HÜ1介绍MATLAB Live Script。沿用此前公告，未在线更新确认。练习自愿，电脑练习4/5通过可在考试通过后给Bonus，不是考试准入。未报名、未新教学，掌握度不变。

关键文件：本课程 CURRENT、10-16 MATLAB与选组提醒session、10-19第一章复测session、第二章阅读索引；未新读PDF。

下一步：有需要时在Moodle确认选组及实际状态；知识继续按此前入口短测补偿秤反馈量Position，再进入Kapitel2。

最新记录：handoff/sessions/2026-10-22-2019-19日选组事项复核.md。
