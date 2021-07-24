---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Decentralized Bayesian Learning with Metropolis-Adjusted Hamiltonian Monte Carlo"
authors: ["Vyacheslav Kungurtsev","Adam Cobb","Tara Javidi","Brian Jalaian"]
date: 2021-07-15
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-07-24T15:18:33-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: ""

# Summary. An optional shortened abstract.
summary: "Federated learning performed by a decentralized networks of agents is becoming increasingly important with the prevalence of embedded software on autonomous devices. Bayesian approaches to learning benefit from offering more information as to the uncertainty of a random quantity, and Langevin and Hamiltonian methods are effective at realizing sampling from an uncertain distribution with large parameter dimensions. Such methods have only recently appeared in the decentralized setting, and either exclusively use stochastic gradient Langevin and Hamiltonian Monte Carlo approaches that require a diminishing stepsize to asymptotically sample from the posterior and are known in practice to characterize uncertainty less faithfully than constant step-size methods with a Metropolis adjustment, or assume strong convexity properties of the potential function. We present the first approach to incorporating constant stepsize Metropolis-adjusted HMC in the decentralized sampling framework, show theoretical guarantees for consensus and probability distance to the posterior stationary distribution, and demonstrate their effectiveness numerically on standard real world problems, including decentralized learning of neural networks which is known to be highly non-convex."

tags: ["Distributed Learning", "Decentralized Learning", "Uncertainty Quantification", "Bayesian Machine Learning", "Federated Learning"]
categories: []
featured: True

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2107.07211.pdf
url_code:
url_dataset:
url_poster:
url_project:
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
