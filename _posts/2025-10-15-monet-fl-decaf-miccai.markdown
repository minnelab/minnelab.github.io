---
layout: post
title:  "MONet-FL: Extending nnU-Net with MONAI for clinical federated learning"
date:   2025-10-15
author: Simone Bendazzoli, Mehdi Astaraki, Antonios Tzortzakakis, Andréas Abrahamsson, Björn Engelbrekt Wahlin, Sofia Brunori, Maria Holstensson & Rodrigo Moreno
venue: DeCaF @ MICCAI 2025
abstract: "While nnU-Net's success as a state-of-the-art tool for medical image segmentation has driven its adoption as a baseline, its limited portability and lack of clinical integration have limited broader deployment in real-world healthcare workflows. The MONet Bundle addresses these challenges by extending nnU-Net within the MONAI ecosystem, providing a modular benchmarking tool for federated learning that is directly compatible with downstream clinical operations such as model deployment, active learning, and DICOM-based PACS integration."
paper: https://link.springer.com/chapter/10.1007/978-3-032-05663-4_10
---

**Presented at DeCaF (Distributed and Collaborative Federated Learning) 2025, MICCAI.**

Work by [Simone Bendazzoli](/people/simone), Mehdi Astaraki, Antonios Tzortzakakis, Andréas Abrahamsson, Björn Engelbrekt Wahlin, Sofia Brunori, Maria Holstensson, and [Rodrigo Moreno](/people/rodrigo).

## Abstract

While nnU-Net's success as a state-of-the-art tool for medical image segmentation has driven its adoption as a baseline, its limited portability and lack of clinical integration have limited broader deployment in real-world healthcare workflows. The MONet Bundle addresses these challenges by extending nnU-Net within the MONAI ecosystem, providing a modular benchmarking tool for federated learning that is directly compatible with downstream clinical operations such as model deployment, active learning, and DICOM-based PACS integration.

MONet enables federated training across distributed clinical datasets while maintaining standardised preprocessing and harmonised workflows. Its flexibility is validated on two representative segmentation tasks: lymphoma lesion segmentation in PET-CT and brain-tumour segmentation from the BraTS challenge.

- Paper: [link.springer.com](https://link.springer.com/chapter/10.1007/978-3-032-05663-4_10)
- Code: [minnelab/MONet-Bundle](https://github.com/minnelab/MONet-Bundle)
