---
name: artifact-provenance
description: "Ensure that every decision, document, and feature in the product lifecycle is transparent and traceable. Establish a complete Chain of Evidence."
---

# Artifact Provenance: Traceability and Evidence Chain Management

In rigorous product management, no requirement arises from thin air. Every word and every logical point must be traceable to its source.

## Core Mandate: The Chain of Evidence

The integrity of any Product Specification (Spec) depends on its traceability. You must be able to answer:
- **Whose pain point does this feature solve?** (Points to `docs/pmpowers/discovery/`)
- **Has this solution been validated?** (Points to `docs/pmpowers/experiments/`)
- **Which business goal does this decision support?** (Points to `north-star-metric`)

## Checklist

1. **Metadata Tagging** — Each Spec file header must include `Source`, `Status`, and `Related Metric`.
2. **Decision Audit** — Record the reasoning behind major logical changes, not just the change itself.
3. **Consistency Scan** — Verify that conclusions in the current document do not conflict with the latest research data.
4. **Cleanup Obsolete Evidence** — Mark stale research records that have been overturned by new experimental results.

## Evidence Hierarchy

| Level | Source | Reliability |
| --- | --- | --- |
| **L1 (Highest)** | Real user payment behavior, A/B test data, retention data. | Extremely High |
| **L2** | Deep user interviews (JTBD), prototype test observations, usability testing. | High |
| **L3** | Survey results, industry whitepapers, competitive analysis. | Medium |
| **L4 (Lowest)** | Stakeholder intuition, team brainstorming ideas, hypothetical reasoning. | Low |

## Expert Principles: Reject "Orphan Requirements"

- **Rule**: If a User Story cannot be traced back to L1 or L2 evidence through the chain of evidence, it must be flagged as "High Risk" in the `validation-guard` audit.
- **Version Control**: Use Git commit messages to record the context of decisions, ensuring that the choice of Solution A over B can still be understood a year later.

## Application Scenarios

- **Sprint Review**: When demonstrating features, simultaneously present the evidence chain behind them.
- **Product Refactoring**: Determine if historical logic still applies to current users by tracing back to original research.
