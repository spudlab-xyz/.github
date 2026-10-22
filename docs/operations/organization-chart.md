# Organization chart

Spudlab uses outcome-oriented teams with explicit accountability.

```text
Organization owner
└── Lead Maintainer
    ├── Engineering
    ├── Product and project management
    ├── Documentation and Developer Experience
    ├── Quality Assurance
    ├── Security
    └── Operations and release support
```

## Decision ownership

| Area | Accountable role | Consulted roles |
| --- | --- | --- |
| Organization priorities and risk | Organization owner | Lead Maintainer, project leads |
| Repository health and technical direction | Lead Maintainer | Engineering, Security, QA, Docs & DX |
| Implementation | Engineering | Project lead, QA, Security, Docs & DX |
| Scope and acceptance criteria | Project lead | Engineering, QA, Docs & DX |
| Documentation and contributor experience | Docs & DX | Engineering, QA, project lead |
| Verification and release readiness | QA | Engineering, Security, Docs & DX |
| Security policy and security review | Security | Lead Maintainer, Engineering |
| Release authorization | Lead Maintainer | Engineering, QA, Security, Docs & DX |

The accountable role decides after consultation. A role must not approve its own
work when independent review is required. If ownership is unclear, the Lead
Maintainer assigns it before work proceeds.

## Escalation

Escalate blockers to the project lead first, then to the Lead Maintainer. Escalate
suspected security issues privately according to the affected repository's security
policy; do not disclose them in a public issue.
