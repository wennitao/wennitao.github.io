---
title: 'VQ-LLM: High-performance Code Generation for Vector Quantization Augmented LLM Inference'
authors:
- Zihan Liu
- Xinhao Luo
- Junxian Guo
- admin
- Yangjie Zhou
- Yue Guan
- Cong Guo
- Weihao Cui
- Yu Feng
- Minyi Guo
- Yuhao Zhu
- Minjia Zhang
- Jingwen Leng
- Chen Jin
date: '2025-03-05'
publishDate: '2024-09-27T22:18:53.424151Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 29th ACM International Conference on Architectural
  Support for Programming Languages and Operating Systems, Volume 2*'
publication_short: '**HPCA 2025**'

abstract: In this work, we design and implement VQ-LLM, an efficient fused Vector Quantization (VQ) kernel generation framework. We first introduce a software abstraction called codebook cache to optimize codebook access efficiency and support the integration of VQ with various computations. The codebook cache adaptively stores different entries across the GPU's memory hierarchy, including off-chip global memory, on-chip shared memory, and registers. Centered around the codebook cache, we design an efficient computation engine that optimizes memory traffic during computations involving codebooks. This compute engine adopts the codebook-centric dataflow and fusion optimizations. Additionally, we provide adaptive heuristics to tailor parameter selection in our optimizations to diverse VQ configurations. Our optimizations achieve an average latency reduction of 46.13% compared to unoptimized versions. Compared to existing open-source implementations, our methods decrease latency by 64.36% to 99.1%. A final comparison with state-of-the-art element-wise quantization methods like AWQ and KVQuant shows that our VQ-LLM is practically viable, achieving latencies close or even better latencies to those at equivalent bit-widths, potentially offering greater accuracy.

tags: 
  - Vector Quantization

url_pdf: 'https://doi.org/10.48550/arXiv.2503.02236'
# url_code: 'https://github.com/SubjectNoi/RTANN'
---
