---
title: Sampling-based surrogate likelihood inference for spatial warping error models with applications to aerosol simulations

reading_time: false
event: Joint Statistical Meeting 2025
event_url: https://ww2.amstat.org/meetings/jsm/2025/index.cfm

location: Music City Center
address:
  # street: 450 Serra Mall
  city: Nashville
  region: TN
  # postcode: '94305'
  # country: United States

summary: 
abstract: 'Complex simulators of physical processes are used increasingly often for scientific applications. However, the parameters governing these physical processes can be highly uncertain so reducing this uncertainty is important for improving the accuracy of simulator predictions. To this end, a growing amount of work focuses on constraining these physical parameters by comparing the simulator outputs to corresponding real-world observations. However, these simulators can often be systematically misspecified which requires accounting for this model discrepancy when inferring model parameters. Existing work does this by incorporating a data-driven additive model discrepancy error but this treatment does not necessarily represent how we expect many simulators to be misspecified. In particular, for simulators that output spatial fields, we hypothesize that misspecification could lead to spatial warping errors between the simulation and observations where the simulated structure of a spatial feature may be correct overall but it is displaced in space or distorted in shape. To address this, we propose a novel spatiotemporal modeling framework and estimation procedure that models the spatial warping errors as random transport maps that capture these spatial distortions. Our method generates plausible transport maps using convex Gaussian processes that preserve the spatial structure of the simulation. However, using this shape-constrained process results in a challenging likelihood-free inference problem. We demonstrate how inference is nevertheless possible using sampling-based surrogate likelihoods which we estimate and maximize using exact Hamiltonian Monte Carlo sampling and Neural Likelihood techniques. As a concrete application of our methodology, we consider the UKESM1 climate model and remotely sensed aerosol observations where we expect misspecification in atmospheric dynamics or meteorology to lead to spatial warping errors. Our results show that modeling spatial warping errors yields significantly higher likelihoods and stronger parameter-constraining capabilities compared to models that rely solely on additive errors. '

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-08-05T14:00:00Z'
date_end: #'2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-08-10T00:00:00Z'

authors:
  - me

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**ASA**](https://ww2.amstat.org/meetings/jsm/2025/index.cfm)'
  focal_point: Right

links:
  - name: Conference Website
    url: https://ww2.amstat.org/meetings/jsm/2025/index.cfm

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  # - tmg-hmc
---

<!-- > [!NOTE]
> Click on the **Slides** button above to view the built-in slides feature.

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using the `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to this page bundle and link it using `links: [{ type: slides, url: path/to/file } ]` in front matter
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->

<!-- <iframe src="Bensen_JSM_2025.pdf" width="100%" height="600px" style="border: 1px solid #ccc;">
  <p>Your browser does not support embedded PDFs. 
     <a href="Bensen_JSM_2025.pdf">Download the slides</a>.</p>
</iframe> -->