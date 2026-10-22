# Generic issue intake handoff

This repository contains the canonical generic issue forms and pull request template for Spudlab repositories that do not provide local overrides.

GitHub community files are inherited from the public organization `.github` repository only when the destination repository does not contain the corresponding local file. A valid local issue form or `.github/ISSUE_TEMPLATE/config.yml` replaces the inherited issue-template set rather than merging with it. A local pull request template similarly takes precedence.

The bug and feature forms require exact `bug`, `enhancement`, and `needs-triage` labels in every destination repository. The preserved support-question form additionally requires `question`. `LABELS.yml` records the full issue-form label union. Reconcile missing names without deleting unrelated labels or changing existing label color and description unless normalization is separately approved.

Support and security chooser links point to this repository's verified `SUPPORT.md` and `SECURITY.md`. The security document records the current absence of a verified private intake route and must not be represented as providing one.

## Verification

- Parse every YAML file and confirm each form has unique input IDs and non-empty `name`, `description`, and `body` fields.
- Confirm the issue-form label union matches `LABELS.yml`.
- Verify support and security links resolve from the default branch.
- Verify inherited behavior in a public and private pilot without local templates.
- Verify a harmless local issue-template override replaces, rather than merges with, inherited templates.
- Record observed URLs and timestamps; file presence alone is not inheritance evidence.

Policy provenance for SPU-34: `spudlab-xyz/operations` commit `d3547f112ef5dc41d14f05cd7a47222a762d23fe`; loaded `AGENTS.md`, `docs/proposed-authority-policy.md`, `docs/runbooks/README.md`, `docs/runbooks/contribution.md`, and `docs/runbooks/testing.md` on 2026-10-22 UTC by the Engineering Agent.
