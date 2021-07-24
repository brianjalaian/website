---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Fountain Coding for Information Protection in Tactical Networks"
authors: ["Vignesh Sridharan","Mehul Motani","Brian Jalaian","Niranjan Suri"]
date: 2021-05-04
doi: "https://doi.org/10.1109/ICMCIS52405.2021.9486393"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-07-24T14:26:32-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Military Communication and Information Systems"
publication_short: "ICMCIS"

abstract: "Tactical edge networks are operated in harsh conditions where ensuring information protection is a challenging issue. An insider threat is one of the major issues that arises in such scenarios. For instance, an attacker can compromise one of the nodes and intercept information that is being relayed to other nodes. In this paper, we propose Fountain Coding for Information Protection (FCIP) to mitigate this threat. The source node encodes information from k source symbols into m messages before sending them over the network and the receiver must recover at least k messages to decipher the information. To mitigate the insider threat, we route the encoded packets along disjoint paths. However, this incurs a trade-off with information availability as the encoded packets are routed along sub-optimal paths. It is also necessary to determine the portion of traffic to encode as encoding all the traffic is resource intensive. We formulate a multi-objective optimization problem that takes into account information protection while trading-off with information availability and considers bandwidth, energy and availability constraints. We model a risk metric to determine the cost of information protection that is provided and a cost metric to quantify the cost of information availability. We demonstrate the benefit of FCIP in our performance study by comparing it against a shortest path routing solution and provide optimal results for FCIP. We analyze the trade-off between information protection and availability and provide insight on the performance and benefits of FCIP for different operational scenarios."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Information Protection","Cyber Security","Fountain Coding"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/abstract/document/9486393
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
