<div align="center">
<h2>COREA</h2>

<div>&nbsp;&nbsp;
    Jaeyoon Lee<sup>*</sup>&nbsp;
    Hojoon Jung<sup>*</sup>&nbsp;
    Sungtae Hwang&nbsp;
    Jihyong Oh<sup>†</sup>&nbsp;
    Jongwon Choi<sup>†</sup>
</div>

<div>
    Chung-Ang University, Seoul, Korea
</div>
<div>
    <sup>*</sup>Equal contribution, <sup>†</sup>Co-corresponding authors
</div>
<br>

<h4>
    <a href="https://vilab-cau.github.io/COREA/" target='_blank'>
    <img src="https://img.shields.io/badge/🌐-Project%20Page-blue">
    </a>
    <a href="https://arxiv.org/abs/25xx.xxxxx" target='_blank'>
    <img src="https://img.shields.io/badge/arXiv-Paper-b31b1b.svg">
    </a>
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/VILab-CAU/COREA?style=social">
</h4>
</div>

---

<div align="center">
    <h4>
        This repository is the official implementation of "<b>COREA</b>: Coarse-to-Fine 3D Representation Alignment Between <br>
    Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision."
    </h4>
</div>

<div align="center">
    🔥 <b>Physically-based relighting</b>,<br>
    🎯 <b>Bidirectional 3D-to-3D geometry alignment</b>,<br>
    🎨 <b>High-fidelity wrinkles & shading preservation</b>
</div>

<br>

<div align="center">
    <img src="assets/teaser.png" alt="Teaser" width="92%">
</div>

---

## 📢 News
- **Dec 2025** — arXiv submission completed (coming soon)
- **Project Page launch** — Online with all demos
- **Code release plan updated**

---

## 📖 Abstract

Accurate geometry is essential for relightable 3D Gaussian splatting.  
However, existing PBR-driven methods learn 3D properties **indirectly** from rendered 2D signals, producing imprecise normals and unstable shading.

We present **COREA**, the first **unified** framework that jointly learns relightable 3D Gaussians and a neural SDF under **coarse-to-fine bidirectional geometry supervision**:

- Gaussian depth → guides SDF rays and pixel-wise depth gradients (**DSA**)
- SDF normals → supervise Gaussian normals and drive densification (**N3A**)
- **DDC** regulates splitting to ensure memory-efficient refinement

This synergy delivers **precise geometry**, **robust BRDF-lighting decomposition**, and **state-of-the-art** performance on NVS, mesh reconstruction, and relighting tasks.

---

## 🖼️ Method Overview

<p align="center">
    <img src="assets/pipeline.png" width="92%">
</p>

<p align="center">
    <img src="assets/bidirectional.png" width="80%">
</p>

---

## 🔥 Key Features

| Component | What it does |
|---|---|
| **DSA** | Aligns SDF via Gaussian depth + depth gradients |
| **N3A** | Supervises Gaussian normals directly in 3D |
| **DDC** | Regulates densification to control memory growth |
| **Differentiable PBR** | Accurate BRDF & lighting decomposition |

---

## 📬 Contact

For questions, please reach out at  
📧 **leejaeyoon@vilab.cau.ac.kr**

---

⭐ If you find this repository helpful, please consider starring it!
