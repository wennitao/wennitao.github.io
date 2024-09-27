---
title: 'JUNO: Optimizing High-Dimensional Approximate Nearest Neighbour Search with
  Sparsity-Aware Algorithm and Ray-Tracing Core Mapping'
authors:
- Zihan Liu
- admin
- Jingwen Leng
- Yu Feng
- Cong Guo
- Quan Chen
- Chao Li
- Minyi Guo
- Yuhao Zhu
date: '2024-01-01'
publishDate: '2024-09-27T22:18:53.424151Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 29th ACM International Conference on Architectural
  Support for Programming Languages and Operating Systems, Volume 2*'
publication_short: '**ASPLOS 2024**'

abstract: Approximate nearest neighbor (ANN) search is a widely applied technique in modern intelligent applications, such as recommendation systems and vector databases. Therefore, efficient and high-throughput execution of ANN search has become increasingly important. In this paper, we first characterize the state-of-the-art product quantization-based method of ANN search and identify a significant source of inefficiency in the form of unnecessary pairwise distance calculations and accumulations. To improve efficiency, we propose Juno, an end-to-end ANN search system that adopts a carefully designed sparsity- and locality-aware search algorithm. We also present an efficient hardware mapping that utilizes ray tracing cores in modern GPUs with pipelined execution on tensor cores to execute our sparsity-aware ANN search algorithm. Our evaluations on four datasets from 1 to 100 million search points demonstrate 2.2×-8.5× improvements in search throughput. Moreover, our algorithmic enhancements alone achieve a maximal 2.6× improvement on the hardware without the acceleration of the RT core.

tags: 
  - Approximate kNN
  - Ray Tracing
  - OptiX

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3620665.3640360'
url_source: 'https://github.com/SubjectNoi/RTANN'
---
