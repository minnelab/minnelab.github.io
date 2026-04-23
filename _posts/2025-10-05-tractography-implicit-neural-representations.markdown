---
layout: post
title:  "Tractography on implicit neural representations of diffusion MRI"
date:   2025-10-05
author: Sanna Persson, Fabian L. Sinzinger & Rodrigo Moreno
venue: International Society for Tractography (IST) 2025
abstract: "Diffusion-weighted imaging is often constrained by scan time, producing sparsely and non-uniformly sampled Q-space that hinders accurate signal modelling and affects downstream tractography. We represent the raw DWI signal with implicit neural representations (INRs) to address these limitations, and assess the effect of INR-based reconstructions on streamline tractography as a practical use case."
---

**Presented at the first International Society for Tractography (IST) conference, 2025.**

Work by [Sanna Persson](/people/sanna), [Fabian Sinzinger](/people/fabian), and [Rodrigo Moreno](/people/rodrigo).

## Abstract

Diffusion-weighted imaging (DWI) acquisition is often constrained by scan time, producing sparsely and non-uniformly sampled Q-space. These limitations hinder accurate modelling of the diffusion signal and affect downstream tractography.

We propose representing the raw DWI signal with implicit neural representations (INRs): continuous, coordinate-based neural networks that provide a resolution-independent description of the orientation-distribution field rather than a fixed grid-sampled volume. Since INR-based DWI reconstructions only approximate the measured signal, we assess their effect on a practical downstream task — streamline tractography — to quantify when the continuous representation gains or loses relative to conventional reconstructions.
