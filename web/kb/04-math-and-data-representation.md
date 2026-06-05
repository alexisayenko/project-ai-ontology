---
title: Math & Data Representation
tags:
  - foundations
  - math
---

# 4. Mathematical and Data Representation Layer

The numeric objects everything runs on — the "physics layer." The
children form a **dimensional ladder** (scalar → vector → matrix →
tensor), then the learned representations built on it (embedding,
latent space) and the operations that compare them (similarity
metrics). Embeddings and high-dimensional geometry are *why*
semantic search and meaning-as-distance work; similarity metrics
are the bridge to [RAG](14-rag.md).

## Children

- **scalar → vector → matrix → tensor** — the dimensional ladder
- **embedding** — a learned vector that encodes meaning
- **latent space** — the geometry embeddings live in
- **probability distribution** — model outputs are distributions
- **similarity metrics** — how vectors are compared:
  - cosine similarity
  - dot product
  - Euclidean distance
- **high-dimensional geometry** — why distance encodes semantics

## Related

- [RAG](14-rag.md) — semantic search built on embeddings +
  similarity
- [Foundation Models](05-foundation-models.md) — embedding models
  that produce these vectors
- [Model Internals](08-model-internals.md) — logits and
  probabilities at the output
