---
title: Training & Post-Training
tags:
  - training
  - lifecycle
---

# 10. Training and Post-Training

How a model acquires capability and is then shaped in its behavior. Children are a **temporal pipeline**: data work (collection/cleaning/curation) → pretraining (raw capability) → post-training (SFT, instruction tuning, RLHF/RLAIF/DPO, alignment, safety tuning) → distillation. The key split: **pretraining** gives knowledge/ability; **post-training** gives obedience, preference, and safety. This is the factory that converts a base model into an instruct/chat model.

## Children

- data collection
- data cleaning
- data curation
- pretraining
- fine-tuning
- supervised fine-tuning / SFT
- instruction tuning
- RLHF
- RLAIF
- DPO
- preference optimization
- alignment
- safety tuning
- model distillation

## Related

- [Machine Learning](02-machine-learning.md) — self-supervised learning, RL
- [Language Models](06-language-models.md) — base vs instruct/chat models
- [Evaluation & Testing](11-evaluation-and-testing.md) — measuring the result
- [Safety, Security & Governance](20-safety-governance-and-alignment.md) — alignment and safety tuning
