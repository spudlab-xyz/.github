# Spudlab organisation defaults

This public `.github` repository contains Spudlab's organisation profile, shared community guidance and maintainership documentation.

## Repository structure

| Path | Purpose |
| --- | --- |
| [`profile/README.md`](profile/README.md) | Public organisation profile shown on Spudlab's GitHub Overview page. |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Default contribution guidance. |
| `CODE_OF_CONDUCT.md` | Default community conduct policy; publication is awaiting an approved private reporting contact. |
| `SECURITY.md` | Default security reporting policy; publication is awaiting an approved private fallback contact. |
| [`SUPPORT.md`](SUPPORT.md) | Default support guidance. |
| [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) | Default pull request template. |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) | Default issue forms and template chooser configuration. |
| [`GOVERNANCE.md`](GOVERNANCE.md) | Current organisation decision-making model. |
| [`docs/`](docs/) | Scientific, licensing, branding and repository setup guidance. |

## What GitHub applies automatically

For repositories in the `spudlab-xyz` organisation that do not define their own equivalent, GitHub can use this repository's contribution, conduct, security and support files, issue templates, issue-template configuration and pull request template as defaults once the relevant file is present on the default branch. The conduct and security defaults are intentionally withheld until their private reporting routes are approved.

A repository's local community file takes precedence. If a repository has its own valid `.github/ISSUE_TEMPLATE` configuration or templates, GitHub uses that local template set rather than combining individual forms with this one.

The organisation profile is loaded specifically from `profile/README.md`. The root `README.md`, `GOVERNANCE.md`, documents, `LICENSE`, workflows, rulesets, settings and `CODEOWNERS` are not inherited automatically. Every project must include its own licence.

See [GitHub's documentation on default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) for current behaviour.

## Maintaining these files

Keep shared guidance concise and broadly applicable to software and hardware. Put project-specific requirements in the relevant project repository. Check links and issue-form YAML before merging, and review the [new repository checklist](docs/NEW_REPOSITORY_CHECKLIST.md) when starting a project.

Changes to organisation-wide policy should be proposed publicly through an issue or pull request where practical, with the reasoning recorded. Never add private reporting details without the contact owner's approval.

## Licence

Unless a file states otherwise, this repository's covered contents are licensed under the [Apache License 2.0](LICENSE). This does not license other Spudlab repositories or third-party material. See the [licensing policy](docs/LICENSING.md).
