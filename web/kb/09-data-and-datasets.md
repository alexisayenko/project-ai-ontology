---
title: Data & Datasets
tags:
  - data
  - foundations
---

# 9. Data and Datasets

The raw material every model is made of — promoted here to a first-class branch because data quality bounds model quality more than architecture does. Children span the **data lifecycle** (sourcing, cleaning, labeling, curation, augmentation), **dataset types** (pretraining corpora, instruction/preference datasets, evaluation sets, synthetic data), and the **governance** that rides on data (licensing, provenance, PII, contamination, bias). This branch is upstream of training and evaluation; "garbage in, garbage out" is the whole reason it stands alone rather than hiding inside [Training & Post-Training](10-training-and-post-training.md).

## Children

- data lifecycle
  - sourcing / collection
  - cleaning / deduplication
  - labeling / annotation
  - curation / filtering
  - augmentation
- dataset types
  - pretraining corpora
  - instruction datasets
  - preference datasets
  - evaluation / benchmark sets
  - synthetic data
- data governance
  - licensing
  - provenance
  - PII / privacy
  - contamination / leakage
  - bias and representativeness

## Related

- [Training & Post-Training](10-training-and-post-training.md) — the consumer of this data
- [Evaluation & Testing](11-evaluation-and-testing.md) — evaluation sets and contamination
- [RAG](14-rag.md) — retrieval over document data
- [Safety, Governance & Alignment](20-safety-governance-and-alignment.md) — data privacy and responsible sourcing
