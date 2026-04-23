---
layout: post
title:  "Fast 3D image generation for healthy brain aging using diffeomorphic registration"
date:   2023-06-15
author: Jingru Fu, Antonios Tzortzakakis, José Barroso, Eric Westman, Daniel Ferreira & Rodrigo Moreno
venue: Human Brain Mapping
abstract: "Proposes a methodology for generating 3D MRI scans of healthy brain aging from two scans acquired at different time points — filling missing data in longitudinal cohorts with anatomically plausible images that capture subject-specific aging. Introduces two modules within Synthmorph, a fast deep-learning diffeomorphic registration method, to simulate aging between first and last available scans. 7,548 images were generated (one per subject per 6 months), and quality was evaluated quantitatively and by an experienced neuroradiologist."
paper: https://doi.org/10.1002/hbm.26165
image: /assets/papers/figures/arxiv-2205.15607.png
---

**Published in Human Brain Mapping (2023).**

Work by [Jingru Fu](/people/jingru), Antonios Tzortzakakis, José Barroso, Eric Westman, Daniel Ferreira, and [Rodrigo Moreno](/people/rodrigo). Basis for the later [Synthetic Healthy Brain Aging dataset](/code/).

## Abstract

Analysing and predicting brain aging is essential for early prognosis and accurate diagnosis of cognitive diseases. The technique of neuroimaging, such as Magnetic Resonance Imaging (MRI), provides a non-invasive means of observing the aging process within the brain. With longitudinal image-data collection, data-intensive artificial intelligence (AI) algorithms have been used to examine brain aging. However, existing state-of-the-art algorithms tend to be restricted to group-level predictions and suffer from unreal predictions.

This paper proposes a methodology for generating longitudinal MRI scans that capture subject-specific neurodegeneration and retain anatomical plausibility in aging. The proposed methodology is developed within the framework of diffeomorphic registration and relies on three key technological advances to generate subject-level anatomically plausible predictions:

1. A computationally efficient and individualised generative framework based on registration.
2. An aging generative module based on biological linear aging progression.
3. A quality-control module to fit registration for the generation task.

The methodology was evaluated on 2,662 T1-weighted MRI scans from 796 participants from three different cohorts. The synthetic images were assessed using six commonly used quantitative criteria and a qualitative assessment by a neuroradiologist. Overall, the experiments show that the proposed method can produce anatomically plausible predictions that can be used to enhance longitudinal datasets, in turn enabling data-hungry AI-driven healthcare tools.

- Paper: [doi:10.1002/hbm.26165](https://doi.org/10.1002/hbm.26165)
- Preprint: [arXiv:2205.15607](https://arxiv.org/abs/2205.15607)
- Code: [minnelab/Synthetic-Brain-Aging](https://github.com/minnelab/Synthetic-Brain-Aging)
- Dataset: [AIDA Data Hub](https://datahub.aida.scilifelab.se/10.23698/aida/synthetic/shbamri)
