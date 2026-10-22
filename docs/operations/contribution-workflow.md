# Contribution workflow

Repository-local instructions and branch protection rules take precedence. Ask the
maintainers when they conflict or are unclear.

## Before starting

1. Check the README, contribution guide, code of conduct, license, and security
   policy in the target repository.
2. Search existing issues and pull requests. For a substantial change, agree on the
   problem and approach with maintainers before implementation.
3. Fork or create a branch from the repository's default branch. Use a focused,
   descriptive branch name.

## Make and verify the change

1. Keep commits reviewable and avoid unrelated formatting or generated-file churn.
2. Add or update tests and documentation for changed behavior.
3. Run the repository's documented formatting, lint, test, and build checks.
4. Review the diff for secrets, personal data, debug output, and unintended files.

If a documented command fails, record the command, non-sensitive error, environment,
likely cause, and proposed next action. Never paste tokens or sensitive logs.

## Open a pull request

Include:

- the problem and approach;
- linked issue or decision context;
- verification commands and results;
- user-facing, compatibility, security, and migration impact;
- screenshots or logs only when sanitized; and
- follow-up work or known limitations.

Request review from the responsible maintainer and relevant specialist. Authors do
not approve their own changes where independent review is required. Address review
comments with code changes or a clear rationale; resolve conversations only when the
concern is handled.

## Merge and follow through

Merge only after required checks and approvals pass. Use the repository's configured
merge strategy. After merge, confirm linked work is updated and that release notes or
migration guidance are queued when needed.

Report vulnerabilities privately through the repository's security reporting path,
not through public issues or pull requests.
