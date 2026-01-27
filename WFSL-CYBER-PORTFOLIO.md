# WFSL Cyber Portfolio

## Status
Authoritative. Active. Enterprise-ready.

## Purpose
The WFSL Cyber portfolio provides lawful, deterministic, evidence-first cyber instrumentation and integrity analysis.  
It is designed for verification, monitoring, stability assessment, and incident reporting without engaging in intrusive, offensive, or regulated interception activities.

The portfolio operates strictly within observation, integrity assurance, and evidence generation boundaries.

---

## Portfolio Components

### 1. wfsl-cyber-contracts
**Role:** Cyber authority and governance root.

Responsibilities:
- Canonical schemas
- Evidence contracts
- Stability definitions
- Enterprise readiness documentation
- Governance boundaries

This repository defines what is permitted, measurable, and attestable across WFSL Cyber.

---

### 2. wfsl-cyber-cli
**Role:** Operator interface.

Responsibilities:
- Controlled execution of cyber instruments
- Deterministic command structure
- Governance enforcement via ProofGate manifests
- Integration point for subcommands such as NIIM

No raw data capture occurs here.

---

### 3. wfsl-niim (Network Integrity & Intermittence Monitor)
**Role:** Cyber instrument.

Responsibilities:
- Passive network state observation
- Snapshot capture
- Intermittence detection
- Stability scoring
- Deterministic incident report generation

NIIM does not intercept traffic, decrypt content, manipulate packets, or perform surveillance.

---

## Evidence Chain

1. Instrument capture (NIIM)
2. Snapshot persistence (local, append-only)
3. Deterministic scoring (stability engine)
4. Incident synthesis (report generator)
5. Governance validation (ProofGate)
6. Enterprise attestation (Cyber Contracts)

All outputs are:
- Time-stamped
- Deterministic
- Reproducible
- Non-destructive

---

## Lawful Boundary Statement

WFSL Cyber tooling:
- Does not perform interception
- Does not bypass encryption
- Does not access third-party data
- Does not monitor other users
- Does not exploit vulnerabilities

All tooling operates on assets the operator is authorised to observe.

---

## Enterprise Readiness

This portfolio is suitable for:
- ISPs
- Infrastructure providers
- Facilities operators
- Managed service environments
- Compliance-led organisations

It supports:
- Incident evidence
- Stability attestations
- Service integrity reporting
- Provider escalation packs

---

## Governance

- All repositories are ProofGate governed
- Schema changes require explicit versioning
- Instruments cannot self-elevate authority
- Cyber authority is singular and centralised

---

## Portfolio Declaration

WFSL Cyber is a defensive, evidence-led cyber capability.  
It is intentionally constrained, legally aligned, and enterprise-focused.

This document locks the Cyber portfolio structure.
