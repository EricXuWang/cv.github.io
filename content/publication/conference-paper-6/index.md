---
title: 'Fast Data-Driven Sensitivity Measurement for Wireless Receivers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhi Quan
  - Yuan Ma
  - Weisheng Tang
  - H. Vincent Poor

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-05-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Communications*
publication_short: In *ICC*

abstract: Receiver sensitivity is one of the most important performance metrics in communication systems. Industry has been using exhaustive search in a specified range to identify the sensitivity of a receiver. However, such an exhaustive search is neither efficient in terms of measurement time, nor accurate due to the fixed step-size. In this paper, a data-driven approach is proposed to measure the receiver sensitivity based on a dynamic linearization representation of a time-varying pseudo-gradient parameter estimation procedure. Unlike the model-based approach, the proposed data-driven approach is dependent only on the input and output measurement data. In addition, we derive the minimum number of test packets needed to satisfy the desired confidence level for packet error rate estimation. By adapting the number of test packets, we are able to further reduce the measurement time. Numerical analyses and experimental results show that the proposed data-driven sensitivity measurement can achieve good estimation performance as well as reduce measurement time.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8761438'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---