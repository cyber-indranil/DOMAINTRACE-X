# DOMAINTRACE-X — Public Architecture Overview

This document intentionally describes the project at a high level.

## Investigation model

DOMAINTRACE-X accepts a domain or host as an investigation target and coordinates a backend-owned evidence-producing pipeline.

### Producer sequence

1. Baseline Investigation
2. Autonomous Discovery
3. Trace Resurrection
4. Relationship Fusion
5. Evidence Continuity
6. Threat Intelligence

### Derived investigator views

- DNS Reconstruction
- Infrastructure Intelligence
- Host Discovery
- Trace Resurrection
- Threat Intelligence
- Relationship Graph
- Timeline
- Evidence Vault

## Evidence doctrine

A producer result is not considered authoritative solely because execution completed.

The public evidence doctrine requires:

1. normalized result
2. durable persistence
3. SHA-256 calculation
4. evidence registration
5. run identifier and locator
6. schema validation
7. immediate reopen by locator
8. hash parity between sealed and reopened evidence

A persistence or reopen-verification failure is not represented as a successful sealed result.

## Relationship doctrine

Relationship presentation is evidence-first.

- explicit persisted relationships may be visualized
- visual proximity is not evidence
- shared infrastructure does not automatically imply ownership or control
- historical and current meaning must not be conflated
- inferred meaning must never masquerade as direct observation

## Public boundary

Operational implementation details, provider logic, credentials, production service configuration and live case evidence are intentionally excluded from this public documentation.
