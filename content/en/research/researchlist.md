+++
date = "2025-11-12T00:00:00"
+++

<div style="text-align: justify;">

### Research

</div>

<p style="text-align: justify;">
My research spans computer vision, NLP, multimodal learning, and 3D reconstruction, with a focus on building reliable ML systems that operate robustly under real-world conditions. I develop diffusion-based methods for image restoration that handle real sensor noise, low-quality inputs, and cross-domain degradations. I also work on improving the robustness of multimodal models when information is missing, corrupted, or imbalanced across modalities. Beyond 2D vision, I explore 3D reconstruction and neural rendering, including camera pose estimation, NeRF, and Gaussian Splatting. More broadly, my work connects generative modeling, visual understanding, and trustworthy AI, strengthened by my background in natural language processing.
</p>

<div class="research-circles">
  <a class="research-circle" href="/research/diffusion/">
    <div class="circle-image" style="background-image: url('/uploads/research-diffusion.png');" aria-hidden="true"></div>
    <div class="circle-label">Diffusion Models for Inverse Problems</div>
  </a>

  <a class="research-circle" href="/research/multimodal/">
    <div class="circle-image" style="background-image: url('/uploads/research-multimodal.png');" aria-hidden="true"></div>
    <div class="circle-label">Robust Multimodal Learning</div>
  </a>

  <a class="research-circle" href="/research/3d/">
    <div class="circle-image" style="background-image: url('/uploads/research-3d.png');" aria-hidden="true"></div>
    <div class="circle-label">3D Reconstruction</div>
  </a>
</div>


<style>
.research-circles {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  justify-content: center;
  margin-top: 1.5rem;
}
.research-circle {
  flex: 1 1 200px;
  max-width: 240px;
  text-align: center;
  text-decoration: none;
  color: inherit;
}
.circle-image {
  width: 220px;
  height: 220px;
  margin: 0 auto;
  border-radius: 50%;
  background-size: cover;
  background-position: top center;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.research-circle:hover .circle-image,
.research-circle:focus .circle-image {
  transform: translateY(-6px);
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.25);
}
.circle-label {
  margin-top: 0.75rem;
  font-size: 1.1rem;
  font-weight: 600;
}
@media (max-width: 600px) {
  .circle-image {
    width: 180px;
    height: 180px;
  }
}
</style>
