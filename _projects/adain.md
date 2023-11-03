---
title: "AdaIN Style Transfer"
excerpt: "This is a pytorch implementation of Adaptive Instance Normalization (AdaIN) arbitrary style transfer, as outlined in Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization by Xun Huang and Serge Belongie.<br/><img src='/images/projects/adain/architecture.png' width='500'>"
collection: projects
---

Style transfer is a machine learning technique that transfers the "style" of one image to the "content" of another image.

This is a pytorch implementation of Adaptive Instance Normalization (AdaIN) arbitrary style transfer, as outlined in [Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization](https://arxiv.org/abs/1703.06868) by Xun Huang and Serge Belongie. The architecture of this method of style transfer is shown below:

<img src="/images/projects/adain/architecture.png">


A pytorch implementation of  [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576) by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge was also completed to serve as a method for comparison. A grid of comparison is shown below:

<img src="/images/projects/adain/grid.png">

Links:
* [GitHub Repo](https://github.com/hvak/adaIN-style-transfer)
* [Detailed Report](https://github.com/hvak/adaIN-style-transfer/blob/main/report.pdf)