# TM3 当前交接

更新日期：2026-10-16

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

`vl/Kapitel_1_Kinematik_der_Punktmasse_2026.pdf` 已提取正文并进行基础教学；未逐页视觉精读，第一章尚未完整结束。当前入口见下方最新进度及 `notes/Kapitel1-基础与易错点.md`。

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
- Kapitel 1：基础题已训练；给公式后能完成多数代入、分量求导和简单积分，概念与符号仍需复测，不能标记整章掌握。
- 历年题型：资料归类和题型地图已完成，尚未开始逐题训练。
- 第一周负担：暂时较轻，不需要提前攻克复杂旧卷；先完成基础确认并进入 Kapitel 1。

## 下一步

1. 从 `notes/Kapitel1-基础与易错点.md` 继续：先解释曲率半径 rho 与坐标距离 r 的区别。
2. 再完成柱坐标 z 分量和 Schraubenlinie 三维代表例题；旋转基底求导、2*r_dot*phi_dot 的来源及非恒定 a(v) 变式尚未完整展开。未结束 Kapitel 1 前不要自动跳到 Kapitel 2。
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

## 本次收尾的当前入口（2026-10-16 23:06）

- 最新记录：`handoff/sessions/2026-10-16-2306-第一章基础训练收尾.md`；长期知识与错误检查动作：`notes/Kapitel1-基础与易错点.md`。
- 用户进一步明确：题目只出现提供的公式表中已有的公式，保留表内符号。dot/double-dot 的含义可中文解释，不额外列公式表没有的公式。表 1.3 用 phi_dot、phi_ddot；表 1.5 给三类积分。
- 最后题：r=2、r_dot=1、r_ddot=0、phi_dot=3、phi_ddot=0，给公式后用户得 a_r=0-2*9=-18；a_phi=6 为下一步本可计算，但未在该收尾题作答，不补记成用户完成。
- 三类积分：独立选对 a(x) 所用式；a(x)=3x、x0=0、v0=2、x=2 时算得 v²=4+2*6=16，v=4 由助手代算；a(v)=-2 的减速题算对 t=2 s、x=8 m。大部分题已给公式或积分式，不计无提示完全掌握。
- 重要纠错：此前称“第一章可以收尾”过早，已明确更正为尚余曲率半径、旋转基底推导、三维例题及更代表性的积分变式。下次不用再从基础圆周同类代入题开始。
