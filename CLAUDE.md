# CLAUDE.md

**AI / ML / LLM Ontology** — a personal knowledge base mapping
artificial intelligence end-to-end as a multi-level ontology.

Fast-path context for Claude Code. Human-oriented entry point:
[README.md](README.md). Full tree + branch map:
[web/kb/index.md](web/kb/index.md).

## Key principle

> Map the field as a connected graph, not a flat glossary. Every
> node links upward (the broader category it specializes) and
> sideways (concepts in other branches it depends on or mirrors).

Many concepts legitimately live in several branches — vector DB
(retrieval + infrastructure), attention (deep learning +
Transformer), the agent loop (reinforcement learning + agents),
memory (knowledge/memory + agents). The tree is the primary
index; cross-links carry the real structure. Notes that float
free of the graph are the first thing pruned.

## Product

A personal, single-author knowledge base on AI/ML/LLMs.
Markdown-only. Files stay flat (`01-…26-`); the four groups below
are a reading lens in `web/kb/index.md`, not a folder hierarchy.

- **I. Concepts** (1–8): AI · ML · Deep Learning · Math/Data ·
  Foundation Models · Language Models · Transformer · Internals
- **II. Building** (9–19): Data & Datasets · Training · Evaluation ·
  Inference · Reasoning · RAG · Knowledge & Memory · Agents ·
  Tools/Protocols · AI Engineering · Model Lifecycle
- **III. Operating** (20–24): Safety/Governance/Alignment ·
  Security & Threat Model · Cost & Economics · Infrastructure ·
  Interfaces
- **IV. World** (25–26): Vendor & Model Ecosystem · People & Lineage

`Knowledge & Memory` (15), `Agents` (16), and `Model Lifecycle`
(19) straddle groups by design — operational lenses, not strict
categories. **OpenClaw** is tracked as its own class — a *personal
agent runtime* (LLM + tools + memory + channels + cron + real
accounts) — appearing in branches 25, 16, and 21.

Audience: the author. Not a shipped product.

## Branch volatility

Different branches age at different rates — relevant when deciding
what to update:

- **Stable scaffolding (1–24, conceptual):** changes slowly.
- **Churns fast (25):** vendors/models shift monthly — expect
  frequent edits and stale entries (OpenClaw included).
- **Grows by accretion (26):** people/lineage; append, rarely revise.

## Tech stack

Markdown source under `web/kb/`, rendered with **MkDocs Material**.
Source `.md` is authoritative; the build is disposable. Built and
deployed by **GitHub Actions → GitHub Pages**
([`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)) on
push to `main` — no local toolchain needed. Public URL:
<https://ai.isayenko.org> (custom domain via `web/kb/CNAME`).

(Diverges from `project-consciousness`, which builds locally and
deploys to Cloudflare Workers — same MkDocs build, different host.)

## Repo

[alexisayenko/project-ai-ontology](https://github.com/alexisayenko/project-ai-ontology)

## Where to look for more

- [README.md](README.md) — repo entry point + structure
- [web/kb/index.md](web/kb/index.md) — full tree + branch map
