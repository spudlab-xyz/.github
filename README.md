# Spudlab shared organization documentation

This repository is the home for Spudlab's organization-wide, public-safe guidance,
community files, and reusable validation workflow. Private operating records and
policies are maintained separately and take precedence for internal work.

## Operating documentation

- [Organization chart](docs/operations/organization-chart.md)
- [Agent mandates](docs/operations/agent-mandates.md)
- [Project charter template](docs/operations/project-charter-template.md)
- [Contribution workflow](docs/operations/contribution-workflow.md)
- [Release policy](docs/operations/release-policy.md)

Repository-specific instructions take precedence when they are more restrictive.
Credentials, private infrastructure details, personal data, incident material, and
other sensitive operational records must remain in approved private systems—not in
this public repository.

## Reusable validation

Repositories can call [the reusable documentation and YAML validation workflow](.github/workflows/reusable-validation.yml) or start from [the workflow template](.github/workflow-templates/documentation-and-yaml.yml). Callers grant only `contents: read`; no secrets or privileged release permissions are required. Pin production callers to a reviewed full commit SHA and update that pin through normal review.
