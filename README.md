# scene_aware_humanmotion_gen

This is a scene aware human motion generation project for Master Class in Bournemouth university 2025.

# Abstract

We introduce a framework that turns a single RGB image + monocular depth into realistic, physically-plausible human motion, skipping text prompts and heavy 3D scene recon. A Transformer-based diffusion model consumes image and depth features to predict full motion sequences, trained on our new image-motion bi-modal dataset. The model beats strong baselines on multiple metrics, proving that lightweight visual input is enough for high-quality scene-aware motion generation.


<p align="center">
  <img src="assets/gif1.gif" width="45%" />
  &nbsp;  <!-- margin-right -->
  <img src="assets/gif2.gif" width="45%" />
</p>

<p align="center">
  <img src="assets/gif3.gif" width="45%" />
  &nbsp;
  <img src="assets/gif4.gif" width="45%" />
</p>
