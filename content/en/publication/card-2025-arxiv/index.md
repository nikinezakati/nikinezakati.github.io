---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Broadband Wide Field of View Imaging with Computational Mirrors'
subtitle: ''
summary: ''
authors:
  - Vishwanath Saragadam
  - Niki Nezakati
  - Amit Roy-Chowdhury
  - Vivek Boominathan
tags: []
categories: []
date: '2026-08-01'
lastmod: 2026-08-01T00:00:00Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2026-08-01T00:00:00Z'
publication_types:
  - '3'  # 3 = preprint in Wowchemy

abstract: >
  <div class="justify-text">
  Traditional glass-based optics are typically optimized for narrow spectral bands, such as the visible (400–700nm) or shortwave infrared (1000–1800nm). While the emergence of VIS-SWIR sensors (400–1700nm) offers transformative potential, refractive optics struggle to focus this entire range simultaneously. Mirrors represent a promising achromatic alternative; however, they are often sidelined by field curvature, and offaxis aberrations. This paper introduces Computational Mirrors, a framework that enables high-resolution, wide-field-of-view imaging across the complete VIS-SWIR spectrum using a single sensor. Our method is built on the observation that distinct regions of the field of view reach focus at varying distances from the mirror. By capturing a minimal focal stack (2–4 images), we utilize a computational backend to recover a sharp, all-in-focus image. A key contribution of this work is SeidelConv, a novel, physics-inspired, spatially-varying point spread function (PSF) model designed to accurately characterize and correct the off-axis aberrations inherent in simple concave mirrors. We demonstrate the efficacy of our approach using a first-of-its-kind 50mm F/1 optical system equipped with a VIS-SWIR sensor. Our system produces sharp images across RGB, NIR, and SWIR wavelengths without requiring refocusing, revealing material details invisible within individual spectral bands. We further validate the scalability of our approach with a 100mm F/2 system optimized for long-range imaging.
  </div>

publication: '*The European Conference on Computer Vision (ECCV 2026)*'

links:
  - name: PDF
    url: https://arxiv.org/pdf/2605.00029
  - name: DOI
    url: https://doi.org/10.48550/arXiv.2605.00029
---
<style>
  .justify-text {
    text-align: justify;
  }
</style>
