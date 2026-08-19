# Architecture

## Overview

Mycelium is structured as a layered system:

1. **Node layer** — low-power devices with sensing, actuation, and local compute.
2. **Mesh layer** — encrypted, delay-tolerant peer-to-peer communication.
3. **Intelligence layer** — edge agents that learn from local context without requiring cloud dependency.
4. **Protocol layer** — discovery, identity, routing, synchronization, and consent-aware sharing.
5. **Governance layer** — community-defined rules for updates, policy, and participation.

## Core properties

- Local-first execution
- Intermittent connectivity tolerance
- Energy-aware behavior
- Failure isolation and graceful degradation
- Auditability of protocol behavior

## Early component map

- `firmware/node` — embedded runtime for devices
- `software/mesh` — transport and routing services
- `software/edge-agent` — local inference and adaptation logic
- `protocol/specs` — stable protocol documents
- `protocol/rfcs` — proposals and design changes
