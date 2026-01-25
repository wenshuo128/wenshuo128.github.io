---
title: "With Limited Data for Multimodal Alignment, Let the STRUCTURE Guide You."
collection: publications
excerpt: 'STRUCTURE is a framework for building multimodal models in low-data regimes by aligning frozen unimodal foundation models, enabling strong performance on zero-shot classification and retrieval tasks. It introduces a simple, plug-and-play regularization technique that preserves the geometric structure of each modality’s latent space and aligns layers with the highest representational similarity across modalities.'
date: 2025-09-01
venue: 'NeurIPS'
paperurl: 'https://brbiclab.epfl.ch/projects/structure/'
---


Multimodal models have demonstrated powerful capabilities in complex tasks requiring multimodal alignment including zero-shot classification and cross-modal retrieval. However, existing models typically rely on millions of paired multimodal samples, which are prohibitively expensive or infeasible to obtain in many domains. In this work, we explore the feasibility of building multimodal models with limited amount of paired data by aligning pretrained unimodal foundation models. We show that high-quality alignment is possible with as few as tens of thousands of paired samples—less than 1% of the data typically used in the field. To achieve this, we introduce STRUCTURE, an effective regularization technique that preserves the neighborhood geometry of the latent space of unimodal encoders. Additionally, we show that aligning last layers is often suboptimal and demonstrate the benefits of aligning the layers with the highest representational similarity across modalities. These two components can be readily incorporated into existing alignment methods, yielding substantial gains across 24 zero-shot image classification and retrieval benchmarks, with average relative improvement of 51.6% in classification and 91.8% in retrieval tasks.
