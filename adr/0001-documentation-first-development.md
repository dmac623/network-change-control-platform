# ADR-0001: Documentation-First Development

- Status: Accepted
- Date: 2026-07-24

## Context

NCCP spans governance, security, workflows, integrations, evidence, and vendor-neutral execution. Unrecorded design decisions would create implementation drift and hidden coupling.

## Decision

Use documentation-first development. Material implementation work must trace to product documentation, contracts, diagrams, or ADRs.

## Consequences

Design review occurs before implementation. Documentation changes are reviewed with the same rigor as code changes.
