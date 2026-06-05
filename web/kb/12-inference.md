---
title: Inference
tags:
  - inference
  - runtime
---

# 12. Inference

A single act of running the model to get output. Children are the **knobs and I/O of one call**: the input structure (system/developer/user messages, context), the token economy (input/output/reasoning tokens, context length), the sampling controls (temperature, top_p, max tokens, stop sequences), and the output shape (structured output, JSON schema, streaming). This is the practitioner's primary control surface — what you actually touch via an API.

## Children

- prompt
- system instructions
- developer instructions
- user message
- context
- context length
- input tokens
- output tokens
- reasoning tokens
- temperature
- top_p
- max tokens
- stop sequences
- structured output
- JSON schema
- streaming output

## Related

- [Model Internals](08-model-internals.md) — the sampling and logits these knobs control
- [Reasoning & Test-Time Compute](13-reasoning-and-test-time-compute.md) — reasoning tokens, thinking budget
- [Infrastructure & Runtime](23-infrastructure-and-runtime.md) — where inference physically runs
