---
layout: post
title:  "Unsupervised domain adaptation for pediatric brain-tumour segmentation"
date:   2024-10-01
author: Jingru Fu, Simone Bendazzoli, Örjan Smedby & Rodrigo Moreno
venue: ADSMI @ MICCAI 2024
abstract: "Significant advances have been made in automatic segmentation of adult gliomas, but performance degrades on paediatric glioma due to imaging and clinical differences. Manual annotations in children are scarce. We propose DA-nnUNet, which performs unsupervised domain adaptation from adult glioma (source) to paediatric glioma (target) by adding a domain classifier with a gradient-reversal layer to nnU-Net — achieving ~32% better Dice and ~20-point lower 95th-percentile Hausdorff in the tumour-core region without using any paediatric annotations."
paper: https://arxiv.org/abs/2406.16848
image: /assets/papers/figures/arxiv-2406.16848.png
---

**Presented at the ADSMI workshop, MICCAI 2024.**

Work by [Jingru Fu](/people/jingru), [Simone Bendazzoli](/people/simone), Örjan Smedby, and [Rodrigo Moreno](/people/rodrigo).

## Abstract

Significant advances have been made toward building accurate automatic segmentation models for adult gliomas. However, the performance of these models often degrades when applied to paediatric glioma due to their imaging and clinical differences (domain shift). Obtaining sufficient annotated data for paediatric glioma is typically difficult because of its rare nature. Also, manual annotations are scarce and expensive.

In this work, we propose **Domain-Adapted nnU-Net (DA-nnUNet)** to perform unsupervised domain adaptation from adult glioma (source domain) to paediatric glioma (target domain). Specifically, we add a domain classifier connected with a gradient-reversal layer (GRL) to a backbone nnU-Net. Once the classifier reaches a very high accuracy, the GRL is activated with the goal of transferring domain-invariant features from the classifier to the segmentation model while preserving segmentation accuracy on the source domain. The accuracy of the classifier slowly degrades to chance levels. No annotations are used in the target domain.

The method is compared to 8 different supervised models using BraTS-Adult glioma (N=1251) and BraTS-PED glioma data (N=99). The proposed method shows notable performance enhancements in the tumour core (TC) region compared to the model that only uses adult data: ~32% better Dice scores and ~20 better 95th-percentile Hausdorff distances. Moreover, our unsupervised approach shows no statistically significant difference compared to the practical upper-bound model using manual annotations from both datasets in the TC region.

- Preprint: [arXiv:2406.16848](https://arxiv.org/abs/2406.16848)
- Code: [minnelab/DA_nnUNet](https://github.com/minnelab/DA_nnUNet)
