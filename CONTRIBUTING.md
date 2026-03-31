# Contributing to Pmpowers

感谢你为 **Pmpowers** 贡献专业 PM 技能！我们致力于构建全球最严谨的产品管理 AI 工作站。

## 技能贡献标准

为了保持与 `superpowers` 同等的工程质量，每一个新增技能必须满足：

### 1. 结构化目录
- 路径: `skills/[skill-name]/SKILL.md`
- 辅助脚本 (如有): `skills/[skill-name]/scripts/`

### 2. 高密度 SKILL.md 内容
每一个 `SKILL.md` 必须包含：
- **Intent (意图)**: 明确技能解决的具体 PM 问题。
- **Hard Gates (硬门禁)**: 强制性的前置或后置校验逻辑。
- **Checklist (任务清单)**: 原子化的执行步骤。
- **Visual Process (流程图)**: 使用 Mermaid 或 Dot 描述逻辑。
- **Anti-Patterns (反模式)**: 明确指出在该领域 PM 容易犯的错误。
- **ABC Principles**: 解释方案背后的底层产品逻辑。

## 提交 PR 流程
1. Fork 本仓库。
2. 创建你的技能分支。
3. 确保你的 `SKILL.md` 逻辑严密且无模糊描述。
4. 提交 PR 并附带一个简单的测试用例或 Spec 示例。

## 开源协议
你的贡献将基于 [MIT License](LICENSE) 授权。
