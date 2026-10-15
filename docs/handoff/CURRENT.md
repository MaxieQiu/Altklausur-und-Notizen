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
- 用户明确 Bonus 不重要：以通过、必需考核与行程安排为先；自愿 Bonus 任务降低优先级。
- 每门课程的对话进度和交接状态必须存入该课程自己的文件夹，不能因切换课程而覆盖上一门课程。

## 课程索引

### TT

- 课程：`Technische Thermodynamik`
- 目录：`ws/tt/`
- 最新状态：`ws/tt/handoff/CURRENT.md`
- 历史记录：`ws/tt/handoff/sessions/`
- 当前资料：保留 2015_F-2024_H 共 20 份试卷，已完整读取 `vl/TTD1_V1_2026.pdf`。
- 已确认：考试三大题结构长期稳定；新卷主要增加流程复杂度，核心仍为 1./2. Hauptsatz、理想气体、真实工质/两相区和 Exergie。
- 当前进度：完成 Vorlesung 1 的 System、Systemgrenze、Zustand、Prozess、Zustandsgröße 与 Prozessgröße；基础概念为“引导可做”。
- 下一步：下次回到 TT 时先复测 `geschlossen/offen`、`starr`、`adiabatisch` 和 Masse/Wärme/Arbeit，再进入尚未加入的 Vorlesung 2。

### TM3

- 目录：`ws/tm3/`
- 最新状态：`ws/tm3/handoff/CURRENT.md`
- 历史记录：`ws/tm3/handoff/sessions/`
- 最近工作：已检查 Kapitel 0 和历年试卷；下一步读取 Kapitel 1。

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

- 已知笔试：TdF 2027-03-01 08:00–10:00；PFM 暂定 03-09 09:30–11:30；TT 03-19（时段未知）。日期互不重叠，但未在线核验最新公告。
- TM3、MM1、WK3 本学期笔试日期未确认，不能宣称所有考试均无冲突。
- GdD 十二月 PACP 已知行程冲突；WK3 实验组日期未知，需先查。
- 跨课程初步难度仅沿用已有资料：TM3 > TT ≳ Math 2 > PFM > TdF；MM1/GdD/WK3 尚未充分分析，不硬排。
