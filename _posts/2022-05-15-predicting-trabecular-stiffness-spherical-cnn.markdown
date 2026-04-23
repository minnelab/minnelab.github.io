---
layout: post
title:  "Predicting the trabecular bone apparent stiffness tensor with spherical convolutional neural networks"
date:   2022-05-15
author: Fabian Sinzinger, Jip van Kerkvoorde, Dieter H. Pahr & Rodrigo Moreno
venue: Bone Reports
abstract: "The apparent stiffness tensor characterises trabecular-bone quality. We train spherical convolutional neural networks (SphCNNs) to estimate this tensor from micro-CT data. Information on the edges, trabecular thickness, and spacing is summarised as functions on the unit sphere used as inputs, and the resulting dimensionality reduction allows training on relatively small datasets. Predictions are compared against micro–finite-element (μFE) reference stiffness and fourth-order fabric-tensor models; combining edges and trabecular thickness yields significant accuracy improvements over the fabric-tensor baseline."
paper: https://doi.org/10.1016/j.bonr.2022.101179
---

**Published in Bone Reports (2022).**

Work by [Fabian Sinzinger](/people/fabian), Jip van Kerkvoorde, Dieter H. Pahr, and [Rodrigo Moreno](/people/rodrigo).

## Abstract

The apparent stiffness tensor is relevant for characterising trabecular-bone quality. Previous studies have used morphology–stiffness relationships for estimating the apparent stiffness tensor. This paper proposes to train **spherical convolutional neural networks (SphCNNs)** to estimate this tensor.

Information on the edges, trabecular thickness, and spacing is summarised in functions on the unit sphere that are used as inputs for the SphCNNs. The concomitant dimensionality reduction makes it possible to train neural networks on relatively small datasets. The predicted tensors were compared to the stiffness tensors computed using the micro–finite-element method (μFE), considered as the gold standard, and to models based on fourth-order fabric tensors. Combining edges and trabecular thickness yields significant improvements in accuracy compared to the methods based on fourth-order fabric tensors. SphCNNs are promising for replacing the more expensive μFE stiffness estimations.

- Paper: [Bone Reports — ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2352187222000146)
