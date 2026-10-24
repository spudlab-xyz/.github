# New repository checklist

Use this checklist when creating a Spudlab repository. Keep requirements proportionate to the project's maturity and risk.

## Project contents

- [ ] Add a project-specific README explaining purpose, scope, setup and an honest maturity status.
- [ ] Add an explicit licence appropriate to the material in this repository.
- [ ] Document configuration, local development or assembly, and meaningful validation steps.
- [ ] Document supported versions and a release practice proportionate to the project.
- [ ] Record data provenance, provider terms, attribution, units and transformations where relevant.
- [ ] Check branding, image descriptions, colour contrast and other accessibility needs.

## Community guidance

- [ ] Review which organisation defaults are suitable for this project.
- [ ] Add project-specific contribution, conduct, support, security or pull request guidance only where an override is needed.
- [ ] Decide whether project-specific issue forms, labels or templates are needed and create any referenced labels in this repository.

GitHub can apply supported community files from the public `spudlab-xyz/.github` repository when no local equivalent exists. Local files take precedence. A local `.github/ISSUE_TEMPLATE` configuration or valid template set replaces the inherited set; GitHub does not merge selected local forms with selected inherited forms.

## Explicit repository setup

- [ ] Configure a private security reporting route. Enable GitHub private vulnerability reporting for this repository where appropriate, then verify the **Report a vulnerability** button and maintainer notifications.
- [ ] Configure repository features, permissions, branch rules or rulesets deliberately.
- [ ] Add workflows and `CODEOWNERS` only when the project needs them and their owners and maintenance are clear.
- [ ] Configure releases, packages, environments or deployment settings only when used.

Licences, governance documents, workflows, rulesets, repository settings and `CODEOWNERS` are not inherited from the organisation's `.github` repository. Private vulnerability reporting is also a per-repository setting. Verify settings in the destination repository rather than relying on files alone.
