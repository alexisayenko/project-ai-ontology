---
title: Safety, Governance & Alignment
tags:
  - safety
  - governance
  - alignment
---

# 20. Safety, Governance and Alignment

Keeping deployed AI controlled, accountable, and pointed at intended goals. This branch is the DEFENSE and PRINCIPLES side — the controls you put in place and the values they serve (the attacker's-eye threat model lives in [Security & Threat Model](21-security-threat-model.md)). Children split into **defensive controls** (guardrails, permissions, sandboxing, audit logs, policy enforcement, access control), **governance principles** (privacy, responsible AI, transparency), and **alignment** (making the model want what we want — the training-time counterpart to runtime guardrails). The distinction from evaluation: evaluation *measures* risk; this branch *enforces* against it and sets the values it enforces toward.

## Children

- guardrails
- permissions
- sandboxing
- audit logs
- policy enforcement
- access control
- privacy
- responsible AI
- transparency
- alignment
- alignment risk

## Related

- [Security & Threat Model](21-security-threat-model.md) — the threats these controls defend against
- [Evaluation & Testing](11-evaluation-and-testing.md) — measuring risk vs enforcing against it
- [Training & Post-Training](10-training-and-post-training.md) — alignment and safety tuning
