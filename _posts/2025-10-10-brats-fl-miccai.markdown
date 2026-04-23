---
layout: post
title:  "BraTS-FL: Enhancing generalisation in brain-tumour segmentation via federated learning"
date:   2025-10-10
author: Simone Bendazzoli & Rodrigo Moreno
venue: BraTS @ MICCAI 2025
abstract: "A federated-learning approach to brain-tumour segmentation aimed at generalisation across heterogeneous cohorts — adult glioma, brain metastasis, meningioma, paediatric glioma, and a sub-Saharan African cohort. The method took first prize in the BraTS GoaT Task 7 subchallenge on generalisability across tumour types, confirming that federated training on site-specific nnU-Net models can close the domain gap between tumour subtypes and acquisition sources."
---

**Presented at the BraTS Workshop, MICCAI 2025. Awarded 1st prize in BraTS GoaT Task 7 on generalisability across tumour types.**

Work by [Simone Bendazzoli](/people/simone) and [Rodrigo Moreno](/people/rodrigo), built on the [MONet Bundle](https://github.com/minnelab/MONet-Bundle) infrastructure.

## Summary

The BraTS Generalisability-across-Tumours (GoaT) challenge at MICCAI 2025 asks segmentation methods to generalise across a family of radiologically and demographically heterogeneous tumour subtypes — adult glioma, brain metastasis, meningioma, paediatric glioma, and a sub-Saharan African cohort — often collected on different scanners and protocols.

BraTS-FL trains site-specific nnU-Net models through federated learning rather than pooled centralised training, so that each site's model is adapted to its local distribution while still benefiting from joint parameter updates. The approach was run within the MONet-Bundle framework. In the BraTS GoaT Task 7 subchallenge on generalisability across tumour types, BraTS-FL was awarded first prize, demonstrating that federated training is a competitive strategy for heterogeneous multi-cohort brain-tumour segmentation.

- Code: [minnelab/MONet-Bundle](https://github.com/minnelab/MONet-Bundle)
