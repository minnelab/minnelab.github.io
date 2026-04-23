---
layout: post
title:  "Learning accurate rigid registration for longitudinal brain MRI from synthetic data"
date:   2025-04-15
author: Jingru Fu, Adrian V. Dalca, Bruce Fischl, Rodrigo Moreno & Malte Hoffmann
venue: IEEE ISBI 2025
abstract: "Recent machine-learning methods for linear and deformable registration have become state of the art across subjects, but they have demonstrated limitations when applied to longitudinal (within-subject) registration, where achieving precise alignment is critical. We propose a model optimised for longitudinal rigid brain registration, trained on synthetic within-subject pairs augmented with rigid and subtle non-linear transforms, that outperforms prior cross-subject networks on real follow-up scans within and across MRI contrasts."
paper: https://arxiv.org/abs/2501.13010
image: /assets/papers/figures/arxiv-2501.13010.png
---

**Presented at the IEEE International Symposium on Biomedical Imaging (ISBI) 2025.**

Work by [Jingru Fu](/people/jingru), Adrian V. Dalca, Bruce Fischl, [Rodrigo Moreno](/people/rodrigo), and Malte Hoffmann.

## Abstract

Rigid registration aims to determine the translations and rotations necessary to align features in a pair of images. While recent machine-learning methods have become state of the art for linear and deformable registration across subjects, they have demonstrated limitations when applied to longitudinal (within-subject) registration, where achieving precise alignment is critical.

Building on an existing framework for anatomy-aware, acquisition-agnostic affine registration, we propose a model optimised for longitudinal, rigid brain registration. By training the model with synthetic within-subject pairs augmented with rigid and subtle non-linear transforms, the model estimates more accurate rigid transforms than previous cross-subject networks and performs robustly on longitudinal registration pairs within and across magnetic resonance imaging (MRI) contrasts.

- Preprint: [arXiv:2501.13010](https://arxiv.org/abs/2501.13010)
- Code: [minnelab/longitudinal-rigid-registration](https://github.com/minnelab/longitudinal-rigid-registration)
