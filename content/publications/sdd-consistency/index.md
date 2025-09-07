---
title: "Spectral Differential Network Analysis for High‑dimensional Time Series"
authors:
- admin
- Byol Kim
- Zaid Harchaoui
- Ali Shojaie
date: "2025-07-21"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-29"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: [""]

# Publication name and optional abbreviated publication name.
publication: "*AISTATS*"
publication_short: ""

abstract: "Spectral networks derived from multivariate time series data arise in many domains, from brain science to Earth science. Often, it is of interest to study how these networks change under different conditions. For instance, to better understand epilepsy, it would be interesting to capture the changes in the brain connectivity network as a patient experiences a seizure, using electroencephalography data. A common approach relies on estimating the networks in each condition and calculating their difference. Such estimates may behave poorly in high dimensions as the networks themselves may not be sparse in structure while their difference may be. We build upon this observation to develop an estimator of the difference in inverse spectral densities across two conditions. Using an $\ell_1$ penalty on the difference, consistency is established by only requiring the difference to be sparse. We illustrate the method on synthetic data experiments and on experiments with electroencephalography data."

# Summary. An optional shortened abstract.
summary: 

tags:

featured: true

url_pdf: "https://arxiv.org/pdf/2412.07905"
url_code: "https://github.com/mikehellstern/spectral-differential-networks" 
---

**Summary:** We develop a new method to directly measure how complex networks of time-dependent signals, such as brain connectivity, change under different conditions. To our knowledge, our approach is the only method that directly targets a differential network in the frequency domain.
