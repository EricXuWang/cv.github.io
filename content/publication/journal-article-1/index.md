---
title: "A Fast Self-Jamming Cancellation Architecture and Algorithm for Passive RFID Sensor System"
authors:
- Chuankui Shen
- Haoqiu Xiong
- admin
- Fengcheng Mei
- Terry Tao Ye
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-03-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Communications Letters"
publication_short: "*ICL*"

abstract: In this letter, we propose a fast self-jamming cancellation (SJC) architecture for Ultra High Frequency (UHF) radio-frequency identification (RFID) interrogators. The core SJC architecture includes a Field Programmable Gate Array (FPGA) as the RFID baseband processor, a radio frequency (RF) agile transceiver which has two transmitting ports as the RF front-end, and a combiner. By detecting the amplitude and phase of the interference carrier, the SJC algorithm transmits a suppression carrier through the second transmitting port of the agile RF transceiver. The suppression carrier could effectively suppress the self-jamming carrier without designing complex circuits. Our test results showed the isolation between the transmitting and receiving port achieves 100dB at UHF band, and the cancellation processes can be finished within 0.4ms.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/9380725/authors#authors
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---