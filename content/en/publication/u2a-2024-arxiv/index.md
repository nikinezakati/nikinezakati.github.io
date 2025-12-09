---
title: 'U2A: Unified Unimodal Adaptation for Robust and Efficient Multimodal Learning'
subtitle: ''
summary: ''
authors:
- Md Kaykobad Reza
- Niki Nezakati
- Ameya Patil
- Mashhour Solh
- M. Salman Asif
tags: []
categories: []
date: '2025-01-01'
lastmod: 2025-01-01T00:00:00-04:00
featured: false
draft: false

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
publishDate: '2025-01-01T00:00:00Z'
publication_types:
- '1'

abstract: >
  <div class="justify-text">
  Multimodal learning systems often rely on specialized architectures and complex training
  procedures to achieve strong performance. In this work, we introduce <em>Unified Unimodal
  Adaptation (U2A)</em>, a simple and efficient framework that jointly adapts pretrained unimodal
  encoders using low-rank adaptation (LoRA) for a wide range of multimodal tasks. U2A
  substantially reduces the number of trainable parameters and removes the need for strategies
  such as alternating updates, gradient manipulation, or unimodal pre-fine-tuning.

  To address scenarios with missing modalities during training or inference, we propose
  <em>Mask Tokens (MT)</em>, lightweight tokens that synthesize representations of unavailable
  modalities using information from the available ones. This unified mechanism avoids
  task-specific estimation modules or prompt-tuning techniques.

  Experiments across diverse datasets demonstrate that U2A matches or exceeds the performance
  of state-of-the-art methods in both full-modality and missing-modality settings, while being
  parameter-efficient and easy to train.
  </div>

publication: '*CoRR (arXiv preprint)*'
links:
- name: DOI
  url: https://www.arxiv.org/abs/2501.17823v1
- name: PDF
  url: https://www.arxiv.org/pdf/2501.17823v1.pdf
---

<style>
  .justify-text {
    text-align: justify;
  }
</style>
