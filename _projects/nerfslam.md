---
title: "<br/><img src='/images/projects/nerfslam/nerfslam_icon.png' width='50'> NeRF-SLAM Docker"
excerpt: "**Relevant skills: Python, PyTorch, GTSAM, Docker** 
We built a docker environment of NeRF-SLAM: *Real-Time Dense Monocular SLAM with Neural Radiance Fields* by Antoni Rosinol, John J. Leonard, and Luca Carlone. We replicate results in the paper, as well as test on our own datasets."
collection: projects
---

In this project, we built a docker environment of [*NeRF-SLAM: Real-Time Dense Monocular SLAM with Neural Radiance Fields*](https://arxiv.org/abs/2210.13641) by Antoni Rosinol, John J. Leonard, and Luca Carlone. NeRF-SLAM performs monocular visual SLAM and achieves 3D scene reconstruction using NeRFs.  

We reproduced the paper results on the Replica dataset. Additionaly, we collected our own datasets of locations in the University of Michigan Ford Robotics Building. Our datasets and video results can be found at this [link](https://drive.google.com/drive/folders/1QP0KsM6KKRtO_wGg9mvceJ_WIQCdat15). The figure below shows one of our results.

<img src="/images/projects/nerfslam/nerfslam_figure.png">

Our testing was run on a GTX 4080 with 12gb of VRAM. Our tests do not show real-world performance, and there were memory constraints, though the final renders showed high fidelity. More details can be found in the report linked below.  


Links:
* [GitHub Repo](https://github.com/sarveshmayil/NeRF-SLAM-docker)
* [Detailed Report](https://hvak.io/files/NeRF_SLAM_Report.pdf)
* [Datasets & Videos](https://drive.google.com/drive/folders/1QP0KsM6KKRtO_wGg9mvceJ_WIQCdat15)