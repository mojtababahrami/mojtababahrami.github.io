---
title: "Deep feature extraction of single-cell transcriptomes by generative adversarial network"
authors:
- admin
- M. Maitra
- C. Nagy
- G. Turecki
- H.R. Rabiee
- Y. Li

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2020-12-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Bioinformatics*"
publication_short: "Bioinformatics"

abstract: Single-cell RNA-sequencing (scRNA-seq) offers the opportunity to dissect heterogeneous cellular compositions and interrogate the cell-type-specific gene expression patterns across diverse conditions. However, batch effects such as laboratory conditions and individual-variability hinder their usage in cross-condition designs. Here, we present a single-cell Generative Adversarial Network (scGAN) to simultaneously acquire patterns from raw data while minimizing the confounding effect driven by technical artifacts or other factors inherent to the data. Specifically, scGAN models the data likelihood of the raw scRNA-seq counts by projecting each cell onto a latent embedding. Meanwhile, scGAN attempts to minimize the correlation between the latent embeddings and the batch labels across all cells. We demonstrate scGAN on three public scRNA-seq datasets and show that our method confers superior performance over the state-of-the-art methods in forming clusters of known cell types and identifying known psychiatric genes that are associated with major depressive disorder. The scGAN code and the information for the public scRNA-seq datasets are available [here](https://github.com/li-lab-mcgill/singlecell-deepfeature).

# Summary. An optional shortened abstract.
summary: Single-cell RNA-sequencing (scRNA-seq) offers the opportunity to dissect heterogeneous cellular compositions and interrogate the cell-type-specific gene expression patterns across diverse conditions. However ...

tags:

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://academic.oup.com/bioinformatics/article/37/10/1345/5998665#:~:text=Article%20history-,PDF,-Split%20View'
url_code: 'https://github.com/li-lab-mcgill/singlecell-deepfeature'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://academic.oup.com/bioinformatics/article/37/10/1345/5998665'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'scGAN'
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
