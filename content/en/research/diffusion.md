---
title: ""
date: 2025-11-12
slug: diffusion
share: false
commentable: false
editable: false
---

<div class="project-cards">
<div class="project-card">
  <h3>Diffusion-Based Image Restoration</h3>
  <p>
    Real-world imaging systems introduce complex degradations that standard diffusion models are not designed to handle. My work focuses on developing diffusion-based restoration methods that remain reliable under realistic sensor conditions, including spatially correlated noise, low resolution, and thermal imaging artifacts. I explore principled transformations such as whitening to convert correlated sensor noise into forms compatible with diffusion sampling, enabling accurate restoration without retraining. I also design patch-based diffusion frameworks that learn local thermal priors from small image regions and use overlapping patch denoising with smooth blending to reconstruct full-resolution outputs. Across denoising, super-resolution, and deblurring, these approaches improve robustness and generalization for both RGB and thermal images and aim to make diffusion-based restoration practical for real-world deployment.
  </p>
</div>
</div>


<style>
.project-cards {
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
  margin-top: 1.5rem;
}
.project-card {
  border: 1px solid #e0e0e0;
  border-radius: 10px;
  padding: 0.9rem 1.4rem;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
  background: #fff;
  width: 100%;
}
.project-card h3 {
  margin: 0 0 0.75rem 0;
}
.project-card p {
  margin: 0;
  text-align: justify;
}
.dark .project-card {
  background: #1e1e1e;
  border-color: #3a3a3a;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.4);
}
.dark .project-card h3,
.dark .project-card p {
  color: #f5f5f5;
}
</style>
