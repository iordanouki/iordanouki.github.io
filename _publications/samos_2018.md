---
title: "A performance evaluation of multi-FPGA architectures for computations of information transfer."
collection: publications
permalink: /publication/samos_2018
excerpt: ''
date: 15-07-2018
venue: 'Proceedings of the 18th International Conference on Embedded Computer Systems: Architectures, Modeling, and Simulation'
paperurl: 'https://dl.acm.org/doi/10.1145/3229631.3229635'
---
Mutual Information (MI) and Transfer Entropy (TE) algorithms compute statistical measurements on the information shared between two dependent random processes. These measurements have focused on pairwise computations of time series in a broad range of fields, such as Econometrics, Neuroscience, Data Mining and Computer Vision. Unlike previous works which mostly focus on 8-bit Computer Vision applications, this work proposes the first generic hardware architectures for the acceleration of the MI and TE algorithms to target any dataset for a realistic, multi-FPGA platform. We evaluate and compare two such systems, the Maxeler MAX3A Vectis and the Convey HC-2ex platforms, and provide insight into each one's benefits and limitations. All reported results are from actual experimental runs, including I/O overhead, and comprise lower bounds of our systems' full capabilities for large-scale datasets. These are compared to equivalent optimized multi-threaded software implementations, yielding ~19x speedup vs. out-of-the-box software packages and ~2.5x speedup vs. highly optimized software that is presented in the related work. These hardware architectures are obtained with a small fraction of the FPGA resources, and are limited by I/O bandwidth. This means that with near-future FPGA I/O capabilities, the performance of the architectures presented in this work for the O(n^2) Mutual Information and the O(n^3) Transfer Entropy problems will easily scale up.

[Find it on ACM Digital Library](https://dl.acm.org/doi/10.1145/3229631.3229635)
