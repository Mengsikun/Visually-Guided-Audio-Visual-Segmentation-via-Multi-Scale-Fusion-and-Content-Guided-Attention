![2](https://github.com/user-attachments/assets/97e3ad0d-6295-4b38-a5a1-12c58526f338)
# Visually-Guided Audio-Visual Segmentation via Multi-Scale Fusion and Content-Guided Attention

> **Authors:** Ying Cao, Sikun Meng, Yonghang Yan, Hengyi Ren

[![Paper](https://img.shields.io/badge/Paper-Coming_Soon-blue.svg)](#)
[![Dataset](https://img.shields.io/badge/Dataset-AVSBench-orange)](#)

This is the official PyTorch implementation of our proposed visually-guided framework for the Audio-Visual Segmentation (AVS) task.

## 🚀 News & Updates
- **[Coming Soon]** The complete source code (including our proposed **MSF** and **CGAF** modules), training logs, and pre-trained weights (ResNet-50 & PVTv2) will be made publicly available upon the official acceptance and publication of the paper. Stay tuned!

## 📖 Abstract
Audio-Visual Segmentation (AVS) is designed to utilize audio signals for identifying and generating pixel-level segmentation masks of sounding objects, mirroring the intertwined nature of human audio-visual perception. While recent technological strides have fostered related tasks such as Sound Source Localization (SSL) and audiovisual event localization, these primarily address coarse-grained analysis. In contrast, AVS demands a finer-grained perception capability to simultaneously localize sound sources and accurately delineate their shapes. Driven by this requirement for detailed cross-modal understanding and pixel-level precision, AVS holds significant potential across diverse applications, including video editing, augmented reality, and intelligent surveillance systems.Although these methods are effective, they fail to fully explore the fine-grained correlations between audio and visual cues across various scenarios. First, in multi-source scenes where multiple targets emit sound simultaneously, mixed audio signals with high information density struggle to adaptively attend to visual signals. Second, simple fusion strategies often result in the insufficient utilization of cross-modal information.

## 🏗️ Architecture
*(You can upload your Figure 2 architecture diagram here later)*
```html
<p align="center">
  <img src="docs/framework.png" alt="Framework" width="80%">
</p>
