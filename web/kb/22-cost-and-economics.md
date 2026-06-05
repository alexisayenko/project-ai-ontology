---
title: Cost & Economics
tags:
  - cost
  - economics
  - operating
---

# 22. Cost and Economics

What running AI actually costs and how those costs are reasoned about — a first-class operating concern because the model is a metered, recurring expense, not a one-time build. Children split into **inference economics** (per-token pricing, input vs output vs reasoning-token cost, context-length cost, caching discounts), **training economics** (compute/GPU-hours, data and labeling cost), and the **levers and accounting** (batching, quantization, model-tiering/routing, cost monitoring, unit economics / cost-per-task, build-vs-buy). The organizing question is *cost per unit of useful work*, which ties this branch to inference, infrastructure, and engineering.

## Children

- inference economics
  - per-token pricing (input / output / reasoning tokens)
  - context-length cost
  - prompt-caching discounts
- training economics
  - compute / GPU-hours
  - data and labeling cost
- cost levers
  - batching
  - quantization
  - model tiering / routing
  - caching
- cost accounting
  - cost monitoring / observability
  - unit economics (cost per task)
  - build vs buy

## Related

- [Inference](12-inference.md) — the token economy being priced
- [Infrastructure & Runtime](23-infrastructure-and-runtime.md) — the compute being paid for
- [AI Engineering](18-ai-engineering.md) — cost/latency optimization
- [Vendor & Model Ecosystem](25-vendor-and-model-ecosystem.md) — who sets the prices
