# Runtime Architecture

A change request is handled as a durable workflow. Temporal coordinates long-running transitions, retries, timeouts, approvals, and compensating behavior.

The API records intent and governance events. Renderers create review artifacts. Policy gates determine eligibility. Execution workers invoke approved adapters. Verification captures observed outcomes. Evidence services seal artifacts and reconciliation determines closure eligibility.
