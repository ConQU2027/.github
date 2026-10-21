<!-- ================================================================
     ConQU2027 — ROBOCON 2027 参赛队 · 组织简介
     赛事官网：https://www.robocon.org.cn/sys-index/
     原有图片链接保持不变
     ================================================================ -->

<div align="center">
<a href="https://github.com/ConQU2027">
  <img src="https://github.com/ConQU2027/.github/blob/main/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20261021164108_286_17.png" height="100" alt="ConQU2027 Logo">
</a>

# ConQU2027

**ROBOCON 2027 · “女娲补天” 参赛队**

[![ROBOCON 2027](https://img.shields.io/badge/ROBOCON-2027%20%E5%A5%B3%E5%A8%B2%E8%A1%A5%E5%A4%A9-red?style=for-the-badge)](https://www.robocon.org.cn/sys-index/)
[![Official Rules](https://img.shields.io/badge/Official-Rulebook%20v1.1-blue?style=for-the-badge)](https://www.robocon.org.cn/sys-nd/129.html)
[![Team Repo](https://img.shields.io/badge/Team-ConQU2027-181717?style=for-the-badge&logo=github)](https://github.com/ConQU2027)

</div>

---

## 📖 关于我们

**ConQU2027 是征战 ROBOCON 2027 赛季的参赛队伍。** ROBOCON（全国大学生机器人大赛）是中国最具影响力的综合性大学生机器人竞赛之一，自 2002 年在中国首次举办，冠军队代表中国参加 ABU ROBOCON[reference:0]。2027 赛季的主题是 **“女娲补天”** ，参赛队需要设计并制作两台机器人——**TR（搬运机器人）** 与 **BR（建筑机器人）** ——协同完成规则设定的高难度任务[reference:1]。

我们的仓库是这一赛季从规则分析、机械设计、电控制作到赛场调试的**全部技术产出与协作记录**。

> 🔗 **官方赛事入口**：[robocon.org.cn/sys-index](https://www.robocon.org.cn/sys-index/)　·　**2027 规则书**：[Rulebook v@]([https://www.robocon.org.cn/sys-nd/129.html](https://github.com/ConQU2027/.github/blob/main/%E7%AC%AC%E4%BA%8C%E5%8D%81%E5%85%AD%E5%B1%8A%E5%85%A8%E5%9B%BD%E5%A4%A7%E5%AD%A6%E7%94%9F%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%A4%A7%E8%B5%9B%E5%A5%B3%E5%A8%B2%E8%A1%A5%E5%A4%A9%E7%AB%9E%E6%8A%80%E8%B5%9B%E8%A7%84%E5%88%99V2(1).pdf))

---

## 🎯 2027 赛季焦点

| 维度 | 内容 |
|:--|:--|
| **赛季主题** | 女娲补天 |
| **核心机器人** | **TR（搬运机器人）** · **BR（建筑机器人）** |
| **技术重心** | 机械结构设计、运动控制、多机协同、任务策略 |
| **备赛周期** | 通常约十个月的设计、制作与迭代 |

---

## 📦 仓库导览

<!-- 按“赛季流程”重组，比按语言分类更贴合参赛队的使用场景 -->

| 类别 | 仓库 / 目录 | 说明 |
|:--|:--|:--|
| **📐 机械设计** | `mechanical/` | TR / BR 的结构模型、传动方案、强度校核、BOM |
| **⚡ 电控与嵌入式** | `electronics/` | 主控、驱动、传感器、电源、通信 |
| **🧠 算法与策略** | `algorithms/` | 定位、路径规划、协同任务调度、视觉辅助 |
| **🖥️ 上位机与工具** | `tools/` | 调试工具、数据记录、仿真脚本、标定程序 |
| **📄 文档与规则** | `docs/` | 赛季规则解读、会议纪要、测试报告、复盘 |
| **🧪 测试与验证** | `tests/` | 单元测试、场地测试数据、回归用例 |

> 如果某个方向暂时独立为单独仓库，请把上表的 `目录` 替换为该仓库的超链接。

---

## 🌈 参与与协作

- **队内成员**：按 [CONTRIBUTING.md](https://github.com/ConQU2027/.github/blob/main/CONTRIBUTING.md)（待创建）的分支规范提交；每个赛季开始前在本 README 更新一次**分工矩阵**。
- **赛队外部同学 / 开源社区**：欢迎通过 Issue 提问、提交 PR，或在 [Discussions](https://github.com/orgs/ConQU2027/discussions) 交流规则理解与技术方案。
- **规则相关问题**：优先查阅 [官方规则问答](https://www.robocon.org.cn/) 与规则书原文，再在队内讨论。

---

## 📚 资源速查

| 资源 | 链接 |
|:--|:--|
| **ROBOCON 官方赛事页（你提供的入口）** | [robocon.org.cn/sys-index](https://www.robocon.org.cn/sys-index/) |
| **2027 官方规则书 v1-1** | [robocon.org.cn/sys-nd/129.html](https://www.robocon.org.cn/sys-nd/129.html) |
| **本队组织主页** | [github.com/ConQU2027](https://github.com/ConQU2027) |
| **本队仓库索引** | [.github 仓库](https://github.com/ConQU2027/.github/tree/main) |

---

## 🍿 一点队内传统

- 调试到凌晨时，最常出现的对话是：“是机械的问题还是电控的问题？”——**答案通常是“都有”。**
- 赛季初期每个人都觉得自己能提前一个月完工；赛季末期每个人都学会了微笑接受“再改一版”。
- **早餐标配**：比赛日靠咖啡和能量棒撑过第一场排位。

---

<div align="center">
  <sub>

  **ConQU2027** · ROBOCON 2027 赛季 · [官方赛事](https://www.robocon.org.cn/sys-index/) · [GitHub 组织](https://github.com/ConQU2027)

  </sub>
</div>
