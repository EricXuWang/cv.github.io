---
title: 'Robust Federated Learning for Energy Storage Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yuanqi Liang
  - Yuanzhu Chen
  - Octavia Dobre

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-04-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Wireless Communications and Networking Conference*
publication_short: In *WCNC*

abstract: One of the Sustainable Development Goals of the United Nations is affordable and clean energy. True utilization of renewable energy is only possible via battery-based energy storage systems. Overseeing the operation of battery-based energy storage systems and diagnosing abnormal batteries are of the utmost importance for their durability and stability. Because of inadequate anomalous samples and privacy considerations, we jointly train a global autoencoder on various battery-based energy storage systems to detect anomalous batteries. Due to potentially unstable network connectivity in energy storage systems, a chunk of model parameters may be lost during model transmission, leading to dramatic performance deterioration. The trained model tends to classify all measurements as anomalies To solve this problem, we propose a robust federated learning scheme to mitigate negative impact caused by packet loss during model transmission. By permuting and unpermuting model parameters before and after model transmission, we are able to distribute the lost parameters across the entire model. Such a loss can no longer have a significant negative impact on anomalous battery detection. Experimental results illustrate that the proposed algorithm is robust against packet loss during the model exchange between the cloud server and battery-based energy storage systems..

# Summary. An optional shortened abstract.
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
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
