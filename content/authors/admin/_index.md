---
# Display name
title: Wentao Ni

# Name pronunciation (optional)
# name_pronunciation: Chien Shiung Wu

# Full name (for SEO)
first_name: Wentao
last_name: Ni

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: PhD

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of California San Diego
    url: https://ucsd.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:w2ni@ucsd.edu'
    label: E-mail Me
  # - icon: brands/x
  #   url: https://twitter.com/GetResearchDev
  # - icon: brands/instagram
  #   url: https://www.instagram.com/
  - icon: brands/github
    url: https://github.com/wennitao
  # - icon: brands/linkedin
  #   url: https://www.linkedin.com/
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?user=btVTcgIAAAAJ&hl=en
  # - icon: academicons/orcid
  #   url: https://orcid.org/

interests:
  - Machine Learning System
  - High Performance Computing
  - Computer Architecture

education:
  - area: PhD
    institution: University of California San Diego
    date_start: 2024-09-01
    date_end: 
    summary: |

  - area: BE
    institution: Shanghai Jiao Tong University
    date_start: 2020-09-01
    date_end: 2024-06-30
    summary: |
      
work:
  - position: Research Assistant
    company_name: Shanghai Jiao Tong University
    company_url: ''
    company_logo: ''
    date_start: 2022-06-01
    date_end: 2023-05-31
    summary: |2-  
      Optimize High-Dimensional ANNS with Ray-Tracing Core
      - We study the inefficiency of the typical IVFPQ pipeline and identify sparsity and spatial similarity in codebook usage.
      - We design a threshold-based selective algorithm to rapidly filter out the unnecessary search points leveraging the sparsity and spatial locality and propose a mapping for our algorithm to run on the RT core.
      - We study how to generalize the existing kNN-RT core mapping to ANN search with arbitrary dimensions, in aspects of approximation method, metrics and system design, and propose JUNO, an end-to-end high-dimensional ANN search engine with both algorithmic enhancement and optimized hardware mapping.
  - position: Research Assistant
    company_name: Duke University
    company_url: ''
    company_logo: ''
    date_start: 2022-09-01
    date_end: 2023-12-31
    summary: |
      Combining Graph & Tensor Transformation with Scheduling via Compilers
      - State Space Models (SSM) are known for its capability in long range modeling. However, the authors needed to carefully design CUDA kernels for SSMs.
      - We explore TVM and EinNet to combine graph-level and tensor-level transformation on tensor expressions, along with the scheduling space. We implement it based on TVM te expression.
  - position: Research Assistant
    company_name: Duke University
    company_url: ''
    company_logo: ''
    date_start: 2022-09-01
    date_end: 2023-12-31
    summary: |
      Search Efficient Network Architectures for LLM with Linear Complexity
      - We consider using NAS-based distillation to search architecture computing attention in linear complexity, like RetNet and Hyena Hierarchy.
      - Previously, we carefully study State Space Models (SSM) and its application in neural networks. We find it efficient in both memory and computation, so we want to find ways to apply it to transformers.
  - position: Research Intern
    company_name: Microsoft Research Asia
    company_url: ''
    company_logo: ''
    date_start: 2023-09-01
    date_end: 2023-12-31
    summary: |
      Improve LLM Quantization by Searching Configurations
      - We have previous works studying efficient kernels for sparse matrix computation (PIT and sparTA). So we consider building a search space of quantization configurations, such as quantization method, granularity, number of bits etc. With the help of sparse kernels, hybrid quantization can be perfectly supported.

# Skills
# Add your own SVG icons to `assets/media/icons/`
# skills:
#   - name: Technical Skills
#     items:
#       - name: Python
#         description: ''
#         percent: 80
#         icon: code-bracket
#       - name: Data Science
#         description: ''
#         percent: 100
#         icon: chart-bar
#       - name: SQL
#         description: ''
#         percent: 40
#         icon: circle-stack
#   - name: Hobbies
#     color: '#eeac02'
#     color_border: '#f0bf23'
#     items:
#       - name: Hiking
#         description: ''
#         percent: 60
#         icon: person-simple-walk
#       - name: Cats
#         description: ''
#         percent: 100
#         icon: cat
#       - name: Photography
#         description: ''
#         percent: 80
#         icon: camera

# languages:
#   - name: English
#     percent: 100
#   - name: Chinese
#     percent: 75
#   - name: Portuguese
#     percent: 25

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
# awards:
#   - title: Neural Networks and Deep Learning
#     url: https://www.coursera.org/learn/neural-networks-deep-learning
#     date: '2023-11-25'
#     awarder: Coursera
#     icon: coursera
#     summary: |
#       I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.

---

## About Me

Wentao Ni is a first year PhD at STABLE lab in University of California San Diego, advised by Prof. Jishen Zhao. His research interests include machine learning system, high performance computing and computer architecture. He wants to contribute to faster computations and less resources needed in machine learning and other computation tasks.
