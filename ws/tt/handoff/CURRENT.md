# Technische Thermodynamik 当前交接

更新日期：2026-10-14

## 课程与考试定位

- 课程：`Technische Thermodynamik I`（6 CP）
- 教师：Prof. Dr.-Ing. Peter Stephan
- 资料目录：`ws/tt/`
- 讲义目录：`ws/tt/vl/`
- 当前讲义：`ws/tt/vl/TTD1_V1_2026.pdf`
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

- 用户已大致理解 System、Umgebung、Zustand 和 Prozess 的含义。
- 能在无提示下把 `p,T,V` 归为 Zustandsgrößen，把 `Q,L` 归为 Prozessgrößen。
- 已理解系统不“储存” Wärme 或 Arbeit；二者是在过程中穿过系统边界的能量传递。
- 仍需强化：
  - 区分 Wärme 与 Arbeit；此前将活塞压缩误判为 Wärme；
  - 根据系统边界判断质量是否穿过；此前将储罐充气误判为无质量传递；
  - 区分 `starr` 与 `adiabatisch/wärmeisoliert`：前者给出 `V = konstant`，后者给出 `Q = 0`。
- 当前掌握等级：基础概念为“引导可做”，尚不能评价为稳定独立掌握。

## 全科通用学习规则

- 题目、提问和模拟考试现场表述使用德语。
- 解题思路、概念解释、推理和纠错使用中文。
- 重要术语首次出现使用“德语（中文）”双语形式，后续以德语为主。
- 该规则已写入根目录 `通用考试复习项目模板.md`，适用于所有课程。

## 未完成事项与下一步入口

1. TT 下次继续时，先用一道综合判断题检查 `geschlossen/offen`、`starr`、`adiabatisch` 以及 Masse/Wärme/Arbeit 是否穿过系统边界。
2. 用户当前要切换至下一门课程；在用户指定课程后，读取对应课程的 handoff 和最近 session。
3. `Vorlesung 2` 已归档；下次 TT 先复测上述基础，再从系统分类和 `Zustandsgrößen und Prozessgrößen` 继续。

## 2026-10-16 Vorlesung 2 归档

- 新增 `vl/TTD1_V2_2026.pdf`（34 页），从 Downloads 复制并经 SHA256 校验，原件保留。
- 已提取全篇正文、视觉核对第 6 页目录；公式文本提取较差，正式讲解公式前须视觉核对相关页。尚未完整逐页视觉核验或开展第二讲教学。
- 内容：V1 回顾、系统分类、Stoff/Phase、intensive/extensive/spezifische/molare Zustandsgrößen、状态方程与偏导/全微分、状态量路径无关性、机械/热平衡、Nullter Hauptsatz 和温标。末页仅预告 V3 的第一定律。
- 用户确认当前提供的 PPT 基本对应第一周已开课内容；本轮按难到易巩固，先 TM3，再回 TT。第二讲掌握状态为未学。

本次收尾记录：`handoff/sessions/2026-10-16-2306-第二讲归档与复习安排.md`。
