# Executive Summary

Enterprise network change is often automated without being governed. Scripts, controllers, pipelines, and vendor-specific tools can execute work, but they rarely provide a consistent control model for intent, policy, approval, evidence, verification, and closure.

NCCP addresses that gap by becoming the enterprise control plane for network change.

## Product thesis

The durable enterprise value is not device configuration generation. It is trusted change governance across heterogeneous networks and replaceable execution systems.

## Outcomes

NCCP is designed to provide:

- a single governed lifecycle for network change;
- explicit separation of intent, desired state, and execution;
- policy enforcement before authorization;
- human accountability for approvals;
- vendor-neutral change models and adapters;
- verification and evidence for every execution;
- reconciliation between intended and observed state;
- auditable integration with enterprise systems.

## Initial technology direction

- FastAPI modular monolith
- React, TypeScript, and Vite
- PostgreSQL
- Temporal
- Open Policy Agent
- Vault
- Kubernetes
- S3-compatible evidence storage
