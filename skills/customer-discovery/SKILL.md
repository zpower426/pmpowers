---
name: customer-discovery
description: "Understand user personas, pain point scenarios, and their underlying JTBD (Job-to-be-Done) through structured research interviews. Ensure evidence authenticity before defining any solution."
---

# Customer Discovery: Deep User Discovery and Evidence Synthesis

Reject product definitions based on assumptions. Uncover real user behavioral motivations through deep interviews and observations, and transform them into quantifiable "opportunities."

## Checklist

1. **Identify Target Segments** — Who is the person in the most pain right now? Define their characteristics, scenarios, and existing alternatives.
2. **Design Non-Leading Interview Protocols** — Use the "Past behavior predicts future behavior" principle. Write questions that focus on specific events rather than hypothetical intentions.
3. **Execute & Capture Raw Evidence** — Save raw dialogue records or key summaries to `docs/pmpowers/discovery/`.
4. **Synthesize Evidence** — Extract core pain points, unmet needs, and potential JTBDs.
5. **Sync Opportunity Map** — Connect synthesized insights to nodes in `opportunity-mapping`.

## Interview Guidance: The Mom Test Protocol

### 1. Anti-Patterns
- **Asking about Future Intent**: "If you had this feature, would you use it?" (❌) -> People will lie out of politeness.
- **Leading Bias**: "Don't you think the current process is cumbersome?" (❌) -> Guiding the user to give the answer you want.
- **Selling Solutions**: Strictly forbid mentioning your product ideas during the first 90% of the interview. (❌)

### 2. Best Practices
- **Anchor Specific Events**: "When was the last time you encountered [Problem]? Please walk me through that process." (✅)
- **Dig for Alternatives**: "How much money or time do you currently spend to solve this? What tools have you tried?" (✅)
- **Deep Dive Motivation (Five Whys)**: Ask why repeatedly until you touch on the user's emotional motivation or efficiency bottleneck. (✅)

## Core Framework: JTBD (Job-to-be-Done)

Every research output must be able to fill the following formula:
> "When I am in **[Scenario]**, I want to **[Take Some Action]**, so that I can **[Achieve Some Progress/Outcome]**."

## Delivery Standards
Interview records and synthesis reports must be stored in `docs/pmpowers/discovery/YYYY-MM-DD-<user-or-segment>.md`.
