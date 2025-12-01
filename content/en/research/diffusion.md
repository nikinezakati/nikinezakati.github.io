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
  border: 1px solid #97c2e6ff;
  border-radius: 10px;
  padding: 0.9rem 1.4rem;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
  background: #97c2e6ff;
  width: 100%;
}
.project-card h3 {
  margin-top: 0;
  margin-bottom: 0.75rem;
}
.project-card p {
  margin: 0;
  text-align: justify;
}
</style>
