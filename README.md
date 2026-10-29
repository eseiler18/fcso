# Flow-Corrected Shape Optimization: Taming Manifold Drift in High-Dimensional 3D Models

[![NeurIPS 2026](https://img.shields.io/badge/NeurIPS-2026-blue.svg)](https://neurips.cc/)
[![Paper](https://img.shields.io/badge/arXiv-Paper-red.svg)](https://arxiv.org/abs/2608.07199)
[![Project Page](https://img.shields.io/badge/Project-Page-green.svg)](https://eseiler18.github.io/projects/fcso/)

This repository contains the official PyTorch implementation and benchmarks for the paper:

> **Flow-Corrected Shape Optimization: Taming Manifold Drift in High-Dimensional 3D Models**  
> Emilien Seiler, Nicolas Talabot, Federico Stella, Yingxuan You, Pascal Fua  
> *CVLab, EPFL*  
> **NeurIPS 2026**

---

### 🚧 Coming Soon

> **Note:** The source code, pre-trained models, and benchmark evaluation suites are currently being prepared for release.  
> Everything will be made available here shortly. Star ⭐ or watch this repository to stay tuned!

---

### 📖 Abstract

Optimizing 3D shapes within the latent spaces of deep generative models is fundamental to computer-assisted engineering, yet remains prone to a critical failure mode we term **manifold drift**: the tendency of gradient-based optimization to move latent vectors away from the manifold of valid shapes. 

We introduce **Flow-Corrected Shape Optimization (FCSO)**, an optimizer-corrector framework that alternates between gradient steps for objective minimization and guided flow matching to drive the latent state back to the valid shape manifold. By decoupling objective minimization from flow-based correction, FCSO preserves geometric validity without sacrificing expressiveness while scaling efficiently to modern, high-capacity 3D shape models.

---

### 📚 Citation

If you find this work or method useful for your research, please consider citing:

```bibtex
@inproceedings{seiler2026flowcorrected,
  title={Flow-Corrected Shape Optimization: Taming Manifold Drift in High-Dimensional 3D Models},
  author={Seiler, Emilien and Talabot, Nicolas and Stella, Federico and You, Yingxuan and Fua, Pascal},
  booktitle={Advances in Neural Information Processing Systems (NeurIPS)},
  year={2026}
}
