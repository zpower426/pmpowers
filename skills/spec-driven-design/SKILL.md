---
name: spec-driven-design
description: "Write Product Specifications (Specs) that are highly logically rigorous, testable, and business-relevant."
---

# Spec-Driven Design: Advanced Product Logic Definition Guide

Documentation is the product logic contract. It is not a description of features, but a rigorous definition of the system's behavioral boundaries.

## Checklist

1. **Context, Metrics & Evidence** — Clearly link to Opportunity Map nodes, research evidence sources, and the North Star Metric this Spec is expected to impact.
2. **User Stories & Value** — Use the standard format: "As a [Role], I want to [Do Something], so that [Value is Gained]."
3. **Acceptance Criteria (AC)** — Every User Story must have clear, verifiable "Done" criteria; strictly forbid vague language.
4. **Functional Logic & State Machines** — Describe core business processes. For complex interactions, use State Transition Diagrams or Sequence Diagrams.
5. **Exception & Edge Case Handling** — Exhaustively define behavior logic for non-happy paths (e.g., network interruption, illegal input, missing permissions).
6. **Logic Self-Review & Provenance** — Reference `validation-guard` for consistency scans.

## Core Mandates: Clarity and Rigor

### 1. Eliminate Ambiguity
- **Anti-Pattern**: "The system should be responsive" or "Provide a smooth experience." (❌)
- **Best Practice**: "The system must respond to requests within 200ms" or "When the user clicks A, the system must display B on the current page and disable button C." (✅)

### 2. Modular Definition
- A Spec should describe a logically complete unit.
- If a feature involves multiple subsystems, define the interaction protocols in an overall Spec first, then detail internal logic in sub-Specs.

### 3. Testability
- Every Acceptance Criterion should be directly translatable into a test case. If it cannot be tested, the definition is not clear.

## Specification Document Structure Template

```markdown
# Spec: [Feature Name]
- **Date**: YYYY-MM-DD
- **Related Metric**: [Metric Name]
- **Evidence Source**: [Link to Discovery/Experiment]

## 1. Goal & Scope
[Briefly describe what problem is being solved]

## 2. User Stories & Acceptance Criteria (AC)
### [Story 1]
- **As a** ... **I want to** ... **So that** ...
- **AC 1**: ...
- **AC 2**: ...

## 3. Business Logic
[Flowcharts, state machines, detailed rules]

## 4. Edge Cases
[List possible exceptions and their handling methods]
```

## Delivery Standards
Save to `docs/pmpowers/specs/YYYY-MM-DD-<feature-name>.md`.
