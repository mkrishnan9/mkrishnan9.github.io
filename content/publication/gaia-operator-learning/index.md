---
title: "GAIA: Geometry Adaptive Integral AutoEncoder Networks for Operator Learning"
authors:
- admin
- P. Pulijala
- Ke Chen
- Haizhao Yang
- Ramani Duraiswami
date: "2026-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2607.01128 (in review)"
publication_short: ""

abstract: "Operator learning for partial differential equations (PDEs) on arbitrary geometries builds fast neural surrogates for large-scale simulation. Although recent geometry-adaptive neural operators have made substantial progress, they are mainly designed for forward problems in which inputs and outputs share the same spatial domain. This limits their applicability for boundary value problems (BVPs) and inverse problems, where inputs and outputs may live on different domains. We introduce the Geometry-Adaptive Integral Autoencoder (GAIA), an operator learning model that encodes the domain boundary and the interior field distribution into geometry tokens, and conditions integral transform layers on these tokens via cross-attention, allowing the kernel to adapt locally to geometric features. This yields a single architecture for forward (including BVPs) and inverse problems on arbitrary domains in one pass, without retraining, iterative optimization, or graph construction. We evaluate GAIA on seven 2D and 3D benchmarks, four of which are new or substantially extended benchmarks for inverse problems and BVP: electrical impedance tomography, optical tomography, 3D Darcy flow on varying geometries, and a modified setting of Poisson BVP on mechanical components benchmark (MCB). GAIA sets new state-of-the-art results on every inverse and BVP task, reducing median relative L2 error by 64% on airfoil flow reconstruction and 27% on EIT relative to the next best amortized method, and outperforming all baselines on every shape category of MCB. On other forward problems, GAIA is competitive with specialized solvers while maintaining stable accuracy across point resolutions on which transformer-based baselines degrade."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Source Themes
featured: false

url_pdf: https://arxiv.org/abs/2607.01128
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
