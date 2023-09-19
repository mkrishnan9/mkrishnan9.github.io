---
title: "A unified asymptotic preserving and well-balanced scheme for the Euler system with multiscale relaxation"
authors:
- admin
- K R Arun
- Saurav Samantaray
date: "2022-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computers and Fluids"
publication_short: ""

abstract: "The design and analysis of a unified asymptotic preserving (AP) and well-balanced scheme for the Euler Equations with gravitational and frictional source terms is presented in this paper. The asymptotic behaviour of the Euler system in the limit of zero Mach and Froude numbers, and large friction is characterised by an additional scaling parameter. Depending on the values of this parameter, the Euler system relaxes towards a hyperbolic or a parabolic limit equation. Standard Implicit–Explicit Runge–Kutta schemes are incapable of switching between these asymptotic regimes. We propose a time semi-discretisation to obtain a unified scheme which is AP for the two different limits. A further reformulation of the semi-implicit scheme can be recast as a fully-explicit method in which the mass update contains both hyperbolic and parabolic fluxes. A space–time fully-discrete scheme is derived using a finite volume framework. A hydrostatic reconstruction strategy, an upwinding of the sources at the interfaces, and a careful choice of the central discretisation of the parabolic fluxes are used to achieve the well-balancing property for hydrostatic steady states. Results of several numerical case studies are presented to substantiate the theoretical claims and to verify the robustness of the scheme."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0045793021003510
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


