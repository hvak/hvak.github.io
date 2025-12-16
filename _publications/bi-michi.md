---
title: "Bi-capacity Choquet Integral for Sensor Fusion with Label Uncertainty"
collection: publications
permalink: /publication/bi-michi2024
excerpt: 'This paper proposes a novel Choquet integral-based fusion framework, named Bi-MIChI, which uses bi-capacities to represent the interactions between pairs of subsets of the input sensor sources on a bi-polar scale. This allows for extended non-linear interactions between the sensor sources and can lead to interesting fusion results.'
date: 2024-08-05
venue: 'FUZZ-IEEE'
paperurl: 'https://arxiv.org/abs/2409.03212'
citation: 'H. Vakharia and X. Du, "Bi-Capacity Choquet Integral for Sensor Fusion with Label Uncertainty," 2024 IEEE International Conference on Fuzzy Systems (FUZZ-IEEE), Yokohama, Japan, 2024, pp. 1-10, doi: 10.1109/FUZZ-IEEE60900.2024.10611865.
'
---
**Abstract:** Sensor fusion combines data from multiple sensor sources to improve reliability, robustness, and accuracy of data interpretation. The Fuzzy Integral (FI), in particular, the Choquet integral (ChI), is often used as a powerful nonlinear aggregator for fusion across multiple sensors. However, existing supervised ChI learning algorithms typically require precise training labels for each input data point, which can be difficult or impossible to obtain. Additionally, prior work on ChI fusion is often based only on the normalized fuzzy measures, which bounds the fuzzy measure values between [0, 1]. This can be limiting in cases where the underlying scales of input data sources are bipolar (i.e., between [-1, 1]). To address these challenges, this paper proposes a novel Choquet integral-based fusion framework, named Bi-MIChI (pronounced "bi-mi-kee"), which uses bi-capacities to represent the interactions between pairs of subsets of the input sensor sources on a bi-polar scale. This allows for extended non-linear interactions between the sensor sources and can lead to interesting fusion results. Bi-MIChI also addresses label uncertainty through Multiple Instance Learning, where training labels are applied to "bags" (sets) of data instead of per-instance. Our proposed Bi-MIChI framework shows effective classification and detection performance on both synthetic and real-world experiments for sensor fusion with label uncertainty. We also provide detailed analyses on the behavior of the fuzzy measures to demonstrate our fusion process. 

[Link to the paper](https://arxiv.org/abs/2409.03212)

[Code repo](https://github.com/hvak/Bi-MIChI)

H. Vakharia and X. Du, "Bi-Capacity Choquet Integral for Sensor Fusion with Label Uncertainty," 2024 IEEE International Conference on Fuzzy Systems (FUZZ-IEEE), Yokohama, Japan, 2024, pp. 1-10, doi: 10.1109/FUZZ-IEEE60900.2024.10611865.
