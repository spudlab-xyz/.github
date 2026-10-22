# Release policy

This policy is the organization-wide baseline. A repository may adopt stricter
controls and must document any different versioning or support model.

## Versioning and compatibility

- Use semantic versioning for versioned software: patch for compatible fixes, minor
  for compatible features, and major for incompatible changes.
- Clearly identify pre-release versions. Do not imply production support for an
  experimental release.
- Document deprecations before removal when practical, including replacement and
  migration guidance.

## Release readiness

A release candidate must have:

- an identified release owner and version or release identifier;
- passing required CI and risk-appropriate testing;
- independent review required by repository policy;
- security review for material security impact;
- updated user documentation, migration guidance, and release notes;
- reviewed dependency and licensing changes; and
- a rollback, disablement, or recovery plan appropriate to impact.

The Lead Maintainer authorizes the release after required reviewers report readiness.
Release authors must not substitute self-approval for a required independent review.

## Publishing

1. Build from a reviewed commit on the protected release branch or tag.
2. Prefer automated, reproducible publishing with least-privilege credentials.
3. Publish release notes describing changes, compatibility, upgrade actions, known
   issues, and security information safe for public disclosure.
4. Record the source commit, checks, artifacts, and publication result without
   credentials or sensitive logs.
5. Verify the published version and primary installation or upgrade path.

## Urgent fixes and rollback

Expedited releases may shorten normal timing but do not waive authorization,
credential safety, or risk-appropriate verification. If validation fails or impact is
unacceptable, stop distribution and use the documented rollback or recovery path.
Communicate user impact and next steps through the project's normal channels.

## Security releases

Coordinate security fixes privately until disclosure is approved. Public notes must
balance actionable upgrade guidance with the need to avoid premature exploitation
details. Follow the affected repository's security policy and disclosure process.
