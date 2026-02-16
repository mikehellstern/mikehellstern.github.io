---
title: "Dynamic Deep Learning for Detecting Changes in Biomedical Processes"
authors:
- admin
- Ali Shojaie
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-27"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: [""]
publication_type_show: false

# Publication name and optional abbreviated publication name.
publication: "*In preparation*"
publication_short: ""

abstract: "With the recent success of deep learning across a variety of fields, it is natural to consider if such methods can be leveraged in change-point detection. While existing deep learning-based change-point detection methods exist, they are often limited to specific architectures or require sample splitting or multiple data sequences for training and validation. We propose Dynamic Deep Learning (DDL), a flexible framework that allows the use of any deep learning architecture for change-point detection and does not require sample splitting. We introduce the core concepts of the framework and compare DDL to existing deep learning and benchmark methods in several simulation settings. DDL outperforms existing methods across a variety of simulation settings and metrics. These findings are confirmed when detecting change-points in COVID-19 outcomes in NYC, where DDL performs better at recovering notable events such as new COVID variants and introduction of vaccines."
abstract_show: false

# Summary. An optional shortened abstract. MH note - don't actually need this
summary: "Insert description"


featured: true

url_pdf: ''
url_slides: ''
---

**Summary:** We introduce Dynamic Deep Learning (DDL), a flexible framework for change-point detection that can use any deep learning architecture without requiring sample splitting or multiple data sequences. In simulations, DDL consistently outperforms existing deep learning and benchmark methods. Applied to COVID-19 data from NYC, DDL accurately identifies major events such as new variants and vaccine rollouts.