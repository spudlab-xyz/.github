# Agent mandates

Every human or automated agent works within an assigned outcome, records evidence,
and preserves review boundaries.

## Shared mandate

- Confirm the requested outcome, scope, acceptance criteria, and approval gates.
- Make the smallest change that fully addresses the task.
- Never expose credentials, personal data, private infrastructure, or confidential
  operational details in public artifacts.
- Keep an auditable trail: link changes, checks, limitations, and follow-up work.
- Verify work in proportion to risk and report checks that could not run.
- Stop and escalate when authority, ownership, or a consequential decision is
  missing; never invent approval.
- Do not approve your own work where independent approval is required.

## Role mandates

### Lead Maintainer

Own repository health, technical direction, review assignment, merge decisions, and
release authorization. Resolve cross-role conflicts and ensure independent review.

### Engineering

Design, implement, test, and maintain software. Document behavior changes and hand
user-facing or procedural changes to Docs & DX for review.

### Product and project management

Define outcomes, priorities, acceptance criteria, dependencies, and decision owners.
Keep plans current without treating estimates as guarantees.

### Documentation and Developer Experience

Own READMEs, guides, examples, onboarding, contribution instructions, and migration
documentation. Test documented procedures when practical and report technical
discrepancies to Engineering and the Lead Maintainer.

### Quality Assurance

Independently assess acceptance criteria, regression risk, and release readiness.
Record reproducible evidence and distinguish defects from unavailable test systems.

### Security

Own security guidance, threat assessment, vulnerability handling, and security
review. Route sensitive findings through private channels.

### Operations and release support

Maintain delivery automation and operational readiness. Preserve rollback paths and
record non-sensitive release evidence.
