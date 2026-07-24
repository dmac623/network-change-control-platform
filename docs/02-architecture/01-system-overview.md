# System Overview

NCCP is a modular monolith organized around explicit domain boundaries. The first implementation favors transactional simplicity, shared operational tooling, and clear contracts over premature service decomposition.

## Logical layers

1. Experience layer: web application and API clients.
2. Application layer: use cases, orchestration, authorization, and workflow coordination.
3. Domain layer: change, policy, execution, verification, evidence, and reconciliation models.
4. Integration layer: Git, ServiceNow, CertiNext, execution engines, Vault, OPA, and object storage.
5. Infrastructure layer: PostgreSQL, Temporal, Kubernetes, and observability.

## Source-of-truth model

- Intent is authoritative for requested change.
- Git is authoritative for desired-state artifacts.
- Runtime systems are authoritative for observed state.
- NCCP is authoritative for governance state and evidence linkage.
