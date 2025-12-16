---
title: Addressing bias in bagging and boosting regression models

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Juliette Ugirumurera
- Erik A Bensen
- Joseph Severino
- Jibonananda Sanyal

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-08-08'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-12-15T23:53:59.491699Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Scientific Reports*'
publication_short: ''

hugoblox:
  ids:
    doi: 'http://dx.doi.org/10.1038/s41598-024-68907-5'

abstract: 'As artificial intelligence (AI) becomes widespread, there is increasing attention on investigating bias in machine learning (ML) models. Previous research concentrated on classification problems, with little emphasis on regression models. This paper presents an easy-to-apply and effective methodology for mitigating bias in bagging and boosting regression models, that is also applicable to any model trained through minimizing a differentiable loss function. Our methodology measures bias rigorously and extends the ML model’s loss function with a regularization term to penalize high correlations between model errors and protected attributes. We applied our approach to three popular tree-based ensemble models: a random forest model (RF), a gradient-boosted model (GBT), and an extreme gradient boosting model (XGBoost). We implemented our methodology on a case study for predicting road-level traffic volume, where RF, GBT, and XGBoost models were shown to have high accuracy. Despite high accuracy, the ML models were shown to perform poorly on roads in minority-populated areas. Our bias mitigation approach reduced minority-related bias by over 50%.'

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
