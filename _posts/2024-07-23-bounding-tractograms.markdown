---
layout: post
title:  "Bounding tractogram redundancy"
date:   2024-07-23
author: Sanna Persson & Rodrigo Moreno
abstract: "Proposes a principled definition of redundancy in diffusion MRI tractograms and an algorithm to remove superfluous streamlines while preserving anatomical coverage and connectivity. Demonstrates on public datasets that large fractions of streamlines can be pruned without degrading downstream analyses, improving storage and computation."
image: /assets/papers/bounding_tractography.jpg
---
**Published in Frontiers in Neuroscience**

Paper link: <https://www.frontiersin.org/articles/10.3389/fnins.2024.1403804/full>




Introduction: In tractography, redundancy poses a significant challenge, often resulting in tractograms that include anatomically implausible streamlines or those that fail to represent the brain's white matter architecture accurately. Current filtering methods aim to refine tractograms by addressing these issues, but they lack a unified measure of redundancy and can be computationally demanding.

Methods: We propose a novel framework to quantify tractogram redundancy based on filtering tractogram subsets without endorsing a specific filtering algorithm. Our approach defines redundancy based on the anatomical plausibility and diffusion signal representation of streamlines, establishing both lower and upper bounds for the number of false-positive streamlines and the tractogram redundancy.

Results: We applied this framework to tractograms from the Human Connectome Project, using geometrical plausibility and statistical methods informed by the streamlined attributes and ensemble consensus. Our results establish bounds for the tractogram redundancy and the false-discovery rate of the tractograms.

Conclusion: This study advances the understanding of tractogram redundancy and supports the refinement of tractography methods. Future research will focus on further validating the proposed framework and exploring tractogram compression possibilities.