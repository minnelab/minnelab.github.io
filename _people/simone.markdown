---
layout: person
title: 'Simone Bendazzoli'
category: people
permalink: /people/simone
image: /assets/people/simben.jpg
position: 'PhD student'
status: 'current'
---

![Simone](/assets/people/simben.jpg){:class="people-profile-image"}

## About me

I began my PhD in October 2020, focusing on medical image processing using deep learning — a field that has rapidly evolved but still faces challenges in real-world clinical adoption. Over the years, working at the intersection of AI research and medical practice has made me reflect deeply on how difficult it remains to integrate the models we develop into clinical workflows in a transparent, reproducible, and scalable way.

This realization led me to design and build MAIA, an open-source Medical AI platform that promotes collaboration and reproducibility in medical imaging research. MAIA integrates Kubernetes, MONAI, and the MONAI Bundle format to simplify deploying, configuring, and updating AI models in distributed research environments. It integrates essential tools such as 3D Slicer, OHIF Viewer, Orthanc, XNAT, and MLFlow, forming a cohesive ecosystem for annotation, model training, active learning, and refinement.

Through this work, I aim to bridge the gap between AI innovation and clinical implementation by providing researchers and clinicians with the infrastructure they need to collaborate effectively.

As I approach the defense of my PhD thesis on November 27, 2025, my focus remains on advancing open, modular, and transparent medical AI systems that can empower the community and accelerate the safe translation of research into practice.

When I’m not coding or experimenting with new infrastructure designs, I’m usually out running — my favorite way to clear my mind, stay focused, and find inspiration for the next challenge. Follow my running activities on [Strava](https://www.strava.com/athletes/107384738)

## Research

### Lung Vessel Connectivity Map as Anatomical Prior Knowledge for Deep Learning–Based Lung Lobe Segmentation  
**Simone Bendazzoli**, Emelie Bäcklin, Örjan Smedby, Birgitta Janerot-Sjöberg, Bryan Connolly, Chunliang Wang  
*J. Med. Imaging, 2024 — [PMID: 38988990](https://pubmed.ncbi.nlm.nih.gov/38988990/) | [DOI: 10.1117/1.JMI.11.4.044001](https://doi.org/10.1117/1.JMI.11.4.044001)*  

This study explores how **anatomical priors** can enhance deep learning segmentation of lung lobes from chest CT. We introduced a **Lung Vessel Connectivity (LVC) map**, encoding the vascular structure of the lungs, and integrated it into three **nnU-Net** variants: standard, multitask, and cascade models.  

Including the LVC map improved segmentation accuracy, especially at challenging interlobar boundaries and in expiration scans, while also improving **robustness in pathological cases** such as COVID-19. The results demonstrate that embedding anatomical knowledge into model design can enhance both **accuracy and generalization**, promoting more **clinically reliable** segmentation systems

---

### Designing Radio-dynamics Features for pCR Prediction in Breast DCE-MRI  
**Simone Bendazzoli**, Mehdi Astaraki, Yanbo Li, Rodrigo Moreno, Örjan Smedby, Hong Lu, Chunliang Wang  
*KTH Royal Institute of Technology, Karolinska Institutet, Tianjin Medical University Cancer Hospital*  

This work introduces a novel family of imaging biomarkers, **radio-dynamics features**, designed to improve **pathological complete response (pCR)** prediction in breast cancer patients undergoing **neoadjuvant chemotherapy (NAC)**. These features are derived from **dynamic contrast-enhanced MRI (DCE-MRI)** and aim to capture the **temporal dynamics** of tumor enhancement beyond what traditional radiomics can represent.  

The study implemented a full machine learning pipeline for **feature extraction, selection, and classification**, evaluated on 80 subjects using 5-fold cross-validation. Results showed that radio-dynamics features outperformed conventional radiomics, particularly in ensemble models, demonstrating their potential for more accurate and physiologically meaningful prediction of treatment response.  

The **source code and pipeline** are openly available at: [https://github.com/minnelab/Hive_ML](https://github.com/minnelab/Hive_ML)  

