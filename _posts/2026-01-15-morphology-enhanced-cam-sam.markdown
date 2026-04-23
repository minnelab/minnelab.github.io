---
layout: post
title:  "Morphology-enhanced CAM-guided SAM for weakly supervised breast lesion segmentation"
date:   2026-01-15
author: "X. Yue, Q. Zhao, X. Liu, J. Li, J. Bai, C. Song, S. Liu, Rodrigo Moreno, Zhikai Yang, et al."
venue: Biomedical Signal Processing and Control
abstract: "Ultrasound imaging plays a critical role in the early detection of breast cancer. We present a novel framework for weakly supervised lesion segmentation in early breast ultrasound images using morphological enhancement and class-activation-map (CAM)-guided localisation, followed by the Segment Anything Model (SAM) for detailed segmentation. The approach does not require pixel-level annotation, reducing data-annotation cost."
paper: https://arxiv.org/abs/2311.11176
image: /assets/papers/figures/arxiv-2311.11176.png
---

**Published in Biomedical Signal Processing and Control (2026).**

Co-authored by [Rodrigo Moreno](/people/rodrigo) and [Zhikai Yang](/people/zhikai), with a team led by Xin Yue.

## Abstract

Ultrasound imaging plays a critical role in the early detection of breast cancer. Accurate identification and segmentation of lesions are essential steps in clinical practice, requiring methods to assist physicians in lesion segmentation. However, ultrasound lesion-segmentation models based on supervised learning require extensive manual labelling, which is both time-consuming and labour-intensive.

In this study, we present a novel framework for weakly supervised lesion segmentation in early breast-ultrasound images. Our method uses morphological enhancement and class-activation-map (CAM)-guided localisation. Finally, we employ the Segment Anything Model (SAM), a computer vision foundation model, for detailed segmentation. This approach does not require pixel-level annotation, thereby reducing the cost of data annotation.

The performance of our method is comparable to supervised-learning methods that require manual annotations, achieving a Dice score of 74.39% and outperforming comparative supervised models in terms of Hausdorff distance on the BUSI dataset. These results demonstrate that our framework effectively integrates weakly supervised learning with SAM, providing a promising solution for breast-cancer image analysis.

- Preprint: [arXiv:2311.11176](https://arxiv.org/abs/2311.11176)
- Code: [github.com/YueXin18/MorSeg-CAM-SAM](https://github.com/YueXin18/MorSeg-CAM-SAM)
