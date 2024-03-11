---
title: "Data-Driven Measurement of Receiver Sensitivity in Wireless Communication Systems
"
authors:
  - Yuan Ma
  - admin
  - Zhi Quan
  - H. Vincent Poor
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-01-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Communications "
publication_short: "*TCOM*"

abstract: Receiver sensitivity is one of the most important parameters in determining the overall performance of a radio frequency communication system. The traditional receiver sensitivity measurement is to use exhaustive search in a specified range to identify the receiver's sensitivity. However, such an exhaustive search is neither efficient in terms of measurement time, nor accurate due to the fixed step-size. In this paper, a data-driven approach is proposed to measure the receiver sensitivity based on a dynamic linearization representation of a time-varying pseudo-gradient parameter estimation procedure. Unlike the model-based approach, the proposed data-driven approach is dependent only on the input and output measurement data. Furthermore, an analytical approach is presented to derive the minimum number of test packets needed to satisfy the desired confidence level for packet error rate estimation. By adapting the number of test packets, the proposed approach can converge to the exact receiver sensitivity with less time. A theoretical analysis of the proposed approach is provided and further validated by numerical analyses and real-world experimental verification. These analyses show that the proposed data-driven sensitivity measurement can a achieve good estimation performance within a few iterations as well as reduce measurement time.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/8606141/authors#authors
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---