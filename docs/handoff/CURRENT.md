# 项目交接索引

更新日期：2026-10-14

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

### 其他已有课程

以下目录已有资料，但尚未建立课程独立 handoff。首次对这些课程开展实质性工作或执行“收工”时，应在对应课程目录中创建 `handoff/CURRENT.md` 和 `handoff/sessions/`：

- `ws/vc/`
- `ws/se/`
- `ss/math2/`
- `ss/wk2/`

## 历史兼容

`docs/handoff/sessions/` 中已提交的旧记录继续保留，不删除。TdF 的既有记录已在 `ws/TdF/handoff/sessions/` 中补建课程副本。今后的课程记录以各课程文件夹内的 handoff 为准。
