---
layout: page
title: MAIA
permalink: /maia/
eyebrow: Platform
lede: >-
  MAIA is a medical AI platform developed within MINNE Lab by Simone Bendazzoli,
  built to close the gap between medical-AI research and clinical adoption.
---

<figure class="maia-figure maia-figure--cover">
  <img src="https://raw.githubusercontent.com/SimoneBendazzoli93/MAIA-AIDA-TechDays-Workshop/main/img/Cover_Aurora_Snow-Night.png" alt="MAIA platform cover artwork" />
</figure>

## The problem

In medical AI, isolating individual stages of the development process often obstructs the advancement of impactful research. Fragmented workflows limit iterative improvement, validation, and — critically — translation into clinically usable solutions.

A lung-nodule detection model developed in isolation, without collaboration with radiologists or IT and infrastructure planning, might perform well in a lab but fail to integrate with hospital systems like PACS. Without clinical input and a continuous feedback loop, even promising AI models may remain unusable, rendering the research effort ineffective.

What's needed is a **shared, open, collaborative environment** — one in which knowledge, models, and algorithms can be freely exchanged between research groups and institutions, and iteratively evaluated against clinical reality.

## What MAIA does

MAIA is a medical-AI platform built to:

- Promote collaboration across diverse areas of expertise.
- Integrate all stages of the AI lifecycle within a unified environment.
- Allow open sharing of models and algorithms between researchers.
- Facilitate clinical validation through direct integration with hospital infrastructure.

<figure class="maia-figure">
  <img src="https://raw.githubusercontent.com/kthcloud/maia/master/dashboard/image/README/MAIA_Workspace.png" alt="Diagram of the MAIA platform workspace" />
  <figcaption>The MAIA workspace — researchers, clinicians, and infrastructure connected in a single environment.</figcaption>
</figure>

## Key features

MAIA supports the complete AI lifecycle:

- **Active learning** with human-in-the-loop refinement.
- **PACS integration** — deep-learning models connected directly to the clinical imaging archive for automatic segmentation of incoming DICOM images.
- **Federated learning** across institutions, enabling collaborative model improvement without sharing patient data.

By connecting researchers, clinicians, and infrastructure in a single platform, MAIA bridges the gap between medical-AI research and clinical adoption.

## Current usage

MAIA has been the main research platform at KTH in the Division of Biomedical Imaging for the past two years, serving over **80 PhD students, master students, postdocs, and participants in master-level courses**.

On the clinical side, a deployment at the Radiology Department of **Karolinska University Hospital** is enabling closer collaboration between AI researchers and radiologists. Current projects include:

- MRI bone-metastasis segmentation.
- Brain-MRI metastasis segmentation.

AI researchers develop models directly from raw DICOM images imported into the MAIA platform, while radiologists contribute active learning and smart annotation to refine predicted lesions. The integrated workflow ensures that models are both technically robust and clinically relevant.

## Ongoing directions

We are exploring the integration of **large language models** into radiology workflows to enable automatic report generation directly from medical images and corresponding segmentation masks as ROIs — a seamless pipeline from image acquisition to AI-based analysis, segmentation, and structured clinical reporting.

We welcome collaborations. If you are interested in contributing or exploring these capabilities, please reach out.

## Publication

<div class="maia-pub">
  <span class="eyebrow">NPJ Artificial Intelligence · open access</span>
  <h3 class="maia-pub__title">
    <a href="https://www.nature.com/articles/s44387-025-00042-6" target="_blank" rel="noopener">MAIA: A Collaborative Medical AI Platform for Integrated Healthcare Innovation</a>
  </h3>
  <a class="maia-pub__link" href="https://www.nature.com/articles/s44387-025-00042-6" target="_blank" rel="noopener">Read on nature.com &rarr;</a>
</div>

## Learn more

<ul class="maia-links">
  <li><span class="maia-links__label">GitHub</span><a href="https://github.com/minnelab/MAIA" target="_blank" rel="noopener">github.com/minnelab/MAIA</a></li>
  <li><span class="maia-links__label">Documentation</span><a href="https://maia-toolkit.readthedocs.io" target="_blank" rel="noopener">maia-toolkit.readthedocs.io</a></li>
  <li><span class="maia-links__label">KTH research platform</span><a href="https://maia.app.cloud.cbh.kth.se" target="_blank" rel="noopener">maia.app.cloud.cbh.kth.se</a></li>
  <li><span class="maia-links__label">AIDA TechDays workshop</span><a href="https://minnelab.github.io/MAIA-AIDA-TechDays-Workshop/" target="_blank" rel="noopener">minnelab.github.io/MAIA-AIDA-TechDays-Workshop</a></li>
</ul>
