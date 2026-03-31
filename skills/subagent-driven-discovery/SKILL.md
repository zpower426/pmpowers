---
name: subagent-driven-discovery
description: "Direct AI agents to perform large-scale data scraping, competitive analysis, and trend research. Synthesize massive amounts of raw information into actionable product opportunities."
---

# Subagent-Driven Discovery: Expert Guide to Agent-Assisted Research

As a Chief PM, you must direct AI agents as you would direct a research team. Research is not for collecting information, but for discovering differences.

## Checklist

1. **Define Research Boundary** — Clearly define the market, competitors, or user groups to be explored. Do not give "broad" instructions.
2. **Delegate Specialized Tasks** — Assign complementary tasks to different agents.
   - **Agent A (Competitive)**: Deeply deconstruct competitor core paths and value tensions.
   - **Agent B (Sentiment)**: Analyze negative reviews on the App Store/Reddit to find "opportunities."
   - **Agent C (Analytical)**: Summarize industry technical trends and policy risks.
3. **Synthesis & Cross-Check** — Compare findings from different agents to identify consensus and contradictions.
4. **Extract Opportunities** — Transform research conclusions into nodes in `opportunity-mapping`.
5. **Identify Known-Unknowns** — Clarify which conclusions still need validation through real `customer-discovery`.

## Agent Command Protocol

### 1. Structured Prompting
Do not say: "Help me research competitors." (❌)
Say: "Deconstruct the [Login/Payment] flow of [Competitor Name], list its AC (Acceptance Criteria), and the three interaction break points most complained about by users on Reddit." (✅)

### 2. Critical Synthesis
AI agents are prone to "hallucinations" or "mediocre summaries." You must require them to:
- **Search for Outliers**: "Who is doing something different in this market?"
- **Search for Conflicts**: "Why do users say they like this feature, but retention is dropping?"

## Delivery Standards
Research summary reports must be stored in `docs/pmpowers/discovery/subagent-<topic>.md`, including a clear "Opportunity Extraction" section.

## Warning
AI agents provide only "second-hand information." Any major decision based on agent research must be confirmed with L1/L2 level evidence through `lean-experimentation` or real `customer-discovery`.
