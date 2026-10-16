# 项目交接索引

更新日期：2026-10-16

## 使用方式

本文件只保存项目级索引和跨课程规则，不再用某一门课程的状态覆盖其他课程。

开始课程任务时：

1. 读取根目录 `通用考试复习项目模板.md`；
2. 读取本索引；
3. 识别当前课程目录；
4. 读取该课程的 `handoff/CURRENT.md` 和最近相关 session。

执行“收工”时，应根据本次对话和实际文件识别涉及的课程，只更新对应课程的 handoff；若涉及多门课程，分别记录。

## 跨课程用户偏好

- 题目、提问和模拟考试现场表述使用德语；解题思路、概念解释、推理与纠错使用中文。
- 重要考试术语首次出现使用“德语（中文）”双语形式，后续以德语为主；该规则适用于所有课程。
- 新题型需要完整讲通；已学题型不提前提示，一次检查一步。
- 只有无提示独立完成的内容才算掌握。
- 重视实际得分、资料匹配和个人易错点，不追求无差别覆盖整本讲义。
- 希望通过 GitHub 在不同设备间延续课程状态。
- 简短收尾口令为“收工”。
- 所有课程的练习资料统一归入各自的 `ue/` 文件夹；讲义继续放在 `vl/`。原 12 门课程及新增 SRT 均已建立 `ue/`，空目录以 `.gitkeep` 保留；目录数不等于本学期选课数。
- 用户明确 Bonus 不重要：以通过、必需考核与行程安排为先；自愿 Bonus 任务降低优先级。
- 每门课程的对话进度和交接状态必须存入该课程自己的文件夹，不能因切换课程而覆盖上一门课程。
- 用户确认本次提供的 PPT 基本对应第一周已开课课程；当前计划课程若未提供 PPT，则先视为尚未开课，不因已有旧卷就提前展开整门课。希望按难到易、一次一个重点学习。
- 2026-10-16 用户新要求：以后出题均附上所需公式，当前 TM3 尤其参照用户提供的考试公式表。此要求优先于此前默认“已学题不给公式”的练习方式；应区分“给公式后能应用”和“无提示独立掌握”。
- 用户进一步要求：不列其公式表中没有的公式，保持表内符号；新符号先解释，避免中途换记号；简单计算可代算，不反复刷同类题。

## 全项目课程规划资料

- 模块手册：`docs/studienplanung/MHB_Bachelor_MB_SE_40.pdf`（Stand: 01.09.2026，125 页，已从 Desktop 复制并校验）。
- 第五学期提前修读评估：`docs/studienplanung/第五学期提前修读评估.md`。已核对手册第 52–59 页；用户暂定选择 SRT，已建目录，尚未确认 TUCaN 报名；GdD/WK3 尚未决定推迟。
- 若 GdD/WK3 均推迟，当前七门课从 36 CP 降为 30 CP；无需为凑学分自动加课。SRT 推荐数学与力学基础，WuSt 推荐热力学基础；推荐先修不等于必须先通过。

## 课程索引

### SRT

- 课程：Systemtheorie und Regelungstechnik，`16-23-5010`，6 CP。
- 目录：`ws/srt/`；最新状态：`ws/srt/handoff/CURRENT.md`；历史记录：`ws/srt/handoff/sessions/`。
- 用户暂定报名，尚未确认 TUCaN 课程/考试报名；已建立 `vl/`、`ue/`。当前主线为 740 页的 2026 版试卷集（2020–2026，14 场及配套答案），另保留 288 页旧集作补充，两集去重共 26 场；教学未开始。
- 最新试卷分析：`ws/srt/2026版试卷集分析.md`。自 2022-08 起为 120 分钟四大题，数字控制并入其他题；2026-09 总分 109，理解题约 24%。
- 手册确认冬季开课、120 分钟笔试，推荐数学/微分方程和工程力学基础；下一步读取当学期导论、习题和考核公告，核对十二月任务及考试时间。

### TT

- 课程：`Technische Thermodynamik`
- 目录：`ws/tt/`
- 最新状态：`ws/tt/handoff/CURRENT.md`
- 历史记录：`ws/tt/handoff/sessions/`
- 当前资料：保留 2015_F-2024_H 共 20 份试卷，已完整读取 `vl/TTD1_V1_2026.pdf`。
- 已确认：考试三大题结构长期稳定；新卷主要增加流程复杂度，核心仍为 1./2. Hauptsatz、理想气体、真实工质/两相区和 Exergie。
- 当前进度：完成 Vorlesung 1 的 System、Systemgrenze、Zustand、Prozess、Zustandsgröße 与 Prozessgröße；基础概念为“引导可做”。
- 下一步：下次回到 TT 时先复测 `geschlossen/offen`、`starr`、`adiabatisch` 和 Masse/Wärme/Arbeit，再进入已归档的 `vl/TTD1_V2_2026.pdf`（34 页，尚未教学）。

### TM3

- 目录：`ws/tm3/`
- 最新状态：`ws/tm3/handoff/CURRENT.md`
- 历史记录：`ws/tm3/handoff/sessions/`
- 最近工作：Kapitel 1 已完成基础求导、圆周/极坐标速度加速度与三类积分训练；多为给公式后会应用，第一章未完整结束，第二章未学。
- 最新入口：`ws/tm3/notes/Kapitel1-基础与易错点.md`；下次先讲曲率半径 rho 与距离 r 的区别，再做三维例题。已归档考试公式表（SoSe 2026 版，非本学期考试日期）。

### TdF

- 目录：`ws/TdF/`
- 最新状态：`ws/TdF/handoff/CURRENT.md`
- 历史记录：`ws/TdF/handoff/sessions/`
- 最近工作：已整理第一课、课程公告、官方模拟卷和 SoSe 2025 考试回忆；下一步随课堂读取新讲义。

### PFM

- 课程：`Physik für den Maschinenbau`
- 目录：`ws/pfm/`
- 最新状态：`ws/pfm/handoff/CURRENT.md`
- 历史记录：`ws/pfm/handoff/sessions/`
- 当前资料：已读取 `vl/Kapitel 00.pdf`、`vl/Kapitel 01_1_2.pdf`、2022 正式 Nachklausur 和 WiSe 2024/25 回忆卷；`Physik single coice fragen.pdf` 尚未系统读取。
- 已确认：WiSe 2026/27，Prof. Dr. Thorsten Kröll；考试暂定 2027-03-09 09:30–11:30，以 TUCaN 为准；通过线 50%，习题可在通过后改善成绩。
- 考试结论：两份试卷的电容器、E/B 场、电磁感应、干涉/衍射、透镜和光电效应高度重复；难点是广度与时间压力，单题数学一般。
- 当前进度：完成课程初始化、第一节知识课和初步试卷比较，尚未进行无提示测验；下一步读取选择题资料并建立固定题型模板。

### MM1

- 课程：`Maschinenelemente und Mechatronik 1`（依据 PDF 标题元数据）。
- 目录：`ws/mm1/`
- 最新状态：`ws/mm1/handoff/CURRENT.md`
- 历史记录：`ws/mm1/handoff/sessions/`
- 已完整读取 Kapitel 0、1；MM1 120 分钟、120 分，40% 及格，日期未知。
- 当前进度：整理五大组成、反馈框图与执行器三环节，尚未无提示验证。
- 下一步：复测 Kapitel 1，再进 Kapitel 2；Bonus 为低优先级。

### Grundlagen der Digitalisierung

- 课程：`Grundlagen der Digitalisierung`（依据 PDF 标题元数据）；目录简称暂用 `gdd`。
- 目录：`ws/gdd/`
- 最新状态：`ws/gdd/handoff/CURRENT.md`
- 历史记录：`ws/gdd/handoff/sessions/`
- 当前资料：`vl/00_VirtuelleVorbereitung.pdf`，已从 Downloads 复制，原文件保留。
- 已完整读取准备讲义：项目考核与代码问答，未列传统期末笔试。
- 风险：12-11 至 12-18 PACP 与用户离德行程冲突，远程或改期未获确认。
- 下一步：联系课程组确认安排，10-22 17:00 前选习题组、10-31 前考试报名，完成 MATLAB Onramp。

### WK3

- 课程：Werkstoffkunde III；目录 `ws/wk3/`。
- 最新状态：`ws/wk3/handoff/CURRENT.md`；历史记录：`ws/wk3/handoff/sessions/`。
- 已完整读取并归档第一周 Kunststoffe；尚未无提示验证。
- 下一步：10-21 09:30 至 10-28 23:59 选实验组，每组最多五人；先检查日期是否避开用户十二月离德期间。笔试时间未知。

### Math 2

- 目录 `ss/math2/`；最新状态 `ss/math2/handoff/CURRENT.md`，历史记录 `ss/math2/handoff/sessions/`。
- 已以 3.3 通过；题型驱动复习方法已总结在通用模板，无逐题得分明细。

### 其他已有课程

以下目录已有资料，但尚未建立课程独立 handoff。首次对这些课程开展实质性工作或执行“收工”时，应在对应课程目录中创建 `handoff/CURRENT.md` 和 `handoff/sessions/`：

- `ws/vc/`
- `ws/se/`
- `ss/wk2/`

## 历史兼容

`docs/handoff/sessions/` 中已提交的旧记录继续保留，不删除。TdF 的既有记录已在 `ws/TdF/handoff/sessions/` 中补建课程副本。今后的课程记录以各课程文件夹内的 handoff 为准。

## 本次跨课程安排核对（2026-10-16）

- 本次项目级历史：`docs/handoff/sessions/2026-10-16-2306-课程规划与资料结构收尾.md`；八门涉及课程分别在自己的 `handoff/sessions/` 新建本次记录，不用项目记录覆盖课程状态。
- 原七门36 CP；加入暂定SRT共42 CP；若GdD/WK3均推迟，加SRT后为36 CP。未确认实际TUCaN注册，TM2是否补考未决定。
- 下周已有MechCenter Studienberatung预约，可讨论GdD PACP与WK3实验行程风险和SRT提前修读；尚未取得替代考核批准。

- 已知笔试：TdF 2027-03-01 08:00–10:00；PFM 暂定 03-09 09:30–11:30；TT 03-19（时段未知）。日期互不重叠，但未在线核验最新公告。
- TM3、MM1、WK3 本学期笔试日期未确认，不能宣称所有考试均无冲突。
- GdD 十二月 PACP 已知行程冲突；WK3 实验组日期未知，需先查。
- 跨课程初步难度仅沿用已有资料：TM3 > TT ≳ Math 2 > PFM > TdF；MM1/GdD/WK3 尚未充分分析，不硬排。
