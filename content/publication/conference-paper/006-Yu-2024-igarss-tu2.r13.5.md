---
title: 'Empirical Upscaling of Point-scale Soil Moisture Measurements for Spatial Evaluation of Model Simulations and Satellite Retrievals'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Brendan P. Malone
  - Luigi J. Renzullo

# Author notes (optional)
author_notes:

date: '2024-07-07T00:00:00Z'
doi: 'https://doi.org/10.1109/IGARSS53475.2024.10642763'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-07T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE International Geoscience and Remote Sensing Symposium (IGARSS 2024)*
publication_short:

abstract: The evaluation of modelled or satellite-derived soil moisture (SM) estimates is usually dependent on comparisons against in-situ SM measurements. However, the inherent mismatch in spatial support (i.e., scale) necessitates a cautious interpretation of point-to-pixel comparisons. The upscaling of the in-situ measurements to a commensurate resolution to that of the modelled or retrieved SM will lead to a fairer comparison and statistically more defensible evaluation. In this study, we presented an upscaling approach that combines spatiotemporal fusion with machine learning to extrapolate point-scale SM measurements from 28 in-situ sites to a 100 m resolution for an agricultural area of 100 km by 100 km. We conducted a four-fold cross-validation, which consistently demonstrated comparable correlation performance across folds, ranging from 0.6 to 0.9. The proposed approach was further validated based on a cross-cluster strategy by using two spatial subsets within the study area, denoted as cluster A and B, each of which equally comprised of 12 in-situ sites. The cross-cluster validation underscored the capability of the upscaling approach to map the spatial variability of SM within areas that were not covered by in-situ sites, with correlation performance ranging between 0.6 and 0.8. In general, our proposed upscaling approach offers an avenue to extrapolate point measurements of SM to a spatial scale more akin to climatic model grids or remotely sensed observations. Future investigations should delve into a further evaluation of the upscaling approach using independent data, such as model simulations, satellite retrievals or field campaign data.

# Summary. An optional shortened abstract.
summary: Experiments to upscale in-situ soil moisture to satellite footprints.

tags:
  - Soil moisture

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
  caption: ''
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
slides: 
  - example
---
