# Scalability and Resilience

## Strategy

- Scale stateless API and worker pools horizontally.
- Partition execution workers by region, network zone, or vendor domain.
- Use idempotency keys for all external side effects.
- Persist workflow state durably.
- Apply backpressure at authorization and worker queues.
- Isolate slow integrations with retries and circuit breakers.
- Preserve evidence even when downstream closure integrations fail.
