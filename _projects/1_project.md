---
layout: page
title: SiT for Volumetric Medical Data
description: Self-supervised vIsion Transformer for Volumetric Medical Data (My Master's Thesis Project)
img: assets/img/project_SiT/CT_scan_poster.png
importance: 1
category: work
related_publications: 
---

You can find the repository for this project [here](https://github.com/AliAfs/SiT_3D)

##  Project Overview: 
---

This project is an adaptation and training of the SiT model, originally developed by [Sara Atito, Muhammad Awais, and Josef Kittler](https://github.com/Sara-Ahmed/SiT). The original repository provides a foundation for this project, and we have made modifications to suit our specific needs.

Link to the original repository: [Original Repository](https://github.com/Sara-Ahmed/SiT)
Link to the paper: [Paper](https://arxiv.org/abs/2104.03602)


## Objective:
---

In this project, our objective is to adapt and train a self-supervised vision transformer (SiT) for volumetric medical imaging. Leveraging a dataset of 3D CT scans, we aim to harness the power of vision transformers coupled with self-supervised learning (SSL) to learn a meaningful representation of the data. This learned representation can then be utilized to assess the quality of generated medical image data by measuring the distance between synthetic and real volumes in the learned feature space. By doing so, we hope to overcome the limitations of traditional evaluation metrics and provide a more reliable and domain-specific assessment of the generated medical images.


## Data:
---

For this study, we used data from the Lung Image Database Consortium (LIDC) Collection, hosted within the IDC repository. The LIDC database contains spiral CT lung scans with marked-up annotations of lesions, specifically designed to aid research on lung cancer detection and diagnosis.
The Imaging Data Commons (IDC) serves as a data repository and platform for sharing cancer imaging data, created as part of the Cancer Research Data Commons (CRDC) initiative by the National Cancer Institute (NCI) in the United States.

Data Source: [NCI Imaging Data Commons](https://aacrjournals.org/cancerres/article/81/16/4188/670283/NCI-Imaging-Data-CommonsNCI-Imaging-Data-Commons)




<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_SiT/SiT_architecture.png" title="Network Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of modified SiT model (Adopted from the original paper)
</div>