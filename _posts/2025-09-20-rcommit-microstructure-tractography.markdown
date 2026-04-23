---
layout: post
title:  "Randomly COMMITting: iterative convex optimisation for microstructure-informed tractography"
date:   2025-09-20
author: Sanna Persson, Xiaoyan Wan & Rodrigo Moreno
venue: International Workshop on Computational Diffusion MRI (CDMRI) 2025
abstract: "Tractography is extensively utilised in brain-connectivity studies using diffusion MRI, but anatomically implausible and redundant streamlines are a significant challenge. We introduce rCOMMIT, a tractogram filtering method that extends COMMIT by assessing each streamline in multiple randomised tractogram compositions to estimate an acceptance rate per streamline; this rate is used as a pseudo-label to train neural-network classifiers in a semi-supervised manner, reducing computational cost."
paper: https://link.springer.com/chapter/10.1007/978-3-031-86920-4_5
---

**Presented at the Computational Diffusion MRI workshop (CDMRI) 2025.**

Work by [Sanna Persson](/people/sanna), Xiaoyan Wan, and [Rodrigo Moreno](/people/rodrigo).

## Abstract

Tractography is extensively utilised in brain-connectivity studies using diffusion magnetic resonance imaging (dMRI) data. However, the presence of anatomically implausible and redundant streamlines is a significant challenge. Several tractogram filtering methods have been developed to eliminate false-positive streamlines and address these issues.

We introduce a tractography filtering method — **Randomised COMMIT (rCOMMIT)** — based on the Convex Optimisation Modelling for Microstructure Informed Tractography (COMMIT) filtering method. The method aims to mitigate the biases of COMMIT for individual streamlines by assessing each streamline in multiple tractogram compositions to estimate an acceptance rate per streamline. In order to reduce the computational cost, this acceptance rate is used to create pseudo-labels that are used to train neural-network classifiers in a semi-supervised manner.

- Paper: [link.springer.com](https://link.springer.com/chapter/10.1007/978-3-031-86920-4_5)
- Code: [minnelab/rCOMMIT](https://github.com/minnelab/rCOMMIT)
