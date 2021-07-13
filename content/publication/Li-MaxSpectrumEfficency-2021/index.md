---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Maximize Spectrum Efficiency in Underlay Coexistence With Channel Uncertainty"
authors: ["Shaoran Li", "Yan Huang", "Chengzhang Li", "Brian Jalaian", "Y. Thomas Hou", "Wenjing Lou", "Stephen Russell"]
date: 2021-01-12
doi: "https://doi.org/10.1109/TNET.2020.3047760"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-07-12T22:44:22-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Networking"
publication_short: "IEEE/ACM ToN"

abstract: "We consider an underlay coexistence scenario where secondary users (SUs) must keep their interference to the primary users (PUs) under control. However, the channel gains from the PUs to the SUs are uncertain due to a lack of cooperation between the PUs and the SUs. Under this circumstance, it is preferable to allow the interference threshold of each PU to be violated occasionally as long as such violation stays below a probability. In this article, we employ Chance-Constrained Programming (CCP) to exploit this idea of occasional interference threshold violation. We assume the uncertain channel gains are only known by their mean and covariance. These quantities are slow-changing and easy to estimate. Our main contribution is to introduce a novel and powerful mathematical tool called Exact Conic Reformulation (ECR), which reformulates the intractable chance constraints into tractable convex constraints. Further, ECR guarantees an equivalent reformulation from linear chance constraints into deterministic conic constraints without the limitations associated with Bernstein Approximation, on which our research community has been fixated on for years. Through extensive simulations, we show that our proposed solution offers a significant improvement over existing approaches in terms of performance and ability to handle channel correlations (where Bernstein Approximation is no longer applicable)."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Network Optimization", "Uncertainty Quantification", "Cognitive Radio", "Spectrum Sharing"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/abstract/document/9321155
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
