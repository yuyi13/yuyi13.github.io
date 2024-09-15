---
title: "Spatial Soil Moisture Prediction from In-Situ Data Upscaled to Landsat Footprint Across Heterogeneous Agricultural Landscapes"
authors:
- admin
- Brendan P. Malone
- Luigi J. Renzullo
- Chad A. Burton
- Siyuan Tian
- Ross D. Searle
- Thomas F. A. Bishop
- Jeffrey P. Walker
date: "2024-06-21T00:00:00Z"
doi: "https://doi.org/10.2139/ssrn.4873038"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-21T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The inherent spatial mismatch between satellite-derived and ground-observed near-surface soil moisture (SM) data necessitates cautious interpretation of point-to-pixel comparisons. While upscaling of point-scale SM presents the potential for a statistically defensible comparison, it is often restricted to localised conditions and has overlooked quantifying the uncertainty in assessing the reliable spatial extent for making SM estimates. This gap underscores the need of addressing the prediction uncertainties and extrapolating SM information to a broader spatial scale. Accordingly, this study presents a spatial prediction approach, which integrates machine learning (ML) and spatiotemporal fusion, to extrapolate point-scale SM from in-situ sites to a 100 km × 100 km area at 100 m resolution. Herein 28 stations were used covering both a cross-validation period (2016-2019) and an independent test period (2020-2021). The area of applicability (AOA), which represents the spatial extent within which a ML model can be reliably applied, was determined for two ML models; Random Forests (RF) and eXtreme Gradient Boosting (XGB). The AOA of RF and XGB models encompassed 43.1% and 41.5% of the study area, respectively, with an expected unbiased root mean squared error (ubRMSE) of 0.05 m3/m3 and correlation coefficient (R) of 0.78 against input training data. The spatial SM prediction within the AOA was then evaluated against multiple independent observations, including data from field campaigns using the Hydraprobe Data Acquisition System (HDAS), two additional SM networks, and level 2 data of the Soil Moisture Active Passive mission (SMAP L2). Results showed that the spatial SM estimates predicted by the RF model were more robust and had better agreement with observations than that of XGB. Specifically, during the cross-validation period, the RF-based spatial SM prediction achieved a spatial R of 0.62-0.64 against HDAS SM, a temporal R of 0.84-0.91 against independent SM network stations, and a spatiotemporal R of 0.87 against SMAP L2 data, respectively. Notably, spatial SM prediction within the AOA demonstrated markedly lower ubRMSE against SMAP L2 compared to that outside the AOA. Overall, this study demonstrated the capability of using an AOA to quantify the spatial extent within which SM could be reliably predicted by ML models, being influenced by regional nuances of landscapes in training strategies.

# Summary. An optional shortened abstract.
summary: 

tags:
- Soil moisture

featured: false

links:
- name:
  url:
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
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
- example
---
