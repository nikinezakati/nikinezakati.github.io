---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'TDiff: Thermal Plug-And-Play Prior with Patch-Based Diffusion'
subtitle: ''
summary: ''
authors:
- Piyush Dashpute
- Niki Nezakati
- Wolfgang Heidrich
- Vishwanath Saragadam
tags: []
categories: []
date: '2025-11-04'
lastmod: 2025-11-04T19:57:59-04:00
featured: false
draft: false

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
publishDate: '2025-11-04T23:57:59.485338Z'
publication_types:
- '1'

abstract: '<div class="justify-text">  
Thermal images captured by low-cost sensors often suffer from low resolution, fixed pattern noise, and other localized degradations. Compounding this challenge, available thermal imaging datasets are typically small and lack diversity.  
<br><br>
To address these limitations, we introduce <em>TDiff</em>, a plug-and-play thermal restoration framework built on a patch-based diffusion prior. Our approach exploits the inherently local structure of thermal distortions by training diffusion models on small patches, then restoring full-resolution images by denoising overlapping patches and blending them using smooth spatial windowing.  
<br><br>
To our knowledge, this is the first diffusion-based patch prior designed specifically for thermal imagery and applicable across multiple restoration tasks. Experiments on denoising, super-resolution, and deblurring demonstrate strong performance on both simulated and real thermal datasets, establishing TDiff as a unified and effective pipeline for thermal image restoration.  
</div>'

publication: '*Proceedings of the 2025 ACM International Workshop on Thermal Sensing and Computing*'
links:
- name: PDF
  url: https://dl.acm.org/doi/pdf/10.1145/3737905.3769286
- name: DOI
  url: https://dl.acm.org/doi/abs/10.1145/3737905.3769286
---

<style>
  .justify-text {
    text-align: justify;
  }
</style>
