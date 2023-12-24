---
title: "Persistent spectral hypergraph based machine learning (PSH-ML) for protein-ligand binding affinity prediction"
authors: 
  - admin
  - Huitao Feng
  - Jie Wu
  - Kelin Xia

date: "2021-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Briefings in Bioinformatics, 22(5); bbab127"
publication_short: ""

abstract: Molecular descriptors are essential to not only quantitative structure activity/property relationship (QSAR/QSPR) models, but also machine learning based chemical and biological data analysis. In this paper, we propose persistent spectral hypergraph (PSH) based molecular descriptors or fingerprints for the first time. Our PSH-based molecular descriptors are used in the characterization of molecular structures and interactions, and further combined with machine learning models, in particular gradient boosting tree (GBT), for protein-ligand binding affinity prediction. Different from traditional molecular descriptors, which are usually based on molecular graph models, a hypergraph-based topological representation is proposed for protein–ligand interaction characterization. Moreover, a filtration process is introduced to generate a series of nested hypergraphs in different scales. For each of these hypergraphs, its eigen spectrum information can be obtained from the corresponding (Hodge) Laplacain matrix. PSH studies the persistence and variation of the eigen spectrum of the nested hypergraphs during the filtration process. Molecular descriptors or fingerprints can be generated from persistent attributes, which are statistical or combinatorial functions of PSH, and combined with machine learning models, in particular, GBT. We test our PSH-GBT model on three most commonly used datasets, including PDBbind-2007, PDBbind-2013 and PDBbind-2016. Our results, for all these databases, are better than all existing machine learning models with traditional molecular descriptors, as far as we know.
# Summary. An optional shortened abstract.
# summary: The metabolomic physics of complex diseases.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://academic.oup.com/bib/article/22/5/bbab127/6219114
url_code: https://github.com/LiuXiangMath/Persistent-Spectral-Hypergraph
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
