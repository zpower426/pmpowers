<div align="center">

# 💎 Pmpowers: 实战派产品经理 AI 协作框架

**为 AI 代理注入精英级产品经理 DNA**

[![GitHub Stars](https://img.shields.io/github/stars/zpower426/pmpowers?style=for-the-badge&logo=github&color=FFD700)](https://github.com/zpower426/pmpowers/stargazers)
[![License](https://img.shields.io/badge/License-MIT-orange.svg?style=for-the-badge)](./LICENSE)
[![Platforms](https://img.shields.io/badge/Platforms-Claude%20%7C%20Cursor%20%7C%20Gemini-blue?style=for-the-badge)](https://github.com/zpower426/pmpowers)
[![Engine](https://img.shields.io/badge/Engine-Superpowers-FF69B4?style=for-the-badge)](https://github.com/obra/superpowers)

**简体中文** | [English](./README.md)

---

**Pmpowers** 是一款专为产品经理（PM）深度定制的跨平台 AI 协作流程引擎。它不仅是你的“文档助手”，更是你的“首席产品顾问”。通过将顶级 PM 的决策逻辑内嵌到自动化工作流中，它让 AI 代理真正具备了专业的产品思考能力。

> **拒绝盲目迭代，让每一行需求都源于证据。**

</div>

---

## 📢 最新动态 (News)

- **[2026-03-31]** 🚀 **Pmpowers v1.0 正式发布！** 包含 30+ 专业 PM 技能，支持多平台协作。
- **[2026-03-31]** 🌐 完成全量英文文档翻译，实现中英文双语支持。

---

## 🧭 快速导航

- [📖 什么是 Pmpowers？](#-什么是-pmpowers)
- [📦 项目概览](#-项目概览)
- [⚡️ 技能加载机制](#️-技能加载机制)
- [🚀 快速上手](#-快速上手)
- [🛠 核心工作流](#-核心工作流)
- [🧰 技能宇宙](#-技能宇宙)
- [🧱 架构与致谢](#-架构与致谢)
- [🗺 路线图](#-路线图)
- [🤝 贡献](#-贡献)

---

## 📖 什么是 Pmpowers？

传统的 AI 代理往往在没有质疑底层假设的情况下直接开始写代码或 PRD。**Pmpowers** 通过注入“验证优先”的基因来解决这个问题：

*   **⚡️ 深度启发 (Socratic Inquiry)**：AI 启动 `brainstorming` 流程，通过苏格拉底式提问挖掘用户痛点的深层逻辑。
*   **🛠 规格驱动 (Spec-Driven Design)**：确保需求规格在进入研发前通过 360 度逻辑审查。
*   **🛡 验证守卫 (Validation Guard)**：倡导 **VDD (Validation-Driven Design)** —— 在定义功能前，先定义验证指标。
*   **🧩 原生智能 (Native Intelligence)**：AI 自动感知上下文并激活相关 PM 技能，无需手动输入繁琐指令。

---

## 📦 项目概览

```text
.
├── agents/             # 角色定义 (战略家、研究员)
├── commands/           # 高层产品意图指令
├── docs/pmpowers/      # 生成的 Specs、调研日志及实验记录
├── hooks/              # 会话启动与校验钩子
├── skills/             # 30+ 模块化 PM 专业技能
│   ├── using-pmpowers/ # 框架核心引导与编排逻辑
│   └── ...             # 专项技能 (TDD、市场调研等)
├── GEMINI.md           # 技能加载入口与规则注入
└── README.md           # 说明文档
```

---

## ⚡️ 技能加载机制

Pmpowers 采用 **“引导加载 + 自动编排”** 模型：

1.  **引导加载 (Bootloader)**：当 AI 进入项目时，它会读取 `GEMINI.md`，通过 `@` 导入机制注入 `using-pmpowers` 核心技能。
2.  **工具映射 (Tool Mapping)**：框架将不同平台的特定工具（如 Gemini CLI 或 Claude Code）映射到统一的接口。
3.  **自动编排 (Autonomous Orchestration)**：`using-pmpowers` 技能为 AI 植入“肌肉记忆”，强制其在响应任何用户指令**之前**，先扫描 `skills/` 目录并激活相关技能。

---

## 🚀 快速上手

### 📦 安装指南

<details>
<summary><b>选项 1: Gemini CLI (推荐)</b></summary>

```bash
gemini extensions install https://github.com/zpower426/pmpowers.git
```
</details>

<details>
<summary><b>选项 2: Claude Code</b></summary>

```bash
/plugin install pmpowers@pmpowers-marketplace
```
</details>

<details>
<summary><b>选项 3: Cursor</b></summary>

在 Agent 聊天框中输入 `/add-plugin pmpowers` 或在插件市场搜索 "pmpowers"。
</details>

### ✅ 验证安装

开启新会话并尝试说：*"我有一个关于智能看板的想法"*。观察 AI 是否自动触发 `brainstorming` 或 `customer-discovery` 技能。

---

## 🛠 核心工作流

1.  **发现 (Discovery)** 🔍：激活 `customer-discovery`，穿透噪音，识别真实痛点。
2.  **地图 (Mapping)** 🗺：使用 `opportunity-mapping` 将混乱的想法结构化为清晰的机会地图。
3.  **验证 (Validation)** 🛡：激活 `lean-experimentation`，以最低成本设计 MVP 验证方案。
4.  **定义 (Definition)** 📐：使用 `spec-driven-design` 实现文档即逻辑，自动进行一致性校验。
5.  **对齐 (Alignment)** 🎯：通过 `product-vision-strategy` 和 `north-star-metric` 锚定长期价值。

---

## 🧰 技能宇宙 (Skill Universe)

Pmpowers 预装了覆盖产品全生命周期的 30+ 自动化技能：

| 类别 | 核心技能 |
| :--- | :--- |
| **战略** 🎯 | `product-vision-strategy`, `north-star-metric`, `market-research`, `business-acumen`, `gtm-launch-management` |
| **发现** 🔍 | `customer-discovery`, `user-interviewing`, `lean-experimentation`, `opportunity-mapping`, `data-analysis`, `customer-empathy` |
| **设计** 📐 | `product-definition`, `spec-driven-design`, `ux-design-awareness`, `validation-guard`, `prototyping`, `technical-acumen` |
| **执行** ⚙️ | `prioritization`, `roadmapping`, `agile-scrum-mastery`, `writing-plans`, `project-management`, `qa-quality-mindset`, `outcome-ownership` |
| **协作** 🤝 | `stakeholder-management`, `negotiation-conflict-resolution`, `presentation-storytelling`, `written-communication`, `cross-functional-collaboration`, `problem-solving` |

---

## 🧱 架构与致谢

Pmpowers 站在巨人的肩膀上：

1.  **[Superpowers](https://github.com/obra/superpowers)** (骨架): 提供强大的自动化引擎与跨平台技能激活机制。
2.  **[PM Skills](https://github.com/product-on-purpose/pm-skills)** (灵魂): 提供深厚的产品经理专业知识库与逻辑框架。

---

## 🗺 路线图 (Roadmap)

| 功能特性 | 状态 | 描述 |
| :--- | :--- | :--- |
| **核心 30+ 技能** | ✅ 已完成 | 初始发布的专业 PM 技能集。 |
| **跨平台支持** | ✅ 已完成 | 支持 Gemini, Claude Code, 以及 Cursor。 |
| **动态规格校验** | 🏗 进行中 | 自动化的 PRD 逻辑一致性分析。 |
| **市场数据 MCP** | 📅 计划中 | 与外部市场调研数据源的集成。 |

---

## 📈 Star 趋势 (Star History)

[![Star History Chart](https://api.star-history.com/svg?repos=zpower426/pmpowers&type=Date)](https://star-history.com/#zpower426/pmpowers&Date)

---

## 🤝 贡献者 (Contributors)

感谢所有为 Pmpowers 做出贡献的小伙伴！

<a href="https://github.com/zpower426/pmpowers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zpower426/pmpowers" />
</a>

---

## 📜 协议 (License)

本项目遵循 [MIT License](LICENSE)。

<div align="center">
  Built with ❤️ for Product Managers worldwide.
</div>
