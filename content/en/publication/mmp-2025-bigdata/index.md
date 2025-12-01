---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'MMP: Towards robust multi-modal learning with masked modality projection'
subtitle: ''
summary: ''
authors:
  - Niki Nezakati
  - Md Kaykobad Reza
  - Ameya Patil
  - Mashhour Solh
  - M Salman Asif
tags: []
categories: []
date: '2025-11-23'
lastmod: 2025-11-23T00:00:00Z
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
publishDate: '2025-11-23T00:00:00Z'
publication_types:
  - '3'  # 3 = preprint in Wowchemy

abstract: >
  <div class="justify-text">
  Multimodal learning seeks to combine data from multiple input sources to enhance the performance of different
  downstream tasks. In real-world scenarios, performance can degrade substantially if some input modalities are
  missing. Existing methods that can handle missing modalities involve custom training or adaptation steps for
  each input modality combination. These approaches are either tied to specific modalities or become computationally
  expensive as the number of input modalities increases. In this paper, we propose Masked Modality Projection (MMP),
  a method designed to train a single model that is robust to any missing modality scenario. We achieve this by
  randomly masking a subset of modalities during training and learning to project available input modalities to
  estimate the tokens for the masked modalities. This approach enables the model to effectively learn to leverage the
  information from the available modalities to compensate for the missing ones, enhancing missing modality robustness.
  We conduct a series of experiments with various baseline models and datasets to assess the effectiveness of this
  strategy. Experiments demonstrate that our approach improves robustness to different missing modality scenarios,
  outperforming existing methods designed for missing modalities or specific modality combinations.
  </div>

publication: '*Proceedings of the 2025 IEEE International Conference on Big Data*'

links:
  - name: PDF
    url: https://arxiv.org/abs/2410.03010
  - name: DOI
    url: https://arxiv.org/pdf/2410.03010.pdf
---
<style>
  .justify-text {
    text-align: justify;
  }
</style>
