---
title: 'Designing Robust 6G Networks with Bimodal Distribution for Decentralized Federated Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yuanzhu Chen
  - Octavia Dobre

# # Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-05-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Computer Communications*
publication_short: In *INFOCOM*

abstract: Integrating distributed machine learning with 6G technology  is aligned with the United Nations' Sustainable Development Goals, notably in global connectivity and sustainable industrial development. This combination bolsters innovation, contributing significantly to objectives in industry and infrastructure. Large networks are often modeled as variants or compounds of the random or power-law graph. Yet, either random or power-law network presents distinct vulnerabilities -- random networks are susceptible to failures, while power-law networks are more prone to targeted attacks. To address this issue, we propose to create the network topology based on a bimodal degree distribution so that the network is robust against both types of node removals. Such a design features one central hub with a high degree of connections and other nodes having consistently lower degrees. The resilience of this hub-and-spoke configuration against random failures is clear, especially given the small chance of the central hub being impacted. In contrast of a targeted attack, despite the significant risk of losing the hub, the network effectively withstands further node removals thanks to their residual connections. Simulation experiments in decentralized federated learning show that the developed large 6G network topology is resilient to both random failures and targeted attacks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtube.com'


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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
