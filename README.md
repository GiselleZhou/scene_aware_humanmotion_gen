# scene_aware_humanmotion_gen

This is a scene aware human motion generation project for Master Class in Bournemouth university 2025.

# Abstract

We introduce a framework that turns a single RGB image + monocular depth into realistic, physically-plausible human motion, skipping text prompts and heavy 3D scene recon. A Transformer-based diffusion model consumes image and depth features to predict full motion sequences, trained on our new image-motion bi-modal dataset. The model beats strong baselines on multiple metrics, proving that lightweight visual input is enough for high-quality scene-aware motion generation.

![Our Dataset](assets/gif1.gif)
![Comparison to Baselines in the Kitchen](assets/gif2.gif)
![Comparison to Baselines on the Road](assets/gif3.gif)
![Comparison to Baselines in the Basketball Court](assets/gif4.gif)

<p align="center">
  <video src="assets/video.mp4"
         width="600"
         autoplay
         loop
         muted
         playsinline
         controls>
    Your browser does not support the video tag.
  </video>
</p>

