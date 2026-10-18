# TM3 当前交接

更新日期：2026-10-18

## 课程定位

课程：`Technische Mechanik III - Dynamik`。资料位于 `ws/tm3/`，当前讲义来自 B. Schweizer / Institut für Angewandte Dynamik。

用户已通过 TM1 且自评基础尚可；TM2（Elastostatik/Festigkeitslehre）尚未通过。TM3 主要依赖 TM1 的 Freischnitt、力矩、向量基础和数学，不需要为了开始 TM3 先补完整门 TM2。

## 课程结构

1. `Kinematik der Punktmasse`
2. `Kinematik des starren Körpers`
3. `Kinetik der Punktmasse`
4. `Kinetik von Punktmassensystemen`
5. `Kinetik des starren Körpers (räumlich)`
6. `Kinetik des starren Körpers (eben)`
7. `Analytische Mechanik`
8. `Einführung in die Schwingungslehre`

## 当前讲义进度

已完整读取 `vl/Kapitel_0_Einführung_2026.pdf`。本章主要是 TM1 回顾和符号统一：

- Kinematik、Dynamik、Statik、Kinetik 的区别；
- 力的作用、描述量和分类；
- innere/äußere/eingeprägte Kräfte、Reaktionskräfte、Trägheitskräfte；
- d'Alembert 惯性力 `F_T = -m a`；
- `freies Moment M = F a`；
- `Moment einer Kraft M_O = r_OA × F`；
- 力平移与 `Versatzmoment`。

结论：Kapitel 0 几乎没有进入正式 TM3 计算。它通常不作为完整定义大题，但 Freischnitt、力矩和参考点选择贯穿后续考试。当前只需确认能独立画简单受力图、判断力矩正负、计算 `r × F` 并理解力平移时必须补力矩。

`vl/Kapitel_1_Kinematik_der_Punktmasse_2026.pdf` 已提取正文并进行基础教学，未逐页视觉精读；截至 2026-10-18 主要公式含义和应用已完成第一轮讲解。最新入口见本文末尾更新及 `notes/Kapitel1-基础与易错点.md`。

## 考试资料与题型判断

已完整检查：

- 11 份 2015-02 至 2020-02 的正式试卷/带手写答案扫描；
- 7 份 WiSe 2021/22 至 2025 的 Gedächtnisprotokoll、草图和解题笔记。

三份 WiSe 2024/25 资料属于同一时期考试的不同记录版本，不能视为三次独立考试；`Notes_250224_011112 (1).pdf` 不是完整试卷。

高频考试主线：

1. `Schwerpunktsatz + Drallsatz + Freischnitt`；
2. `Lagrange-Gleichungen 2. Art / Prinzip von d'Alembert-Lagrange`；
3. `Relativmechanik`，包括 Führungs、Relativ、Coriolis 项；
4. `Kreisel`；
5. `Schwingungen`；
6. `Arbeitssatz / Energieerhaltungssatz`；
7. 滚动、绳长与几何约束。

旧卷与近年题高度类似：方法、小问顺序和核心模块稳定，具体机械装置、几何参数和数字会变化。2015-2020 多为四道长综合题；2023 和 WiSe 2024/25 更接近五模块结构：Schwerpunkt-/Drallsatz、Relativmechanik、Kreisel、Lagrange、Schwingungen。旧卷仍适合当前复习。

## 当前掌握状态

- Kapitel 0：内容理解，用户认为 TM1 基础尚可；尚未无提示验证，不能标记为稳定掌握。
- Kapitel 1：截至 2026-10-18，主要公式分量含义及应用完成第一轮讲解；G1-3 在给公式与分步引导下完成。用户理解坐标方向与合成思路，但积分幂次、phi 与 phi_dot 曾混淆，不能标记整章独立掌握。无需以未讲推导为由延后章节收尾。
- 历年题型：资料归类和题型地图已完成，尚未开始逐题训练。
- 第一周主线：Kapitel 1 已完成第一轮讲解和一题引导应用，不需提前攻克复杂旧卷；用户当前先转 TT。

## 下一步

1. 用户已要求暂时放下 TM3；恢复时从 `notes/Kapitel1-基础与易错点.md` 的 2026-10-18 更新继续，不重复从基础圆周代入题开始。
2. 先用短题复测一次积分幂次/系数与 phi/phi_dot；再选 UE1 未做代表题，或按用户要求进入 Kapitel 2。非恒定 a(v) 仅讲含义及公式应用规则，尚未做完整代表变式；不默认要求公式推导。
3. 如有需要，用两三道无提示短题验证 Kapitel 0 的 Freischnitt 和力矩基础；通过后再标记为掌握。
4. 等待 2026/27 正式 Klausurhinweise，以确认最终题数、时长和模块分值。


## 2026-10-16 考试信息核查

- 再次完整读取 Downloads 提供的 16 页 Kapitel_0_Einführung_2026.pdf，与已归档文件逐字节一致，无需重复归档。
- 本讲义未列考试日期、时长、报名截止；本学期考试时间仍未确认。
- 对话截图仅显示 SoSe26，2026-09-03 15:30–17:30、120 分钟和需自印 Moodle 公式表，未显示课程名，不能作为 TM3 或 WiSe26/27 考试安排。
- 掌握状态未变化，下一步仍为 Kapitel 1 和当学期考试公告。

## 2026-10-16 新资料归档

- 新增 `vl/Kapitel_2_Kinematik_des_starren_Körpers_2026.pdf`（83 页），从 Downloads 复制并通过 SHA256 校验，原文件保留；仅核对首页，尚未学习。
- 归档初期仅提取 Kapitel 1 正文并核对目录；后续已开展教学，当前掌握状态以上方和下方最新进度为准。
- 已建立 `ue/` 作为本课练习资料目录；Kapitel 2 属于讲义，存入 `vl/`。
- 下一步继续 Kapitel 1 尚未完成部分，再进入 Kapitel 2。

## 2026-10-16 公式表与教学进度更新

- 用户明确确认 TM3 考试允许带公式表；提供 `TM3_Formelsammlung_Klausur_2026_09.pdf`（13 页扫描 PDF），已从 Downloads 复制到本课程根目录并经 SHA256 校验，原件保留。文件名为 2026-09 版，本学期是否需更新版本仍以当学期公告为准。
- 用户明确要求以后出题均带所需公式；当前优先按公式表训练理解、选用和代入，覆盖此前默认不给公式的练习方式。
- 已视觉核对封面：B. Schweizer / FB16 / Institut für Angewandte Dynamik，明确为 TM III - Dynamik 的 SoSe 2026、2026-09-03 15:30–17:30 公式表。此前不明课程截图中的日期现在可与 TM3 对应，但仍不是 WiSe 2026/27 的考试日期。封面规定页张含封面装订、不得添加笔记/补充/标记、随试卷收回；当前学期版本要求待公告。
- 已进行 Kapitel 1 教学：固定直角坐标 r/v/a 求导、速度向量与速率、圆周运动切向与法向分量、角速度与角加速度、旋转单位基底及平面极坐标速度。
- 已能独立完成简单分量求导；速率根式化简曾出错；切向/法向分量与总加速度、alpha/a、角速度/角加速度仍曾反复混淆，尚不能标记稳定掌握。
- 用户对过多符号、中途更换记号和过度重复题敏感；统一用 a_t、a_n 讲圆周运动，需要时才说明 a_phi、a_r 的对应和符号；新符号先解释，题目明确正方向，机械计算可代算。
- 上述速度题已完成：v_phi=4 m/s，合速率为 5 m/s；其后完成极坐标加速度代入和三类运动学积分练习。

## 历史入口（2026-10-16 23:06，后续进度见下）

- 最新记录：`handoff/sessions/2026-10-16-2306-第一章基础训练收尾.md`；长期知识与错误检查动作：`notes/Kapitel1-基础与易错点.md`。
- 用户进一步明确：题目只出现提供的公式表中已有的公式，保留表内符号。dot/double-dot 的含义可中文解释，不额外列公式表没有的公式。表 1.3 用 phi_dot、phi_ddot；表 1.5 给三类积分。
- 最后题：r=2、r_dot=1、r_ddot=0、phi_dot=3、phi_ddot=0，给公式后用户得 a_r=0-2*9=-18；a_phi=6 为下一步本可计算，但未在该收尾题作答，不补记成用户完成。
- 三类积分：独立选对 a(x) 所用式；a(x)=3x、x0=0、v0=2、x=2 时算得 v²=4+2*6=16，v=4 由助手代算；a(v)=-2 的减速题算对 t=2 s、x=8 m。大部分题已给公式或积分式，不计无提示完全掌握。
- 重要纠错：此前称“第一章可以收尾”过早，已明确更正为尚余曲率半径、旋转基底推导、三维例题及更代表性的积分变式。下次不用再从基础圆周同类代入题开始。

## 最新入口：2026-10-18 21:48（Europe/Berlin）

- 本次记录：`handoff/sessions/2026-10-18-2148-第一章应用与G1-3收尾.md`。长期知识：`notes/Kapitel1-基础与易错点.md`。
- 已讲清 rho 与 r、速率与速度向量、旋转单位基底的直观意义、径向/周向/轨迹切向区别、柱坐标 z 分量、课件第 30 页螺旋线及第 31/33 页轨迹坐标；a(v) 作为已知条件，不通过积分公式反求 a(v)。用户不要求额外推导，因此第一章讲解可收尾；这与此前“未讲完”的判断依据不同，不代表未验证内容已掌握。
- 新归档 `ue/TM3_Uebung_1_ML_VG.pdf`（35 页）与 `ue/TM3_Uebung_2_ML_VG.pdf`（38 页），从 Downloads 复制并校验 SHA256，原件保留；两份标 WS25/26。本次 UE1 用于 G1-3；UE2 只做题型检查，第二章尚未教学。
- G1-3 在引导下完成：v(0)≈1.98 m/s；a(0)≈6.18 m/s²；h(0.5)=0.35 m；phi(0.5)=pi/4=45°。r=0.5 m 固定；phi_dot(0)=pi，phi_ddot=-2pi；z_dot(0)=1.2，z_ddot=-2。机械计算和多数结果由助手给出，不计独立完成。
- 用户正确判断 r 恒定、写出径向加速度 -0.5*pi²、第一次积分 z_dot=1.2-2t；第二次积分误写“1.2t2-t4”，已纠正 z=1.2t-t²。phi(0)=0 曾被当作周向速度为零的依据，已区别 phi 与 phi_dot。
- 用户要求全科图示优先课件/原题原图；必要时生成清晰补图，不用字符画。公式附表内内容、保持符号，只解释分量与应用；新知识先讲再练，已理解简单概念加快推进。
- 本次未确认新的考试安排。用户暂时切换 TT，TM3 不继续追加刷题；恢复入口见上方“下一步”。
