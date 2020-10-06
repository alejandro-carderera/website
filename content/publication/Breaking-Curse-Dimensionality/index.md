---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Breaking the Curse of Dimensionality (Locally) to Accelerate Conditional Gradients"
authors: [Jelena Diakonikolas, Alejandro Carderera, Sebastian Pokutta]
date: 2019-05-19T13:46:30-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-5-04T13:46:30-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent ; 9 = Workshop
publication_types: ["9"]

# Publication name and optional abbreviated publication name.
publication: "OPT2019: 11th Annual Workshop on Optimization for Machine Learning"
publication_short: "OPT2019"

abstract: "Conditional gradient methods constitute a class of first order algorithms for solving smooth convex optimization problems that are projection-free and numerically competitive. We present the Locally Accelerated Conditional Gradients algorithmic framework that relaxes the projection-freeness requirement to only require projection onto (typically low-dimensional) simplices and mixes accelerated steps with conditional gradient steps to achieve dimensionindependent local acceleration for smooth strongly convex functions. We prove that the introduced class of methods attains the asymptotically optimal convergence rate. Our theoretical results are supported by numerical experiments that demonstrate a speed-up both in wall-clock time and in per-iteration progress when compared to state-of-the-art conditional gradient variants."

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
    icon: file-pdf
    name: PDF
    url: 'https://opt-ml.org/papers/2019/paper_26.pdf'
  - icon_pack: fas
    icon: file
    name: Slides
    url: 'MLOptPresentation.pdf'
  - icon_pack: fas
    icon: file-powerpoint
    name: Poster
    url: 'LaCG_MLOPT2019_v3.pdf'

url_pdf: 
url_code: 
url_slides:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Primal gap convergence comparison: Minimization of quadratic over the convex hull of MIPLIB polytope (ran14x18-disj-8). See paper for details."
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
