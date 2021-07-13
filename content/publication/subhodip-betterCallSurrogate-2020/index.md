---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Better call Surrogates: A hybrid Evolutionary Algorithm for Hyperparameter optimization"
authors: ["Subhodip Biswas","Adam D Cobb","Andreea Sistrunk","Naren Ramakrishnan","Brian Jalaian"]
date: 2020-12-11
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-07-12T22:19:39-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "NeurIps Black Box Optimization Challenge"
publication_short: ""

abstract: "In this paper, we propose a surrogate-assisted evolutionary algorithm (EA) for hyperparameter optimization of machine learning (ML) models. The proposed STEADE model initially estimates the objective function landscape using RadialBasis Function interpolation, and then transfers the knowledge to an EA technique called Differential Evolution that is used to evolve new solutions guided by a Bayesian optimization framework. We empirically evaluate our model on the hyperparameter optimization problems as a part of the black box optimization challenge at NeurIPS 2020 and demonstrate the improvement brought about by STEADE over the vanilla EA."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Hyper-parameter optimization", "Auto-ML","Bayesian Optimization","Evolutionary Algorithm"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2012.06453.pdf
url_code: https://github.com/subhodipbiswas/BayesianEvolution
url_dataset:
url_poster:
url_project: https://bbochallenge.com/ 
url_slides:
url_source: 
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
