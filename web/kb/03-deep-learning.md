---
title: Deep Learning
tags:
  - foundations
  - architecture
---

# 3. Deep Learning

Machine learning using multi-layer neural networks — the substrate
of everything modern. Its children mix **mechanics** (layers,
activations, gradients, backprop, loss, optimizers) with
**architecture families** (CNN, RNN, Transformer, diffusion,
autoencoders, GANs). The mechanics are universal across
architectures; the architectures are design families suited to
different data — CNN→spatial, RNN→sequential, Transformer→
relational, diffusion→generative.

## Children

- **neural networks** — the general function approximator
- **layers** · **activations** · **gradients** ·
  **backpropagation** · **loss functions** · **optimizers** — the
  universal training mechanics
- **CNN** — convolutional, for spatial/grid data
- **RNN / LSTM / GRU** — recurrent, for sequences
- **Transformer** — attention-based; see
  [Transformer Architecture](07-transformer-architecture.md)
- **diffusion models** — iterative denoising generators
- **autoencoders** — learned compression / representation
- **GANs** — generator-vs-discriminator adversarial training

## Related

- [Transformer Architecture](07-transformer-architecture.md) — the
  architecture behind modern LLMs
- [Math & Data Representation](04-math-and-data-representation.md) — the
  tensors and embeddings these networks operate on
- [Model Internals](08-model-internals.md) — what a trained network
  looks like at rest and at run
