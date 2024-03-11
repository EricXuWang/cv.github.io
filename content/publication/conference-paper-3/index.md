---
title: 'Malicious Model Detection for Federated Learning Empowered Energy Storage Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yuanzhu Chen
  - Octavia Dobre

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-02-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computing, Networking and Communications*
publication_short: In *ICNC*

abstract: Renewable energy plays an essential role in the energy sector and reducing carbon emissions. Energy storage is the key to releasing the full potential of renewable energy because it offers grid flexibility to ensure uninterrupted power to consumers. As a result, monitoring the operation of energy storage systems and ensuring it functions properly are foremost. Because of data scarcity and privacy concerns, multiple energy storage systems can collectively identify battery failures in a federated manner. However, such a federated learning paradigm introduces vulnerability to the system. Compromised energy storage systems can provide malicious models to jeopardize the convergence and accuracy of the global model. In order to address this problem, we propose an autoencoder-backed malicious model detection framework for federated learning empowered energy storage systems. We construct an autoencoder to calculate the reconstruction error for each updated model. By thresholding the reconstruction error with a predefined value, we are able to identify the malicious model parameters and stop them from model aggregation. Real-world experiments show that the proposed countermeasure efficaciously detects compromised model updates under strong attacks and outperforms state-of-art defense schemes.


# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
