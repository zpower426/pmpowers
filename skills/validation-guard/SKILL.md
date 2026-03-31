---
name: validation-guard
description: "As a product quality guard, perform rigorous logical verification and risk assessment on product decisions, designs, and specifications."
---

# Validation Guard: Product Quality Guard Procedures

Mimic unit testing in R&D to perform automated verification of product logic.

## Checklist

1. **Desirability Check** — Is research evidence from `docs/pmpowers/discovery/` referenced?
2. **Viability Check** — Does this solution directly support the North Star Metric?
3. **Feasibility Check** — Do current team resources allow for this? Are there major technical obstacles?
4. **Usability Check** — Is the user path clear? Are exception handlings defined?

## Logical Audit Standards

- **Logical Closure**: Do all User Stories have corresponding Acceptance Criteria (AC)?
- **Edge Case Coverage**: Are extreme cases (Edge Cases) defined?
- **Resource Waste**: Is there over-design for the sake of features?

## Output Report

The guard must output a clear "Audit Report":
- **Status**: Pass / Fail
- **Risks**: Identified potential risk points.
- **Action**: Recommended improvement measures.
