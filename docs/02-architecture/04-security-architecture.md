# Security Architecture

## Principles

- Zero implicit trust between users, workloads, and execution targets.
- Short-lived credentials and workload identity.
- Separation of request, approval, and execution duties.
- Policy decisions are logged with inputs, outputs, and policy version.
- Sensitive data is referenced, not copied.

## Control points

- Identity federation and role mapping
- Fine-grained authorization
- Approval segregation
- Secret retrieval through Vault
- Signed artifacts and evidence hashes
- Immutable audit records
- Network egress controls for execution workers
