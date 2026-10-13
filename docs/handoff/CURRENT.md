# 当前项目交接

更新日期：2026-10-13

## 项目定位

本仓库用于长期保存和整理考试资料、课程讲义、历年试卷与复习笔记。复习方法以根目录的 `通用考试复习项目模板.md` 为准：先核对课程与考试范围，再按历年试卷的题型、分值和出现概率安排学习；只有无提示独立完成的内容才算掌握。

## 用户偏好

- 考题和专业术语使用德语，解释与推理使用中文。
- 新题型需要完整讲通；已学题型不提前提示，一次检查一步。
- 重视实际得分、资料匹配和个人易错点，不追求无差别覆盖整本讲义。
- 希望项目状态可通过 GitHub 在不同设备间延续，不需要在新设备重新说明工作方式。
- 简短收尾口令为“收工”。

## 当前重点课程：TdF

课程：`Technologie der Fertigungsverfahren`，资料位于 `ws/TdF/`。

已确认的基础内容：

- Fertigung 是把原始状态转化为满足指定形状和性能要求的成品状态。
- DIN 8580 六大类：Urformen、Umformen、Trennen、Fügen、Beschichten、Stoffeigenschaften ändern。
- 同一零件可以使用不同制造路线，选择时需要综合考虑材料、几何形状、产品性能、数量和成本。
- Technologie、Verfahren、Prozess 是三个不同层级的概念。

当前课堂进度：教授已进入 `Hauptgruppe 2 - Umformen`。截至该位置，讲义正式覆盖了制造工程导论、工业生产技术的三个领域、Fertigung 的定义、DIN 8580 六大类、`Urformen` 的烧结示例，以及 `Umformen` 的锻造和深拉示例；尚未进入 Umformen 的详细材料行为、摩擦学或计算。

课程组织信息来自用户提供的 `0_WS2526_Ankündigungsfolien.pdf`：

- TdF I：2026-10-13 至 2026-12-07，由 PtU / Prof. Groche 负责。
- TdF II：自 2026-12-08 开始，由 PTW / Prof. Weigold 负责。
- TdF I 与 TdF II 合并考试：2027-03-01 08:00-10:00。
- TUCan 自 2026-11-15 开放考试报名。
- 2026-11-30 和 2026-12-01 因 EMB 无课。
- 企业实践、匿名 Quiz 和 Demonstratoren 已被介绍，但公告没有明确规定为强制参加；报名成为准备小组后应履行相应准备与协助职责。

考试形式结论：TdF I 和 TdF II 分别由 PtU 与 PTW 授课，但在 2027-03-01 参加一场两小时的联合笔试。现有公告不能证明考试当天一定会发两张独立试卷；更准确的说法是一次考试包含两个课程模块。

## 考试资料判断

### `Musterlösung_Musterklausur TdF1 PtU.pdf`

- PtU 的 TdF I 模拟考试答案版，元数据显示制作于 2020 年。
- 共 17 页、4 道大题，每题 10 分，总计 40 分。
- 四个模块为：Gießen；Pulvermetallurgie und additive Fertigung；Grundlagen der Umformtechnik und Tribologie；Walzen und Schmieden。
- 适合用于确认 PtU 的题型、分值和计算要求，但不是当前 TdF I + TdF II 联合考试的完整试卷。

### `TdFGedächnisprotokoll.pdf`

- 学生整理的 SoSe 2025 考试回忆记录，不是官方试卷，内容明确声明不作保证。
- 覆盖 BWL、Sankey、铸造、相图、Chvorinov、粉末冶金、成形、轧制、深拉、涂层、切削、连接、磨削和增材制造等，明显横跨 TdF I 与 TdF II。
- 适合建立范围和查找重复主题，不能单独用于预测今年原题。

两份资料共同支持的高优先级主题：Gießen、Chvorinov、相图/元素比例、Pulvermetallurgie、Additive Fertigung、Umformen、Walzen；Schmieden 和 Tribologie 也是官方样卷中的高价值内容。

第一份 Einführung 讲义中应优先掌握 Fertigung 的定义、DIN 8580 六大类、分类逻辑、Urformen 与 Umformen 的区别及常见例子。工程师名言、工业革命细节、Darmstadtium 日期和图片来源属于低优先级背景。

## 已完成事项

- 已验证 Codex 能读取仓库中的 Markdown、TXT、URL 和 PDF。
- 已读取通用考试复习模板，并将其确认为默认复习方法。
- 已读取 TdF 第一堂课的三份导论资料和课程公告。
- 已完整检查新加入的两份考试资料，区分官方模拟考试与非官方考试回忆。
- 已根据样卷和回忆记录初步确定高频考试模块。
- 已建立项目级持久指令与跨设备交接机制。

## 下一步

- 继续读取新加入的 TdF 讲义，并把每个章节映射到模拟考试与 SoSe 2025 回忆记录中的题型。
- 当前学习阶段优先掌握第一堂课的 Fertigung 定义和 DIN 8580 分类，不提前学习尚未正式讲到的复杂计算。
- 获得更多历年试卷或 2026-12-07 的正式 Klausurhinweise 后，建立最终 TdF 考试地图和按分值排序的复习计划。
- 在每次工作结束时使用“收工”更新本文件并安全同步。
