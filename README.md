# AI / ML / LLM Ontology

A personal knowledge base mapping the field of artificial
intelligence as a multi-level ontology — from the foundational
paradigms (symbolic vs statistical AI) down through machine
learning, deep learning, the Transformer, language models, data,
training, inference, RAG, agents, tooling, safety, security, cost,
infrastructure, and the vendor/people ecosystem that produces it
all.

## Overview

Markdown-only KB, structured as a 26-branch ontology grouped into
four reading lenses — **Concepts → Building → Operating → World**.
Each branch is one file under [`web/kb/`](web/kb/); files stay
flat (`01-…26-`) and the grouping lives in
[`web/kb/index.md`](web/kb/index.md). Branches cross-link where
concepts span categories (a vector DB lives in both retrieval and
infrastructure; the agent loop echoes reinforcement learning;
attention belongs to both deep learning and the Transformer).

Source is markdown — readable directly on GitHub or any local
viewer. Also rendered with MkDocs Material (build is disposable;
the `.md` source stays authoritative).

## Quick start

1. Read [`CLAUDE.md`](CLAUDE.md) for the key principle and framing.
2. Read [`web/kb/index.md`](web/kb/index.md) for the full tree and
   the map of all 23 branches.

## Structure

```text
project-ai-ontology/
├── web/
│   ├── kb/                  # the ontology — one file per branch
│   │   ├── index.md         # overview + full tree + branch map
│   │   ├── 01-artificial-intelligence.md
│   │   ├── …                # branches 02–25
│   │   ├── 26-people-and-research-lineage.md
│   │   └── tags.md          # tag index (MkDocs)
│   └── mkdocs.yml           # MkDocs Material config
├── CLAUDE.md                # agent-specific guidance
├── README.md               # this file
└── LICENSE
```

Folders are created when content lands, not before. `docs/`
(project strategy) and the deploy pipeline (`package.json`,
`wrangler.toml`) are intentionally not scaffolded yet — add them
the day they're needed.

## Naming

| Convention | Example |
| --- | --- |
| `NN-kebab-case.md` for branches | `07-transformer-architecture.md` |
| Lowercase folders | `web/`, `kb/` |
| `UPPERCASE.md` only for conventional files | `README.md`, `CLAUDE.md`, `LICENSE` |

The `NN-` numeric prefix preserves the ontology's branch order in
file listings and MkDocs nav.
