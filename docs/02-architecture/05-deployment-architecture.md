# Deployment Architecture

NCCP targets Kubernetes with independently scalable web, API, workflow worker, and execution worker deployments.

Stateful dependencies:

- PostgreSQL for transactional data
- Temporal for durable workflows
- S3-compatible storage for evidence
- Vault for secret material
- OPA for policy evaluation

Execution workers should be isolated by trust zone and network reachability.
