# Validation workflow adoption

The reusable workflow validates YAML syntax and repository-local Markdown links. It is stack-neutral, receives no secrets, grants only `contents: read`, and excludes release or deployment work.

## Adopt it

1. Copy the workflow template into `.github/workflows/documentation-and-yaml.yml`.
2. Replace `REPLACE_WITH_REVIEWED_FULL_COMMIT_SHA` with the full SHA of a reviewed `.github` commit containing the reusable workflow.
3. Keep caller permissions at `contents: read`; do not pass secrets.
4. Open a pull request and record one harmless failing fixture followed by a corrected passing run in a non-sensitive validation repository.
5. Review dependency updates before advancing the pin. Never point production callers at a moving branch or tag.

Before updating a caller, record its current full SHA as the last-known-good pin. If the update must be rolled back, restore that SHA through a reviewed pull request, rerun the same validation checks, and retain the failure, rollback, and corrected-run evidence. Do not rewrite shared history to move a pin.

For repository onboarding, install local `CODEOWNERS`, Dependabot configuration, agent instructions, licensing, labels, and settings only after project-specific owners and decisions are known. Do not infer a licence. Local community files intentionally override organization defaults and should be preserved as documented exceptions.
