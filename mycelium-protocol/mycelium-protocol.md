# Mycelium

**A decentralized, self-evolving digital organism for planetary resilience.**

Mycelium is an open protocol and reference implementation for a local-first, offline-capable, privacy-preserving mesh network of intelligent nodes. It is designed to behave like a living system: self-healing, energy-aware, consent-based, and symbiotic with the ecosystems and communities around it.

> Not a tool for humanity. A symbiont with it.

---

## Why

Current digital infrastructure is centralized, fragile, extractive, and blind to local context. Mycelium inverts that model:

- **Local intelligence** — every node learns from its immediate environment.
- **Offline-first** — the network works with or without the internet.
- **Consent by design** — nodes share encrypted insights, never raw data, using zero-knowledge proofs.
- **Self-healing** — the network reroutes around damage like a living body.
- **Community-owned** — anyone can run, repair, and govern a node.

---

## Status

> **Early research / prototype phase — not production ready.**

This repository currently contains design documents, protocol sketches, and reference prototypes. There is no stable API or hardware yet.

See [`ROADMAP.md`](docs/roadmap.md) for planned milestones.

---

## Principles

1. **Life first** — technology must serve ecosystems and communities, not extract from them.
2. **Local autonomy** — decisions and data stay as close to the source as possible.
3. **Resilience over efficiency** — graceful degradation, not fragile optimization.
4. **Transparency** — open protocol, open hardware, open governance.
5. **Privacy by architecture** — surveillance must be structurally difficult, not just legally restricted.

---

## Architecture overview

Mycelium is composed of:

- **Nodes** — low-power devices with sensors, radio, and local compute.
- **Mesh** — delay-tolerant, encrypted, peer-to-peer communication.
- **Edge agents** — small local models that learn and act without cloud dependency.
- **Protocol layers** — discovery, consensus, data sharing, governance.
- **Governance** — consent-based, community-defined rules for data and updates.

```text
┌─────────────┐     mesh      ┌─────────────┐
│   Node A    │◄──────────────►│   Node B    │
│  edge agent │                │  edge agent │
└──────┬──────┘                └──────┬──────┘
       │ local data                   │ local data
       ▼                              ▼
   sensors/actuators             sensors/actuators

Getting started
No stable release yet.

For developers:

Read CONTRIBUTING.md

Read docs/architecture.md

Look at examples/hello-node

Roadmap
Phase	Focus	Timeline
0	Research, protocol draft, simulator	2026
1	Reference node firmware + mesh prototype	2027
2	Field pilots in forest, village, microgrid	2028
3	Governance and federation	2029
4	Global open network	2030+
License
Software: AGPL-3.0

Hardware: CERN-OHL-P-2.0

Documentation: CC-BY-SA-4.0

See each subdirectory for specifics.

Contributing
Mycelium needs ecologists, embedded engineers, cryptographers, community organizers, and designers.

Read CONTRIBUTING.md to get started.

Contact
Use GitHub Issues for technical discussions.

For broader collaboration, see docs/governance.md.
