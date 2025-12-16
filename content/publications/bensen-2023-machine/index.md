---
title: A Machine Learning Method for Real-Time Traffic State Estimation from Probe
  Vehicle Data

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Erik A Bensen
- Joseph Severino
- Juliette Ugirumurera
- Qichao Wang
- Jibonananda Sanyal
- Wesley Jones

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-09-24'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-12-15T23:53:59.482675Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2023 IEEE 26th International Conference on Intelligent Transportation
  Systems (ITSC)*'
publication_short: ''

hugoblox:
  ids:
    doi: 'http://dx.doi.org/10.1109/ITSC57777.2023.10422431'

abstract: 'Reliable Traffic State Estimation (TSE) is an important precursor to developing sophisticated traffic controls for intelligent transportation systems (ITS). Historically, TSE is calculated using stationary sensors with occasional vehicle probe data as supplementary data. However, even with recent developments that apply machine learning to TSE calculations, the literature reports having to fuse probe data with stationary data or focus solely on freeways where the penetration is greater. This work proposes and analyzes an Ordinal Regression model developed using XGBoost to compute TSE exclusively from probe data that can be used for real-time model predictive control on signalized corridors. Our results show our model to have an mean absolute error of less than half a class and show promising preliminary results in a real-world control experiment.'

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
