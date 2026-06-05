---
title: Transformer Architecture
tags:
  - architecture
---

# 7. Transformer Architecture

The specific neural design behind modern LLMs. Children trace the **forward path of a token**: embeddings (token + positional) → attention (self/cross/multi-head) → feed-forward, with residuals and layer-norm stabilizing it, assembled into encoder/decoder stacks. **Attention** is the load-bearing innovation (relating every token to every other); **decoder-only** is the dominant LLM variant. This is the mechanical detail of what Language Models are made of.

## Children

- token embeddings
- positional embeddings
- attention:
  - self-attention
  - cross-attention
  - multi-head attention
- feed-forward network
- residual connections
- layer normalization
- encoder
- decoder
- decoder-only architecture

## Related

- [Deep Learning](03-deep-learning.md) — the broader family
- [Language Models](06-language-models.md) — what this architecture powers
- [Model Internals](08-model-internals.md) — attention heads, parameters at run time
