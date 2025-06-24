# Image-quality-Enhancement---A-GAN-based-approach



# NASR-GAN: Neural Aesthetic Super-Resolution GAN

NASR-GAN is a novel three-stage GAN architecture developed to enhance low-resolution images by not only restoring structural details but also optimizing aesthetic quality. The pipeline is built with Restoration GAN (R-GAN), Detail Enhancer GAN (D-GAN), and Aesthetic Super-Resolution GAN (A-GAN), ensuring images are sharp, detailed, and visually appealing.

---

## 🔍 Project Overview

- **Problem**: Traditional super-resolution methods often focus only on pixel-level accuracy, ignoring how aesthetically pleasing an image looks.
- **Solution**: NASR-GAN integrates an Aesthetic Loss Function to align the generated images with human visual preferences while maintaining high resolution and structural fidelity.
- **Architecture**: 
  - **R-GAN**: Removes noise and reconstructs image structure
  - **D-GAN**: Sharpens edges and restores high-frequency textures
  - **A-GAN**: Optimizes for perceptual appeal using aesthetic scoring and attention mechanisms

---


