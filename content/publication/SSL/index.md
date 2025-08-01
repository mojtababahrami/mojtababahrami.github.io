---
title: 'Delineating the effective use of self-supervised learning in single-cell genomics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - T Richter
  - admin
  - Y Xia
  - DS Fischer
  - FJ Theis

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: '2024-12-27T00:00:00Z'
doi: '10.1038/s42256-024-00934-3'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Nature Machine Intelligence*
publication_short: In *NMI*

abstract: Self-supervised learning (SSL) has emerged as a powerful method for extracting meaningful representations from vast, unlabelled datasets, transforming computer vision and natural language processing. In single-cell genomics (SCG), representation learning offers insights into the complex biological data, especially with emerging foundation models. However, identifying scenarios in SCG where SSL outperforms traditional learning methods remains a nuanced challenge. Furthermore, selecting the most effective pretext tasks within the SSL framework for SCG is a critical yet unresolved question. Here we address this gap by adapting and benchmarking SSL methods in SCG, including masked autoencoders with multiple masking strategies and contrastive learning methods. Models trained on over 20 million cells were examined across multiple downstream tasks, including cell-type prediction, gene-expression reconstruction, cross-modality prediction and data integration. Our empirical analyses underscore the nuanced role of SSL, namely, in transfer learning scenarios leveraging auxiliary data or analysing unseen datasets. Masked autoencoders excel over contrastive methods in SCG, diverging from computer vision trends. Moreover, our findings reveal the notable capabilities of SSL in zero-shot settings and its potential in cross-modality prediction and data integration. In summary, we study SSL methods in SCG on fully connected networks and benchmark their utility across key representation learning scenarios.

# Summary. An optional shortened abstract.
summary: Self-supervised learning (SSL) has emerged as a powerful method for extracting meaningful representations from vast, unlabelled datasets, transforming computer vision and natural language processing. ...

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.nature.com/articles/s42256-024-00934-3'
url_code: 'http://github.com/theislab/ssl_in_scg'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'SSL'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
