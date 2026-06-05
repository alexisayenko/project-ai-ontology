---
title: Security & Threat Model
tags:
  - security
  - threats
  - agents
---

# 21. Security and Threat Model

The attacker's-eye view — how an AI system gets subverted, and the risks that scale with autonomy. Where [Safety, Governance & Alignment](20-safety-governance-and-alignment.md) is the defense, this is the offense catalogue. Classic LLM threats (prompt injection, data leakage, model misuse, jailbreaking) widen sharply once the model holds tools, memory, and real user accounts — the **personal-agent-runtime** class (e.g. OpenClaw) is the sharpest case, since it connects an LLM to the filesystem, channels, background/cron tasks, and live credentials. Threat surface tracks capability: the more an agent can do, the more an attacker who hijacks it can do.

## Children

- classic LLM threats
  - prompt injection
  - data leakage
  - model misuse
  - jailbreaking
- agent-specific risks (scale with autonomy)
  - tool injection
  - malicious skills/plugins
  - filesystem access risk
  - email/calendar/API over-permissioning
  - persistent memory poisoning
  - token-drain attacks
  - OpenClaw-like personal-agent risk model (LLM + tools + memory + channels + cron + real accounts in one runtime)

## Related

- [Safety, Governance & Alignment](20-safety-governance-and-alignment.md) — the defensive controls against these threats
- [Tools, Skills & Protocols](17-tools-skills-commands-protocols.md) — tools are the attack surface
- [Agents](16-agents.md) — autonomy is what amplifies the threat
