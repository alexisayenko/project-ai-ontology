---
title: Infrastructure & Runtime
tags:
  - infrastructure
  - runtime
---

# 23. Infrastructure and Runtime

The compute and serving machinery that runs models in production. Children mix **where it runs** (local/cloud/edge inference, GPU/TPU), **efficiency techniques** (quantization, batching, caching), and **serving components** (model serving, vector DB, orchestration, monitoring). The organizing concern is *cost, latency, and scale of serving*. This is the operational floor under inference and the home of the vector DB that RAG depends on.

## Children

- API
- local inference
- cloud inference
- edge inference
- GPU
- TPU
- quantization
- batching
- caching
- model serving
- vector database
- orchestration
- monitoring

## Related

- [Inference](12-inference.md) — what this runs
- [RAG](14-rag.md) — depends on the vector database
- [AI Engineering](18-ai-engineering.md) — deployment, cost/latency optimization
