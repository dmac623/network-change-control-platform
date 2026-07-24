# ADR-0002: Modular Monolith

- Status: Accepted
- Date: 2026-07-24

## Context

The platform requires strong transactional consistency and rapid evolution across many new domain boundaries.

## Decision

Begin with a FastAPI modular monolith. Enforce module boundaries through packages, interfaces, ownership, and tests.

## Consequences

Operational complexity stays low while the domain stabilizes. Modules may later be extracted when independent scaling, ownership, or failure isolation justifies it.
