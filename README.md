<div align="center"><h1> Motion Mamba: Efficient and Long Sequence Motion Generation with Hierarchical and Bidirectional Selective SSM<br>
<!-- <sub><sup><a href="">Under Review</a></sup></sub>  -->
</h1>

[Zeyu Zhang](https://steve-zeyu-zhang.github.io)<sup>\*</sup>, [Akide Liu](https://www.linkedin.com/in/akideliu/)<sup>\*</sup>, [Ian Reid](https://mbzuai.ac.ae/study/faculty/ian-reid/), [Richard Hartley](http://users.cecs.anu.edu.au/~hartley/), [Bohan Zhuang](https://bohanzhuang.github.io/), [Hao Tang](https://ha0tang.github.io/)<sup>✉</sup>

<sup>*</sup>Equal Contribution
<sup>✉</sup>Corresponding author: bjdxtanghao@gmail.com

[![Website](https://img.shields.io/badge/Website-Demo-fedcba?style=flat-square)](https://steve-zeyu-zhang.github.io/MotionMamba/) [![arXiv](https://img.shields.io/badge/arXiv-2403.07487-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2403.07487) [![OpenReview](https://img.shields.io/badge/OpenReview-8c1b13?style=flat-square)]() [![Papers With Code](https://img.shields.io/badge/Papers%20With%20Code-555555.svg?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2aWV3Qm94PSIwIDAgNTEyIDUxMiIgd2lkdGg9IjUxMiIgIGhlaWdodD0iNTEyIiA+PHBhdGggZD0iTTg4IDEyOGg0OHYyNTZIODh6bTE0NCAwaDQ4djI1NmgtNDh6bS03MiAxNmg0OHYyMjRoLTQ4em0xNDQgMGg0OHYyMjRoLTQ4em03Mi0xNmg0OHYyNTZoLTQ4eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PHBhdGggZD0iTTEwNCAxMDRWNTZIMTZ2NDAwaDg4di00OEg2NFYxMDR6bTMwNC00OHY0OGg0MHYzMDRoLTQwdjQ4aDg4VjU2eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PC9zdmc+)]() [![BibTeX](https://img.shields.io/badge/BibTeX-Citation-eeeeee?style=flat-square)]()

</div>

_Human motion generation stands as a significant pursuit
in generative computer vision, while achieving long-sequence and efficient motion generation remains challenging. Recent advancements in
state space models (SSMs), notably Mamba, have showcased considerable promise in long sequence modeling with an efficient hardware-aware
design, which appears to be a promising direction to build motion generation model upon it. Nevertheless, adapting SSMs to motion generation faces hurdles since the lack of a specialized design architecture to
model motion sequence. To address these challenges, we propose **Motion
Mamba**, a simple and efficient approach that presents the pioneering
motion generation model utilized SSMs. Specifically, we design a **Hierarchical Temporal Mamba** (**HTM**) block to process temporal data by
ensemble varying numbers of isolated SSM modules across a symmetric U-Net architecture aimed at preserving motion consistency between
frames. We also design a **Bidirectional Spatial Mamba** (**BSM**) block to bidirectionally process latent poses, to enhance accurate motion generation within a temporal frame. Our proposed method achieves up to **50%** FID improvement and up to **4** times faster on the HumanML3D and
KIT-ML datasets compared to the previous best diffusion-based method,
which demonstrates strong capabilities of high-quality long sequence motion modeling and real-time human motion generation._

![combine](static/images/combine.svg)

## Stay tuned, project website will be ready soon!

## Acknowledgements

- [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://github.com/state-spaces/mamba)

- [Motion Latent Diffusion: Executing your Commands via Motion Diffusion in Latent Space](https://github.com/ChenFengYe/motion-latent-diffusion)
