---
title: Model Internals
tags:
  - architecture
  - internals
---

# 8. Model Internals

The anatomy of a trained model at rest and at run. Children mix **static structure** (parameters/weights, architecture, layers, neurons, attention heads, vocabulary) with the **runtime pipeline** (tokenizer → context window → logits → probabilities → sampling). The throughline: text becomes tokens, tokens flow through weights, the model emits logits, sampling turns logits back into a token. Bridges architecture to inference.

## Children

- parameters / weights
- architecture
- layers
- neurons / units
- activations
- attention heads
- context window
- tokenizer
- vocabulary
- logits
- probabilities
- sampling strategy

## Related

- [Transformer Architecture](07-transformer-architecture.md) — the structure these internals instantiate
- [Inference](12-inference.md) — the sampling controls exposed to users
- [Math & Data Representation](04-math-and-data-representation.md) — logits and probability distributions
