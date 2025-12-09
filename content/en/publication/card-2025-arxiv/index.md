---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'CARD: Correlation Aware Restoration with Diffusion'
subtitle: ''
summary: ''
authors:
  - Niki Nezakati
  - Arnab Ghosh
  - Amit Roy-Chowdhury
  - Vishwanath Saragadam
tags: []
categories: []
date: '2025-12-04'
lastmod: 2025-12-04T00:00:00Z
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
publishDate: '2025-12-04T00:00:00Z'
publication_types:
  - '3'  # 3 = preprint in Wowchemy

abstract: >
  <div class="justify-text">
  Denoising diffusion models have achieved state-of-the-art performance in image restoration by modeling the process as sequential denoising steps. However, most approaches assume independent and identically distributed (i.i.d.) Gaussian noise, while real-world sensors often exhibit spatially correlated noise due to readout mechanisms, limiting their practical effectiveness. We introduce Correlation Aware Restoration with Diffusion (CARD), a training-free extension of DDRM that explicitly handles correlated Gaussian noise. CARD first whitens the noisy observation, which converts the noise into an i.i.d. form. Then, the diffusion restoration steps are replaced with noise-whitened updates, which inherits DDRM's closed-form sampling efficiency while now being able to handle correlated noise. To emphasize the importance of addressing correlated noise, we contribute CIN-D, a novel correlated noise dataset captured across diverse illumination conditions to evaluate restoration methods on real rolling-shutter sensor noise. This dataset fills a critical gap in the literature for experimental evaluation with real-world correlated noise. Experiments on standard benchmarks with synthetic correlated noise and on CIN-D demonstrate that CARD consistently outperforms existing methods across denoising, deblurring, and super-resolution tasks.
  </div>

publication: '*Under Review*'

links:
  - name: PDF
    url: https://arxiv.org/pdf/2512.05268.pdf
  - name: DOI
    url: https://arxiv.org/abs/2512.05268
---
<style>
  .justify-text {
    text-align: justify;
  }
</style>
