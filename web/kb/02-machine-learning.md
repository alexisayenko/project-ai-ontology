---
title: Machine Learning
tags:
  - paradigm
  - foundations
---

# 2. Machine Learning / ML

Systems that improve at a task from data rather than explicit
programming. The children partition by **supervision signal** —
*where the learning signal comes from*: labeled (supervised), none
(unsupervised), self-generated (self-supervised), partial
(semi-supervised), or reward (reinforcement). Reinforcement
learning is special because it learns from interaction over time,
hence its own sub-vocabulary (agent / environment / state / action
/ reward / policy), which reappears generalized in
[Agents](16-agents.md).

## Children

- **supervised learning** — learn from labeled examples:
  - classification
  - regression
  - ranking
- **unsupervised learning** — find structure without labels:
  - clustering
  - dimensionality reduction
  - anomaly detection
- **self-supervised learning** — labels derived from the data
  itself (the basis of LLM pretraining)
- **semi-supervised learning** — a little labeled, a lot unlabeled
- **reinforcement learning** — learn a policy from reward:
  - agent · environment · state · action · reward · policy
- **probabilistic / Bayesian ML** — reasoning under uncertainty

## Related

- [Deep Learning](03-deep-learning.md) — ML realized with neural
  networks
- [Training & Post-Training](10-training-and-post-training.md) —
  self-supervised pretraining, RLHF
- [Agents](16-agents.md) — the RL action/observation loop
  generalized to LLMs + tools
