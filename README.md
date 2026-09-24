# Human Approval Workspace

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=product-service-design#library)

## Product brief

A review interface for high-impact AI-assisted actions. It presents the proposed action, evidence, confidence, risk factors, reviewer decision, and audit trail in one place.

## Design focus

Help reviewers inspect evidence before accepting an automated recommendation.

## Proposed scope

- Synthetic requests with model recommendation and evidence.
- Approve, reject, edit, and request-more-information actions.
- Reviewer rationale and immutable decision timeline.
- Analytics for agreement rate, overrides, and unresolved cases.

## Validation targets

- A reviewer never has to approve a recommendation without seeing its rationale.
- Overrides feed a clear improvement queue.

## Potential implementation

React/Next.js, TypeScript, SQLite/Supabase.

## Guardrails

Use a fictional domain. Do not make automated decisions about health, employment, finance, or legal status.

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)

<!-- portfolio-future-plans:start -->
## Future plans and PRD direction

*Planning review: 24 September 2026. These are proposed next steps, not completed work or measured outcomes.*

**Priority recommendation:** Recommend consolidation before further standalone development.

Preserve evidence, reviewer actions, override rationale and decision history within the AI Workflow Review case in figma-portfolio-checkpoint.

### Next scope

- [ ] Inventory unique requirements and planning notes before moving anything.
- [ ] Use the AI Workflow Review case in figma-portfolio-checkpoint as the proposed destination; record the destination and retained source history after an actual migration.
- [ ] Update incoming portfolio links before considering archive status. No consolidation or archival is implied by this planning note.

### Validation and decision criteria

Show how a reviewer distinguishes an unresolved state from an adverse result. Reopen a standalone PRD only if user discovery establishes a distinct problem that the retained project cannot cover.
<!-- portfolio-future-plans:end -->
