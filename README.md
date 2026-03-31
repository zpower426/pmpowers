<div align="center">

# 💎 Pmpowers: The Product-on-Purpose Framework

**Empowering AI Agents with Elite Product Management DNA**

[![GitHub Stars](https://img.shields.io/github/stars/zpower426/pmpowers?style=for-the-badge&logo=github&color=FFD700)](https://github.com/zpower426/pmpowers/stargazers)
[![License](https://img.shields.io/badge/License-MIT-orange.svg?style=for-the-badge)](./LICENSE)
[![Platforms](https://img.shields.io/badge/Platforms-Claude%20%7C%20Cursor%20%7C%20Gemini-blue?style=for-the-badge)](https://github.com/zpower426/pmpowers)
[![Engine](https://img.shields.io/badge/Engine-Superpowers-FF69B4?style=for-the-badge)](https://github.com/obra/superpowers)

[简体中文](./README_CN.md) | **English**

---

**Pmpowers** is a cross-platform AI collaboration engine purpose-built for Product Managers (PMs). It transforms AI agents from "document assistants" into "Chief Product Advisors" by embedding elite PM decision logic directly into their automated workflows.

> **Stop blind iterations. Make every requirement rooted in evidence.**

</div>

---

## 📢 News

- **[2026-03-31]** 🚀 **Pmpowers v1.0 Released!** Initial release with 30+ PM skills and cross-platform support.
- **[2026-03-31]** 🌐 Added full English documentation and dual-language support.

---

## 🧭 Navigation

- [📖 What is Pmpowers?](#-what-is-pmpowers)
- [📦 Project Overview](#-project-overview)
- [⚡️ Skill Loading Mechanism](#️-skill-loading-mechanism)
- [🚀 Quick Start](#-quick-start)
- [🛠 Core Workflow](#-core-workflow)
- [🧰 Skill Universe](#-skill-universe)
- [🧱 Architecture & Credits](#-architecture--credits)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)

---

## 📖 What is Pmpowers?

Traditional AI agents often jump straight into writing code or PRDs without questioning the underlying assumptions. **Pmpowers** fixes this by injecting a "Validation-First" DNA:

*   **⚡️ Socratic Inquiry**: AI initiates a `brainstorming` process using Socratic questioning to dig into deep user pain points.
*   **🛠 Spec-Driven Design**: Ensures requirements pass a 360-degree logic review before reaching engineering.
*   **🛡 Validation Guard**: Promotes **VDD (Validation-Driven Design)** — defining success metrics before defining features.
*   **🧩 Native Intelligence**: AI automatically senses context and activates relevant PM skills—no manual commands needed.

---

## 📦 Project Overview

```text
.
├── agents/             # Role definitions (Strategist, Researcher)
├── commands/           # High-level product intent commands
├── docs/pmpowers/      # Generated Specs, Discovery logs, and Experiments
├── hooks/              # Session-start and validation hooks
├── skills/             # 30+ modular PM professional skills
│   ├── using-pmpowers/ # Core framework bootloader & orchestration
│   └── ...             # Specialized skills (TDD, Market Research, etc.)
├── GEMINI.md           # Entry point for skill loading & rules
└── README.md           # This file
```

---

## ⚡️ Skill Loading Mechanism

Pmpowers operates on a **"Bootloader + Orchestration"** model:

1.  **Bootloader**: When the AI enters the project, it reads `GEMINI.md`, which uses `@` imports to inject the `using-pmpowers` core skill.
2.  **Tool Mapping**: The framework maps platform-specific tools (e.g., Gemini CLI vs. Claude Code) to a unified interface.
3.  **Autonomous Orchestration**: The `using-pmpowers` skill installs "muscle memory" in the AI, forcing it to scan the `skills/` directory and activate relevant skills **BEFORE** responding to any user prompt.

---

## 🚀 Quick Start

### 📦 Installation

<details>
<summary><b>Option 1: Gemini CLI (Recommended)</b></summary>

```bash
gemini extensions install https://github.com/zpower426/pmpowers.git
```
</details>

<details>
<summary><b>Option 2: Claude Code</b></summary>

```bash
/plugin install pmpowers@pmpowers-marketplace
```
</details>

<details>
<summary><b>Option 3: Cursor</b></summary>

Enter `/add-plugin pmpowers` in the Agent chat or search for "pmpowers" in the marketplace.
</details>

### ✅ Verify Installation

Start a new session and say: *"I have an idea for a smart dashboard."* Observe if the agent automatically triggers `brainstorming` or `customer-discovery`.

---

## 🛠 Core Workflow

1.  **Discovery** 🔍: Activate `customer-discovery` to cut through noise and identify real pain points.
2.  **Mapping** 🗺: Use `opportunity-mapping` to structure chaotic ideas into a clear Opportunity Map.
3.  **Validation** 🛡: Activate `lean-experimentation` to design MVP plans at minimal cost.
4.  **Definition** 📐: Use `spec-driven-design` for documentation as logic with automated consistency checks.
5.  **Alignment** 🎯: Anchor long-term value via `product-vision-strategy` and `north-star-metric`.

---

## 🧰 Skill Universe

Pmpowers comes pre-installed with 30+ automated skills:

| Category | Key Skills |
| :--- | :--- |
| **Strategy** 🎯 | `product-vision-strategy`, `north-star-metric`, `market-research`, `business-acumen`, `gtm-launch-management` |
| **Discovery** 🔍 | `customer-discovery`, `user-interviewing`, `lean-experimentation`, `opportunity-mapping`, `data-analysis`, `customer-empathy` |
| **Design** 📐 | `product-definition`, `spec-driven-design`, `ux-design-awareness`, `validation-guard`, `prototyping`, `technical-acumen` |
| **Execution** ⚙️ | `prioritization`, `roadmapping`, `agile-scrum-mastery`, `writing-plans`, `project-management`, `qa-quality-mindset`, `outcome-ownership` |
| **Soft Skills** 🤝 | `stakeholder-management`, `negotiation-conflict-resolution`, `presentation-storytelling`, `written-communication`, `cross-functional-collaboration`, `problem-solving` |

---

## 🧱 Architecture & Credits

Pmpowers is built on the shoulders of giants:

1.  **[Superpowers](https://github.com/obra/superpowers)** (The Backbone): Provides the automation engine and cross-platform skill activation mechanism.
2.  **[PM Skills](https://github.com/product-on-purpose/pm-skills)** (The Soul): Provides the deep library of PM expertise and logical frameworks.

---

## 🗺 Roadmap

| Feature | Status | Description |
| :--- | :--- | :--- |
| **Core 30+ Skills** | ✅ Done | Initial set of professional PM skills. |
| **Cross-Platform Support** | ✅ Done | Support for Gemini, Claude Code, and Cursor. |
| **Dynamic Spec Verification** | 🏗 In Progress | Automated logical consistency checking for PRDs. |
| **Market Data MCP** | 📅 Planned | Integration with external market data sources. |

---

## 📈 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=zpower426/pmpowers&type=Date)](https://star-history.com/#zpower426/pmpowers&Date)

---

## 🤝 Contributors

Thanks to all the amazing people who have contributed!

<a href="https://github.com/zpower426/pmpowers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zpower426/pmpowers" />
</a>

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

<div align="center">
  Built with ❤️ for Product Managers worldwide.
</div>
