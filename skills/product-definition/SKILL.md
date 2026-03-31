---
name: product-definition
description: "Translate vision into rigorous, unambiguous product logic documents (PRD/User Stories), providing an accurate execution benchmark for R&D and design."
---

# Product Definition: Rigorous Product Definition Guide

Definition is the "source code" for R&D.

## Checklist

1. **Set Goals and Non-goals (Scope)** — Clarify "what to do" and "what not to do" for this feature.
2. **Write User Stories** — As a... I want to... So that...
3. **Detail Acceptance Criteria (AC)** — Every functional point must be testable.
4. **Organize Core Business Logic** — Use state machines, sequence diagrams, or data dictionaries.
5. **Define Performance and Non-functional Requirements** — Response time, concurrency support, and data consistency.

## Expert Principles

- **Document as Contract**: Do not let R&D write a single line of code until the definition is complete.
- **Edge Case Coverage**: A senior PM should spend 80% of their time handling the 20% of abnormal scenarios outside the Happy Path.
- **Falsifiability**: If you cannot provide a criterion for "failure," the definition is not clear.

## Delivery Standards
Deliverables must be saved under `docs/pmpowers/specs/`.
