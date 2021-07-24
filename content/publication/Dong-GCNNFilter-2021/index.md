---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Graph Neural Networks with Adaptive Frequency Response Filter"
authors: ["Yushun Dong", "Kaize Ding", "Brian Jalaian", "Shuiwang Ji", "Jundong Li"]
date: 2021-04-26
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-07-12T23:06:02-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Graph Neural Networks have recently become a prevailing paradigm for various high-impact graph learning tasks. Existing efforts can be mainly categorized as spectral-based and spatial-based methods. The major challenge for the former is to find an appropriate graph filter to distill discriminative information from input signals for learning. Recently, attempts such as Graph Convolutional Network (GCN) leverage Chebyshev polynomial truncation to seek an approximation of graph filters and bridge these two families of methods. It has been shown in recent studies that GCN and its variants are essentially employing fixed low-pass filters to perform information denoising. Thus their learning capability is rather limited and may over-smooth node representations at deeper layers. To tackle these problems, we develop a novel graph neural network framework AdaGNN with a well-designed adaptive frequency response filter. At its core, AdaGNN leverages a simple but elegant trainable filter that spans across multiple layers to capture the varying importance of different frequency components for node representation learning. The inherent differences among different feature channels are also well captured by the filter. As such, it empowers AdaGNN with stronger expressiveness and naturally alleviates the over-smoothing problem. We empirically validate the effectiveness of the proposed framework on various benchmark datasets. Theoretical analysis is also provided to show the superiority of the proposed AdaGNN."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Graph Convolutional Network", "GCN", "Deep Learning", "Supervised Machine Learning", "Machine Learning"]
categories: []
featured: True

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2104.12840.pdf
url_code: https://github.com/yushundong/AdaGNN
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
