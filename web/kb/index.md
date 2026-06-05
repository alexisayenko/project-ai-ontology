---
title: Overview
tags:
  - index
---

# AI / ML / LLM Ontology

A personal knowledge base mapping artificial intelligence
end-to-end as a multi-level ontology. The files stay **flat**
(`01-…26-`); this page is the **reading lens**: theory → build →
operate → ecosystem. The four groups below are navigation, not a
strict taxonomy — a few branches deliberately straddle several.

## I. Concepts — what AI is

| # | Branch | Covers |
| --- | --- | --- |
| 01 | [Artificial Intelligence](01-artificial-intelligence.md) | The root field; paradigms (symbolic vs statistical) and capability classes |
| 02 | [Machine Learning](02-machine-learning.md) | Learning from data, partitioned by supervision signal |
| 03 | [Deep Learning](03-deep-learning.md) | Neural-network mechanics and architecture families |
| 04 | [Math & Data Representation](04-math-and-data-representation.md) | The numeric substrate: tensors, embeddings, similarity |
| 05 | [Foundation Models](05-foundation-models.md) | Broadly pretrained, adaptable models by modality and role |
| 06 | [Language Models](06-language-models.md) | Text-specialized foundation models; lineage and post-training role |
| 07 | [Transformer Architecture](07-transformer-architecture.md) | The forward path of a token through attention |
| 08 | [Model Internals](08-model-internals.md) | Static anatomy + the runtime token pipeline |

## II. Building — how models and AI systems are made

| # | Branch | Covers |
| --- | --- | --- |
| 09 | [Data & Datasets](09-data-and-datasets.md) | The raw material: lifecycle, dataset types, data governance |
| 10 | [Training & Post-Training](10-training-and-post-training.md) | Acquiring capability, then shaping behavior |
| 11 | [Evaluation & Testing](11-evaluation-and-testing.md) | Measuring capability and failure modes |
| 12 | [Inference](12-inference.md) | A single model call — knobs and I/O |
| 13 | [Reasoning & Test-Time Compute](13-reasoning-and-test-time-compute.md) | Buying quality with compute at run time |
| 14 | [RAG](14-rag.md) | Grounding generation in retrieved documents |
| 15 | [Knowledge & Memory](15-knowledge-and-memory.md) | What the system knows and remembers, by lifespan |
| 16 | [Agents](16-agents.md) | Goal-directed iterative action with tools |
| 17 | [Tools, Skills, Commands & Protocols](17-tools-skills-commands-protocols.md) | Capabilities and the wiring that connects model to world |
| 18 | [AI Engineering](18-ai-engineering.md) | Building reliable systems around a fixed model |
| 19 | [Model Lifecycle](19-model-lifecycle.md) | Idea-to-retirement timeline |

## III. Operating — keeping systems usable, safe and economical

| # | Branch | Covers |
| --- | --- | --- |
| 20 | [Safety, Governance & Alignment](20-safety-governance-and-alignment.md) | Defensive controls, governance principles, alignment |
| 21 | [Security & Threat Model](21-security-threat-model.md) | The attacker's-eye view; agent-specific risks |
| 22 | [Cost & Economics](22-cost-and-economics.md) | Token/training economics, cost levers, unit economics |
| 23 | [Infrastructure & Runtime](23-infrastructure-and-runtime.md) | Compute and serving machinery |
| 24 | [Interfaces](24-interfaces.md) | How humans and systems reach the model |

## IV. World — ecosystem, vendors and historical lineage

| # | Branch | Covers |
| --- | --- | --- |
| 25 | [Vendor & Model Ecosystem](25-vendor-and-model-ecosystem.md) | The organizations and product families (incl. OpenClaw) |
| 26 | [People & Research Lineage](26-people-and-research-lineage.md) | The humans and intellectual history |

## Full tree

```text
AI / ML / LLM Ontology
│
├── I. CONCEPTS
│   ├── 1. Artificial Intelligence — symbolic vs statistical; generative/predictive/multimodal/agentic
│   ├── 2. Machine Learning — supervised · unsupervised · self/semi-supervised · RL · Bayesian
│   ├── 3. Deep Learning — NN mechanics · CNN · RNN · Transformer · diffusion · autoencoders · GANs
│   ├── 4. Math & Data Representation — scalar→tensor · embedding · latent space · similarity metrics
│   ├── 5. Foundation Models — language · vision · audio · video · multimodal · embedding · reranking · frontier
│   ├── 6. Language Models — statistical→neural→SLM→LLM · base/instruct/chat/code/reasoning
│   ├── 7. Transformer Architecture — embeddings · attention · FFN · residual · norm · encoder/decoder
│   └── 8. Model Internals — weights · layers · heads · context window · tokenizer · logits · sampling
│
├── II. BUILDING
│   ├── 9. Data & Datasets — lifecycle (source→clean→label→curate) · dataset types · data governance
│   ├── 10. Training & Post-Training — pretraining · SFT · instruction tuning · RLHF/RLAIF/DPO · distillation
│   ├── 11. Evaluation & Testing — benchmarks · human/automated eval · red teaming · eval-driven dev
│   ├── 12. Inference — prompts · tokens · temperature/top_p · structured output · streaming
│   ├── 13. Reasoning & Test-Time Compute — CoT · thinking budget · planning · reflection · verification
│   ├── 14. RAG — parse→chunk→embed→vector DB · semantic/hybrid search · rerank · grounded generation
│   ├── 15. Knowledge & Memory — short-term → long-term/user/project → knowledge graph → ontology
│   ├── 16. Agents — goal→plan→action→observation loop · tool use · multi-agent · (Claude Code, OpenClaw…)
│   ├── 17. Tools, Skills, Commands & Protocols — tools · skills · function calling · MCP · OpenAPI · SDK
│   ├── 18. AI Engineering — prompt/context/RAG engineering · spec/eval-driven dev · observability
│   └── 19. Model Lifecycle — research → train → eval → deploy → monitor → deprecate → retire
│
├── III. OPERATING
│   ├── 20. Safety, Governance & Alignment — guardrails · sandboxing · policy · privacy · responsible AI · alignment
│   ├── 21. Security & Threat Model — prompt/tool injection · data leakage · agent risks · personal-agent runtime risk
│   ├── 22. Cost & Economics — token/training economics · batching · routing · unit economics · build-vs-buy
│   ├── 23. Infrastructure & Runtime — local/cloud/edge · GPU/TPU · quantization · serving · vector DB · orchestration
│   └── 24. Interfaces — chat UI · API · CLI · IDE · browser · mobile · voice · background worker
│
└── IV. WORLD
    ├── 25. Vendor & Model Ecosystem — OpenAI · Anthropic · Google · Meta · Mistral · DeepSeek · xAI …
    │       └── local/open — LM Studio · Ollama · llama.cpp · vLLM · Hugging Face · OpenClaw
    └── 26. People & Research Lineage — symbolic · ML · DL · Transformer authors · LLM · alignment · founders
```

## Cross-cutting notes

`Knowledge & Memory` (15), `Agents` (16), and `Model Lifecycle`
(19) intentionally straddle several groups — they are operational
lenses across concepts, building, and production, not strict
taxonomic categories.

**OpenClaw** is tracked deliberately as its own class — a
**personal agent runtime**: not a model, vendor API, or plain
local inference tool, but a layer connecting an LLM, tools,
memory, chat channels, cron/background tasks, and real user
accounts. It appears under [Vendor & Model Ecosystem
→ local/open](25-vendor-and-model-ecosystem.md), as an example in
[Agents](16-agents.md), and as a risk class in [Security & Threat
Model](21-security-threat-model.md).

## How to read this KB

- **The tree is the index; cross-links are the structure.** Follow
  the "Related" links at the bottom of each branch.
- **Branches age differently.** Concepts (1–8) and most of Building
  are stable; Vendor (25) churns monthly; People (26) grows by
  accretion. See [`CLAUDE.md`](../../CLAUDE.md#branch-volatility).
