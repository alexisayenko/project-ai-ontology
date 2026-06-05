---
title: RAG
tags:
  - rag
  - retrieval
---

# 14. RAG / Retrieval-Augmented Generation

Grounding generation in retrieved external documents. Children form an **end-to-end pipeline**: ingestion (parse → chunk → extract metadata → embed → store in vector DB), retrieval (semantic/keyword/hybrid search → rerank), and generation (context injection → grounded generation → citations/attribution). It exists to fix LLMs' two weaknesses: stale knowledge and hallucination. Leans directly on embeddings/similarity and on vector databases.

## Children

- source documents
- parsing
- chunking
- metadata extraction
- embeddings
- vector database
- semantic search
- keyword search
- hybrid search
- retrieval
- reranking
- context injection
- grounded generation
- citations
- source attribution

## Related

- [Math & Data Representation](04-math-and-data-representation.md) — embeddings and similarity metrics
- [Infrastructure & Runtime](23-infrastructure-and-runtime.md) — the vector database
- [Knowledge & Memory](15-knowledge-and-memory.md) — external knowledge the system retrieves from
