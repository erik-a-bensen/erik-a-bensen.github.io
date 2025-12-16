---
title: 'Measuring the energy consumption and efficiency of deep neural networks: An
  empirical analysis and design recommendations'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Charles Edison Tripp
- Jordan Perr-Sauer
- Jamil Gafur
- Amabarish Nag
- Avi Purkayastha
- Sagi Zisman
- Erik A Bensen

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-12-15T23:53:59.487184Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint arXiv:2403.08151*'
publication_short: ''

hugoblox:
  ids:
    doi: 'https://doi.org/10.48550/arXiv.2403.08151'

abstract: 'Addressing the so-called "Red-AI" trend of rising energy consumption by large-scale neural networks, this study investigates the actual energy consumption, as measured by node-level watt-meters, of training various fully connected neural network architectures. We introduce the BUTTER-E dataset, an augmentation to the BUTTER Empirical Deep Learning dataset, containing energy consumption and performance data from 63,527 individual experimental runs spanning 30,582 distinct configurations: 13 datasets, 20 sizes (number of trainable parameters), 8 network "shapes", and 14 depths on both CPU and GPU hardware collected using node-level watt-meters. This dataset reveals the complex relationship between dataset size, network structure, and energy use, and highlights the impact of cache effects. We propose a straightforward and effective energy model that accounts for network size, computing, and memory hierarchy. Our analysis also uncovers a surprising, hardware-mediated non-linear relationship between energy efficiency and network design, challenging the assumption that reducing the number of parameters or FLOPs is the best way to achieve greater energy efficiency. Highlighting the need for cache-considerate algorithm development, we suggest a combined approach to energy efficient network, algorithm, and hardware design. This work contributes to the fields of sustainable computing and Green AI, offering practical guidance for creating more energy-efficient neural networks and promoting sustainable AI.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

<!-- Add the **full text** or **supplementary notes** for the publication here using Markdown formatting. -->
