---
layout: post
title:  "3D breast ultrasound image classification using 2.5D deep learning"
date:   2024-05-15
author: Zhikai Yang, Tianyu Fan, Örjan Smedby & Rodrigo Moreno
venue: IWBI 2024
abstract: "3D breast ultrasound is a radiation-free and effective imaging technology for breast-tumour diagnosis, but it is time-consuming to check compared to mammograms. We propose a 2.5D deep-learning–based classification system: a pre-trained STU-Net is fine-tuned to segment the tumour in 3D, after which DenseNet-121 is fine-tuned on the 10 slices with the largest tumoral area plus their neighbours. Evaluated on the TDSC-ABUS MICCAI Challenge 2023 dataset, the method outperforms 3D CNNs and radiomics baselines."
paper: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13174/131741R/3D-breast-ultrasound-image-classification-using-25D-deep-learning/10.1117/12.3025534.short
---

**Presented at the 17th International Workshop on Breast Imaging (IWBI 2024), Chicago.**

Work by [Zhikai Yang](/people/zhikai), Tianyu Fan, Örjan Smedby, and [Rodrigo Moreno](/people/rodrigo).

## Abstract

3D breast ultrasound is a radiation-free and effective imaging technology for breast-tumour diagnosis, but checking the 3D volume is time-consuming compared to mammograms.

We propose a 2.5D deep-learning–based breast-ultrasound tumour classification system. First, the pre-trained STU-Net is fine-tuned and used to segment the tumour in 3D. Then, DenseNet-121 is fine-tuned for classification using the 10 slices with the largest tumoral area and their adjacent slices.

The Tumour Detection, Segmentation and Classification on Automated 3D Breast Ultrasound (TDSC-ABUS) MICCAI Challenge 2023 dataset was used to train and validate the proposed method. Compared to a 3D convolutional neural network and radiomics baselines, the proposed method achieves better performance.

- Paper: [SPIE Digital Library — DOI 10.1117/12.3025534](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13174/131741R/3D-breast-ultrasound-image-classification-using-25D-deep-learning/10.1117/12.3025534.short)
