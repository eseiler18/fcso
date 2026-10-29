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

> **Note:** The source code, is currently being prepared for release.  

---

### 📖 Abstract

Optimizing 3D shapes within the latent spaces of deep generative models is fundamental to computer assisted engineering, yet remains prone to a critical failure mode we term manifold drift: the tendency of gradient-based optimization to move latent vectors away from the manifold of valid shapes. This problem is exacerbated in state-of-the-art 3D shape generative models that operate in increasingly high-dimensional latent spaces where valid shapes occupy a vanishingly small fraction of the full space. Existing mitigation strategies, including latent regularization and flow-matching approaches, either sacrifice expressiveness, demand a difficult trade-off between objective guidance and generative fidelity that remains prone to manifold drift, or are computationally infeasible to scale to modern, large-capacity 3D shape models. We introduce a novel optimizer-corrector framework that alternates between gradient steps for objective minimization and guided flow matching to drive the latent state back to the valid shape manifold. By decoupling objective minimization from flow-based correction, optimizing freely and correcting strictly, this alternating design avoids inherent trade-offs, preserving geometric validity without sacrificing expressiveness while remaining computationally feasible on modern 3D shape models. We demonstrate its effectiveness across generative priors of varying complexity, from simple vector latent spaces to large-scale architectures across a variety of downstream optimization tasks, including aerodynamic drag reduction and object compliance optimization.

---

### 📚 Citation

If you find this work or method useful for your research, please consider citing:

```bibtex
@misc{seiler2026flowcorrectedshapeoptimizationtaming,
      title={Flow-Corrected Shape Optimization: Taming Manifold Drift in High-Dimensional 3D Models}, 
      author={Emilien Seiler and Nicolas Talabot and Yingxuan You and Federico Stella and Pascal Fua},
      year={2026},
      eprint={2608.07199},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2608.07199}, 
}
