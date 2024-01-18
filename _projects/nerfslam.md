---
title: "<img src='/images/projects/nerfslam/nerfslam_icon.png' width='50'> NeRF-SLAM Docker"
excerpt: "**Relevant skills: Python, PyTorch, GTSAM, Docker** 
We built a docker environment of NeRF-SLAM: *Real-Time Dense Monocular SLAM with Neural Radiance Fields* by Antoni Rosinol, John J. Leonard, and Luca Carlone. We replicate results in the paper, as well as test on our own datasets."
collection: projects
---

In this project, we built a docker environment of [*NeRF-SLAM: Real-Time Dense Monocular SLAM with Neural Radiance Fields*](https://arxiv.org/abs/2210.13641) by Antoni Rosinol, John J. Leonard, and Luca Carlone.

---

### Abstract
Simultaneous localization and mapping (SLAM) is a fundamental robotics problem, which has seen a wide range of solutions. Performing visual SLAM with just monocular images and achieving 3D reconstruction is an extremely challenging problem. NeRF-SLAM achieves this through a combination of dense monocular SLAM, probabilistic volumetric fusion, and real-time hierarchical volumetric neural radiance fields. This scene reconstruction pipeline has shown to be geometrically and photometrically more accurate than other methods. We present a docker environment than allows NeRF-SLAM to work immediately for easy development and deployment. Additionally, we reproduce the results of NeRF-SLAM on the Replica dataset and perform inference on real-world custom datasets.

Our code is publicly available at [Code Repo](https://github.com/sarveshmayil/NeRF-SLAM-docker). Our datasets and video results are available at [Datasets & Videos](https://drive.google.com/drive/folders/1QP0KsM6KKRtO_wGg9mvceJ_WIQCdat15).

---

The figure below shows a screenshot one of our results.

<img src="/images/projects/nerfslam/nerfslam_figure.png">

Our testing was run on a GTX 4080 with 12gb of VRAM. Our tests do not show real-time performance, and there were memory constraints, though the final renders showed high fidelity. More details can be found in the report linked below.  

---
Links:
* [GitHub Repo](https://github.com/sarveshmayil/NeRF-SLAM-docker)
* [Detailed Report](https://hvak.io/files/NeRF_SLAM_Report.pdf)
* [Datasets & Videos](https://drive.google.com/drive/folders/1QP0KsM6KKRtO_wGg9mvceJ_WIQCdat15)