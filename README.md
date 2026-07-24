# Network Change Control Platform

The **Network Change Control Platform (NCCP)** is a governance-first, vendor-neutral control plane for enterprise network changes.

NCCP owns intent, policy, approval, evidence, audit, reconciliation, and closure. Execution engines remain replaceable implementation details.

## Canonical lifecycle

```text
Intent → Validation → Policy → Render → Review Artifact → Git Branch → Approval
→ Execution Authorization → Apply → Verification → Evidence → Reconciliation → Closure
```

> Governance is the product. Automation is replaceable.

## Start here

- [Executive Summary](docs/00-executive-summary.md)
- [Product Vision](docs/01-product-vision.md)
- [Architecture](docs/02-architecture/README.md)
- [Architectural Tenets](docs/02-architecture/02-architectural-tenets.md)
- [Domain Model](docs/03-domain-model/README.md)
- [Contracts](docs/04-contracts/README.md)
- [ADRs](adr/README.md)

## Status

Architecture and documentation foundation. Implementation begins after core boundaries, contracts, workflows, and security decisions are reviewed.
