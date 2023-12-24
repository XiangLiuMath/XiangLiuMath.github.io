---
title: "Multiphysical graph neural network (MP-GNN) for COVID-19 drug design"
authors: 
  - Li Xiao-Shuang
  - admin
  - Le Lu
  - Xian-Sheng Hua
  - Ying Chi
  - Kelin Xia

date: "2022-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Briefings in Bioinformatics, 23(4); bbac231"
publication_short: ""

abstract: Graph neural networks (GNNs) are the most promising deep learning models that can revolutionize non-Euclidean data analysis. However, their full potential is severely curtailed by poorly represented molecular graphs and features. Here, we propose a multiphysical graph neural network (MP-GNN) model based on the developed multiphysical molecular graph representation and featurization. All kinds of molecular interactions, between different atom types and at different scales, are systematically represented by a series of scale-specific and element-specific graphs with distance-related node features. From these graphs, graph convolution network (GCN) models are constructed with specially designed weight-sharing architectures. Base learners are constructed from GCN models from different elements at different scales, and further consolidated together using both one-scale and multi-scale ensemble learning schemes. Our MP-GNN has two distinct properties. First, our MP-GNN incorporates multiscale interactions using more than one molecular graph. Atomic interactions from various different scales are not modeled by one specific graph (as in traditional GNNs), instead they are represented by a series of graphs at different scales. Second, it is free from the complicated feature generation process as in conventional GNN methods. In our MP-GNN, various atom interactions are embedded into element-specific graph representations with only distance-related node features. A unique GNN architecture is designed to incorporate all the information into a consolidated model. Our MP-GNN has been extensively validated on the widely used benchmark test datasets from PDBbind, including PDBbind-v2007, PDBbind-v2013 and PDBbind-v2016. Our model can outperform all existing models as far as we know. Further, our MP-GNN is used in coronavirus disease 2019 drug design. Based on a dataset with 185 complexes of inhibitors for severe acute respiratory syndrome coronavirus (SARS-CoV/SARS-CoV-2), we evaluate their binding affinities using our MP-GNN. It has been found that our MP-GNN is of high accuracy. This demonstrates the great potential of our MP-GNN for the screening of potential drugs for SARS-CoV-2.

# Summary. An optional shortened abstract.
# summary: The metabolomic physics of complex diseases.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://academic.oup.com/bib/article-abstract/23/4/bbac231/6607747
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

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
