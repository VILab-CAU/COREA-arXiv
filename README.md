<div align="center">

<a href="https://sites.google.com/vilab.cau.ac.kr/jaeyoonlee" target="_blank">
Jaeyoon Lee</a><sup>*</sup>&nbsp;

<a href="https://sites.google.com/view/hjjung-homepage/홈" target="_blank">
Hojoon Jung</a><sup>*</sup>&nbsp;

<a href="https://sites.google.com/vilab.cau.ac.kr/hst/" target="_blank">
Sungtae Hwang</a>&nbsp;

<a href="https://sites.google.com/view/ozbro/" target="_blank">
Jihyong Oh</a><sup>†</sup>&nbsp;

<a href="https://sites.google.com/site/jwchoivision/home" target="_blank">
Jongwon Choi</a><sup>†</sup>

<br>

<sup>*</sup>Equal contribution &nbsp;&nbsp;&nbsp; <sup>†</sup>Corresponding authors  
<br>
Chung-Ang University, Seoul, Korea

</div>

<br>

<h4>
    <a href="https://vilab-cau.github.io/COREA/" target='_blank'>
    <img src="https://img.shields.io/badge/🌐https://sites.google.com/view/ozbro-Project%20Page-blue">
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
        This repository is the official implementation of "<b>COREA</b>: Coarse-to-Fine 3D Representation Alignment<br>
    Between Relightable 3D Gaussians and SDF via Bidirectional 3D-to-3D Supervision."
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

We present **COREA**, the first unified framework that jointly learns relightable 3D Gaussians and a Signed Distance Field (SDF) for accurate geometry reconstruction and faithful relighting.
While recent 3D Gaussian Splatting (3DGS) methods have extended toward mesh reconstruction and physically-based rendering (PBR), their geometry is still learned from 2D renderings, leading to coarse surfaces and unreliable BRDF-lighting decomposition.
To address these limitations, COREA introduces a **coarse-to-fine bidirectional 3D-to-3D alignment** strategy that allows geometric signals to be learned directly in 3D space.
Within this strategy, depth provides coarse alignment between the two representations, while depth gradients and normals refine fine-scale structure, and the resulting geometry supports stable BRDF-lighting decomposition.
A density-control mechanism further stabilizes Gaussian growth, balancing geometric fidelity with memory efficiency.
Experiments on standard benchmarks demonstrate that COREA achieves superior performance in **novel-view synthesis**, **mesh reconstruction**, and **PBR** within a unified framework.

---

## 🖼️ Method Overview

<p align="center">
    <img src="assets/pipeline.png" width="92%">
</p>

<p align="center">
    <img src="assets/bidirectional.png" width="80%">
</p>

---

## 📬 Contact

For questions, please reach out at  
📧 **leejaeyoon@vilab.cau.ac.kr**

---

⭐ If you find this repository helpful, please consider starring it!
