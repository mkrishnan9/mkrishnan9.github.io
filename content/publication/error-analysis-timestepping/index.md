---
title: "Error Analysis for Learning Time-Stepping Algorithms for PDEs"
authors:
- Ke Chen
- admin
- Haizhao Yang
date: "2025-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2509.04256 (in review)"
publication_short: ""

abstract: "Deep neural networks (DNNs) have recently emerged as effective tools for approximating solution operators of partial differential equations (PDEs) including evolutionary problems. Classical numerical solvers for such PDEs often face challenges of balancing stability constraints and the high computational cost of iterative solvers. In contrast, DNNs offer a data-driven alternative through direct learning of time-stepping operators to achieve this balancing goal. In this work, we provide a rigorous theoretical framework for analyzing the approximation of these operators using feedforward neural networks (FNNs). We derive explicit error estimates that characterize the dependence of the approximation error on the network architecture -- namely its width and depth -- as well as the number of training samples. Furthermore, we establish Lipschitz continuity properties of time-stepping operators associated with classical numerical schemes and identify low-complexity structures inherent in these operators for several classes of PDEs, including reaction-diffusion equations, parabolic equations with external forcing, and scalar conservation laws. Leveraging these structural insights, we obtain generalization bounds that demonstrate efficient learnability without incurring the curse of dimensionality. Finally, we extend our analysis from single-input operator learning to a general multi-input setting, thereby broadening the applicability of our results."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Source Themes
featured: false

url_pdf: https://arxiv.org/abs/2509.04256
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---
