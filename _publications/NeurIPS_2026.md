---
title: "Rethinking Projector Training in Multimodal LLMs."
collection: publications
excerpt: 'We show that projector training in multimodal LLMs primarily performs coarse alignment, and introduce PORTAL, a training-free initialization method that achieves this alignment without paired data or gradient-based optimization.'
date: 2026-09-01
venue: 'NeurIPS'
paperurl: 'https://brbiclab.epfl.ch/projects/portal/'
---

Multimodal LLMs are typically trained in two stages. First, a projector is trained on large image-caption datasets to align a frozen vision encoder with a frozen language model. This is followed by joint training of the projector and language model on multimodal instructions. Despite its widespread use, the role of the projector alignment stage remains poorly understood. In this work, we show that projector alignment primarily performs coarse alignment, mapping visual features into a language-model-compatible input space that admits a large set of possible solutions. Motivated by these findings, we propose PORTAL (Projector via Optimal-transpoRT ALignment), which constructs the projector directly from the marginal feature statistics of the two modalities, eliminating the need for paired image-caption data or gradient-based optimization during projector alignment.
