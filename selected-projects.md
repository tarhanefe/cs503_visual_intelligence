---
layout: page
title: Selected Projects
subtitle: Examples of standout work across recent offerings
full-width: true
---

<style>
.project-year {
  margin-top: 2.5rem;
  margin-bottom: 1.25rem;
}
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.25rem;
}
.project-card {
  display: block;
  border-radius: 12px;
  overflow: hidden;
  background: #f8f9fb;
  color: inherit;
  text-decoration: none;
  box-shadow: 0 6px 20px rgba(0,0,0,0.08);
  transition: transform 0.15s ease, box-shadow 0.2s ease, border-color 0.2s ease;
  border: 1px solid transparent;
}
.project-card:hover, .project-card:focus {
  transform: translateY(-3px);
  box-shadow: 0 12px 28px rgba(0,0,0,0.12);
  border-color: #d7e3ff;
  outline: none;
}
.project-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  display: block;
}
.project-card .body {
  padding: 1rem 1.1rem 1.2rem;
}
.project-card h4 {
  margin: 0 0 0.35rem;
  font-size: 1.05rem;
}
.project-card p {
  margin: 0;
  color: #4a4f5a;
  font-size: 0.94rem;
}
</style>

> Click any project tile to learn more. Replace links, images, and descriptions with your real projects.

## 2024

<div class="project-grid">
  <a class="project-card" href="https://example.com/project-vision-agents" target="_blank" rel="noopener">
    <img src="/assets/img/projects/vision-agents.jpg" alt="Vision agents project preview">
    <div class="body">
      <h4>Embodied Vision Agents</h4>
      <p>Built a vision-language policy that grounds spatial instructions in 3D scenes, demonstrating robust navigation under noisy sensing.</p>
    </div>
  </a>
  <a class="project-card" href="https://example.com/project-robust-multimodal" target="_blank" rel="noopener">
    <img src="/assets/img/projects/robust-multimodal.jpg" alt="Robust multimodal model preview">
    <div class="body">
      <h4>Robust Multimodal Retrieval</h4>
      <p>Designed a contrastive pretraining recipe that stays accurate under occlusions, boosting zero-shot retrieval on out-of-domain photos.</p>
    </div>
  </a>
  <a class="project-card" href="https://example.com/project-3d-recon" target="_blank" rel="noopener">
    <img src="/assets/img/projects/3d-recon.jpg" alt="3D reconstruction preview">
    <div class="body">
      <h4>Few-Shot 3D Reconstruction</h4>
      <p>Combined NeRF distillation with geometric priors to recover consistent meshes from as few as three posed images.</p>
    </div>
  </a>
</div>

## 2023

<div class="project-grid">
  <a class="project-card" href="https://example.com/project-open-set" target="_blank" rel="noopener">
    <img src="/assets/img/projects/open-set.jpg" alt="Open set detection preview">
    <div class="body">
      <h4>Open-Set Scene Detection</h4>
      <p>Introduced uncertainty-aware prompts for vision transformers, improving detection of unseen classes in driving scenes.</p>
    </div>
  </a>
  <a class="project-card" href="https://example.com/project-human-motion" target="_blank" rel="noopener">
    <img src="/assets/img/projects/human-motion.jpg" alt="Human motion synthesis preview">
    <div class="body">
      <h4>Text-to-Motion Synthesis</h4>
      <p>Built a diffusion model that translates free-form text into physically plausible human motion clips with style control.</p>
    </div>
  </a>
</div>
