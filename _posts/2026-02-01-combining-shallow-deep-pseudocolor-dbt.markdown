---
layout: post
title:  "Combining shallow and deep neural networks on pseudo-colour enhanced images for digital breast tomosynthesis lesion classification"
date:   2026-02-01
author: Zhikai Yang, Yichen Liu, Örjan Smedby & Rodrigo Moreno
venue: Frontiers in Digital Health
abstract: "The classification of lesion types in Digital Breast Tomosynthesis (DBT) images is crucial for the early diagnosis of breast cancer. However, the task remains challenging due to the complexity of breast tissue and the subtle nature of lesions. We propose a novel DBT Dual-Net architecture comprising two complementary neural network branches that extract both low-level and high-level features, combined with pseudo-colour enhancement and inter-slice majority voting."
---

**Published in Frontiers in Digital Health (2026).**

Work by [Zhikai Yang](/people/zhikai), Yichen Liu, Örjan Smedby, and [Rodrigo Moreno](/people/rodrigo).

## Abstract

**Introduction.** The classification of lesion types in Digital Breast Tomosynthesis (DBT) images is crucial for the early diagnosis of breast cancer. However, the task remains challenging due to the complexity of breast tissue and the subtle nature of lesions. To alleviate radiologists' workload, computer-aided diagnosis (CAD) systems have been developed. The breast lesion regions vary in size and complexity, which leads to performance degradation.

**Methods.** To tackle this problem, we propose a novel DBT Dual-Net architecture comprising two complementary neural network branches that extract both low-level and high-level features. By fusing different-level feature representations, the model can better capture subtle structure. Furthermore, we introduced a pseudo-colour enhancement procedure to improve the visibility of lesions on DBT. Moreover, most existing DBT classification studies rely on two-dimensional (2D) slice-level analysis, neglecting the rich three-dimensional (3D) spatial context within DBT volumes. To address this limitation, we used majority voting for image-level classification from predictions across slices.

**Results.** We evaluated our method on a public DBT dataset and compared its performance with several existing classification approaches. The results showed that our method outperforms baseline models.

**Discussion.** The use of pseudo-colour enhancement, extracting high- and low-level features, and inter-slice majority voting are effective for lesion classification in DBT.

- Code: [github.com/xiaoerlaigeid/DBT-Dual-Net](https://github.com/minnelab/DBT-Dual-Net-Classification)
