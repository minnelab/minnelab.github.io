---
layout: page
title: MAIA
permalink: /maia/
hide_title: true
---
![MAIA](/assets/about/MAIA.png)
## MAIA: Bridging the Gap Between Medical AI Research and Clinical Adoption

**MAIA** is a medical AI platform developed within **MINNELab** by **Simone Bendazzoli**. It was designed to address a critical challenge in medical AI: bridging the gap between research innovation and clinical adoption.

In medical AI, isolating individual stages of the development process often **obstructs the advancement of impactful research**. Fragmented workflows limit the potential for iterative improvement, validation, and — critically — **translation into clinically usable solutions**.

For example, a lung nodule detection model developed in isolation, without collaboration with radiologists or IT and infrastructure planning, might perform well in a lab setting but fail to integrate with hospital systems like PACS. Without clinical input and a continuous feedback loop, even promising AI models may remain unusable, rendering the research effort ineffective.

To overcome these challenges, there is a growing need for a **shared, open, and collaborative environment**. Such a platform allows knowledge, models, and algorithms to be freely exchanged between research groups and institutions, promoting iterative evaluation and collective advancement.

---

### Introducing MAIA

With this vision, **MAIA** was developed as a **medical AI platform** built to:

- Promote collaboration across diverse areas of expertise  
- Integrate all stages of the AI lifecycle within a **unified environment**  
- Allow **open sharing of models and algorithms** between researchers  
- Facilitate **clinical validation** through direct integration with hospital infrastructures  

![MAIA Platform Diagram](https://raw.githubusercontent.com/kthcloud/maia/master/dashboard/image/README/MAIA_Workspace.png)
---

### Key Features

MAIA supports the **complete AI lifecycle**, incorporating:

- **Active learning** with human-in-the-loop refinement  
- Integration of deep learning models with **PACS** for automatic segmentation of incoming DICOM images  
- **Federated learning** across institutions, enabling collaborative model improvement without sharing patient data  

By connecting researchers, clinicians, and infrastructure in a single platform, MAIA bridges the critical gap between **medical AI research and clinical adoption**, accelerating the translation of innovative models into solutions that truly impact patient care.

---
### Current Usage

MAIA has been the **main research platform** at KTH in the **Division of Biomedical Imaging** for the past two years, serving over **80 PhD students, Master students, postdocs, and participants in master-level courses**.  

On the clinical side, a deployment at the **Radiology Department of Karolinska University Hospital** is enabling **closer collaboration between AI researchers and radiologists**. MAIA is currently used for projects including:  

- **MRI bone metastasis segmentation**  
- **Brain MRI metastasis segmentation**  

In these projects, AI researchers develop models directly from raw **DICOM images** imported into the MAIA platform, while radiologists play a key role in several steps, including **active learning** and **smart annotation** to refine predicted lesions. This integrated workflow ensures that AI models are both technically robust and clinically relevant.

---
### Current and Future Directions

We are exploring the integration of **large language models (LLMs)** into radiology workflows to enable **automatic report generation** directly from medical images and corresponding segmentation masks as **ROIs**.  

This will allow a seamless pipeline from image acquisition, AI-based analysis, segmentation, and finally to structured clinical reporting — helping to further accelerate clinical adoption of AI.  

We welcome collaborations — if you are interested in contributing or exploring these capabilities, **feel free to reach out**!

---
### Publications

Our work about **MAIA** is available as an open-access preprint on arXiv:
<div style="text-align: center; display: inline-flex; align-items: center; gap: 10px;">
  <a href="https://arxiv.org/abs/2507.19489">
    <img src="https://info.arxiv.org/brand/images/brand-logo-black.jpg" alt="arXiv" width="80">
  </a>
  <a href="https://arxiv.org/abs/2507.19489" style="text-decoration: none; color: inherit; font-weight: bold; font-size: 1rem;">
    MAIA: A Collaborative Medical AI Platform for Integrated Healthcare Innovation
  </a>
</div>


---

### Learn More

- <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/github.svg" alt="GitHub" width="20" style="vertical-align:middle"> **GitHub:** [https://github.com/minnelab/MAIA](https://github.com/minnelab/MAIA)  
- <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/readthedocs.svg" alt="Documentation" width="20" style="vertical-align:middle"> **Documentation:** [https://minnelab.github.io/maia/](https://maia-toolkit.readthedocs.io)  
- <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/internetexplorer.svg" alt="Web" width="20" style="vertical-align:middle"> **Research Platform Webpage at KTH:** [https://maia.app.cloud.cbh.kth.se](https://maia.app.cloud.cbh.kth.se)  
- <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/slides.svg" alt="Workshop" width="20" style="vertical-align:middle"> **Workshop Slides and Material for AIDA TechDays event:** [https://minnelab.github.io/MAIA-AIDA-TechDays-Workshop/](https://minnelab.github.io/MAIA-AIDA-TechDays-Workshop/)  

