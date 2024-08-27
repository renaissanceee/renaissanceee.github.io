---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a third-year master student from [University of Stuttgart](https://www.uni-stuttgart.de/en/), Germany. My research interests include computer vision, neural rendering and generative models. Before that, I got my bachelor degree from [Beijing Institute of Technology (BIT)](https://english.bit.edu.cn/), China in 2021.

[CV](../assets/cv_github.pdf) / [Email](mailto:st179481@stud.uni-stuttgart.de) / [Github](https://github.com/renaissanceee) / [Wechat](../images/wechat.jpg).

## Recent News
I'm looking for PhD positions.
## Publications
[Mipmap-GS: Let Gaussians Deform with Scale-specific Mipmap for Anti-aliasing Rendering](https://arxiv.org/abs/2408.06286)
3D Gaussian Splatting (3DGS) has attracted great attention in novel view synthesis because of its superior rendering efficiency and high fidelity. However, the trained Gaussians suffer from severe zooming degradation due to non-adjustable representation derived from single-scale training. Though some methods attempt to tackle this problem via post-processing techniques such as selective rendering or filtering techniques towards primitives, the scale-specific information is not involved in Gaussians. In this paper, we propose a unified optimization method to make Gaussians adaptive for arbitrary scales by self-adjusting the primitive properties (e.g., color, shape and size) and distribution (e.g., position). Inspired by the mipmap technique, we design pseudo ground-truth for the target scale and propose a scale-consistency guidance loss to inject scale information into 3D Gaussians. Our method is a plug-in module, applicable for any 3DGS models to solve the zoom-in and zoom-out aliasing. Extensive experiments demonstrate the effectiveness of our method. Notably, our method outperforms 3DGS in PSNR by an average of 9.25 dB for zoom-in and 10.40 dB for zoom-out on the NeRF Synthetic dataset.
[arkiv](https://arxiv.org/abs/2408.06286) | [code](https://github.com/renaissanceee/Mipmap-GS)
