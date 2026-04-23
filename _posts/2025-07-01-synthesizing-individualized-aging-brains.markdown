---
layout: post
title:  "Synthesising individualised aging brains in health and disease with generative models and parallel transport"
date:   2025-07-01
author: Jingru Fu, Yuqi Zheng, Neel Dey, Daniel Ferreira & Rodrigo Moreno
venue: Medical Image Analysis
abstract: "Simulating prospective MRI scans from a given individual brain image is challenging: it requires accounting for canonical changes in aging and/or disease progression while also considering the individual brain's current status. We introduce InBrainSyn, a framework that uses parallel transport to adapt population-level aging trajectories learned by a generative deep template network to individual subjects, producing high-resolution longitudinal MRI that is topologically consistent with the original anatomy by design."
paper: https://arxiv.org/abs/2502.21049
image: /assets/papers/figures/arxiv-2502.21049.png
---

**Published in Medical Image Analysis (2025).**

Work by [Jingru Fu](/people/jingru), Yuqi Zheng, Neel Dey, Daniel Ferreira, and [Rodrigo Moreno](/people/rodrigo).

## Abstract

Simulating prospective magnetic resonance imaging (MRI) scans from a given individual brain image is challenging, as it requires accounting for canonical changes in aging and/or disease progression while also considering the individual brain's current status and unique characteristics. While current deep generative models can produce high-resolution anatomically accurate templates for population-wide studies, their ability to predict future aging trajectories for individuals remains limited, particularly in capturing subject-specific neuroanatomical variations over time.

In this study, we introduce **Individualised Brain Synthesis (InBrainSyn)**, a framework for synthesising high-resolution subject-specific longitudinal MRI scans that simulate neurodegeneration in both Alzheimer's disease (AD) and normal aging. InBrainSyn uses a parallel-transport algorithm to adapt the population-level aging trajectories learned by a generative deep template network, enabling individualised aging synthesis. As InBrainSyn uses diffeomorphic transformations to simulate aging, the synthesised images are topologically consistent with the original anatomy by design.

We evaluated InBrainSyn both quantitatively and qualitatively on AD and healthy control cohorts from the Open Access Series of Imaging Studies (OASIS-3) dataset. Experimentally, InBrainSyn can also model neuroanatomical transitions between normal aging and AD. An evaluation on an external set supports its generalisability. Overall, with only a single baseline scan, InBrainSyn synthesises realistic 3D spatiotemporal T1-weighted MRI scans, producing personalised longitudinal aging trajectories.

- Preprint: [arXiv:2502.21049](https://arxiv.org/abs/2502.21049)
- Code: [minnelab/InBrainSyn](https://github.com/minnelab/InBrainSyn)
