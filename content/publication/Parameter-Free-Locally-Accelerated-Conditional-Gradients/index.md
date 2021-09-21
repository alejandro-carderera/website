---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Parameter-Free Locally Accelerated Conditional Gradients - ICML 2021"
authors: [Alejandro Carderera, Jelena Diakonikolas, Cheuk Yin Lin, Sebastian Pokutta]
date: 2021-02-12T13:46:30-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-04T13:46:30-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ICML 2021"
publication_short: "ICML 2021"

abstract: "Projection-free conditional gradient (CG) methods are the algorithms of choice for constrained optimization setups in which projections are often computationally prohibitive but linear optimization over the constraint set remains computationally feasible. Unlike in projection-based methods, globally accelerated convergence rates are in general unattainable for CG. However, a very recent work on Locally accelerated CG (LaCG) has demonstrated that local acceleration for CG is possible for many settings of interest. The main downside of LaCG is that it requires knowledge of the smoothness and strong convexity parameters of the objective function. We remove this limitation by introducing a novel, Parameter-Free Locally accelerated CG (PF-LaCG) algorithm, for which we provide rigorous convergence guarantees. Our theoretical results are complemented by numerical experiments, which demonstrate local acceleration and showcase the practical improvements of PF-LaCG over non-accelerated algorithms, both in terms of iteration count and wall-clock time."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
  - icon_pack: fas
    icon: video
    name: Video
    url: 'https://slideslive.com/38959171/parameterfree-locally-accelerated-conditional-gradients?ref=account-90469-latest'
  - icon_pack: ai
    icon: arxiv
    name: PDF
    url: 'https://arxiv.org/pdf/2102.06806'
  - icon_pack: fab
    icon: github
    name: Code
    url: 'https://github.com/ericlincc/Parameter-free-LaCG'
  - icon_pack: fas
    icon: file
    name: Slides
    url: 'Short_Presentation_PFLaCG.pdf'
  - icon_pack: fas
    icon: file-powerpoint
    name: Poster
    url: 'PF_LaCG_Poster.pdf'

url_pdf: 
url_code: 
url_slides:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Strong Wolfe gap convergence w.r.t. time in seconds for a structured LASSO problem."
  focal_point: "Center"
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
