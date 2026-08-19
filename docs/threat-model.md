# Threat Model (Pre-Alpha)

This is an initial threat model draft and will evolve as implementation matures.

## Assets to protect

- Node identity and key material
- Integrity of local decisions and policies
- Confidentiality of shared insights
- Availability of mesh communication under disruption
- Community governance records and update chains

## Adversaries

- Passive network observers
- Active packet injectors and replay attackers
- Compromised nodes within a local cluster
- Supply-chain attackers targeting firmware/software artifacts
- Coercive actors attempting non-consensual data extraction

## Primary threats

- Metadata leakage from traffic patterns
- Node impersonation and Sybil-style identity abuse
- Malicious update propagation
- Routing manipulation and partition attacks
- Physical node capture

## Initial mitigations

- Mutual authentication with rotating keys
- Message signing, replay protection, and bounded TTL
- Encrypted transport with forward secrecy
- Signed update manifests and verifiable build provenance
- Local data minimization and consent policy enforcement

## Open questions

- Best strategy for low-power key rotation in sparse connectivity
- Practical privacy-preserving analytics for community-level insights
- Governance-safe emergency patch procedures
