---
abstract: "Our ability to measure the masses of exoplanets using the radial velocity (RV) method is limited by stellar variability signals
originating from the star’s surface. To increase the precision of RV measurements, variability signals must be identified, modelled,
and removed. Neural networks have been shown to effectively model stellar variability using cross-correlation functions (CCFs)
for three years of HARPS-N solar observations. In this work, we train a neural network on six years of solar observations and
add additional input features that are likely to correlate with stellar variability. In particular, we compared models that include
white light CCFs, bisector of CCFs, contrast of CCFs, FWHM of CCFs, total solar irradiance (TSI), TSI time derivative, s-index,
H𝛼 and NaD lines, unsigned magnetic flux, and chromatic CCFs. We compare models that only include CCFs with models that
include the CCFs and additional input features. We find that adding several commonly used features (FWHM, Bisector, H𝛼, NaD)
does not reduce the RV scatter compared to the CCF-only model. However, we find that adding several other features (unsigned
magnetic flux, TSI, S-Index, and chromatic CCFs) predict the RV jitter best and reduce the RV scatter 154.7 cm/s
to 92.1 cm/s. Recent work has shown that this noise floor is similar to the expected jitter from solar granulation and supergranulation
of 93.6 cm/s. In the future, finding effective tracers for (super)granulation may be critical to reaching lower RV jitter, and
paving the way towards detecting Earth-twins."
author_notes:
- First-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
- Co-author
authors:
- admin
- Zoë L. de Beurs
- Andrew Vanderburg
- Javier Viaña
- Annelies Mortier
- Lars A. Buchhave
- Andrew Cameron
- Rosario Cosentino
- Xavier Dumusque
- Adriano Ghedina
- Ben Lakeland 
- Marcello Lodi
- Mercedes López-Morales 
- Dimitar Sasselov
- Alessandro Sozzetti
#date: "2017-03-01T00:00:00Z"
doi: ""
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false
projects: []
publication: 'Submitted to MNRAS'
publication_short: ""
publication_types:
- article-journal
publishDate: "2023-12-12T00:00:00Z"
#slides: example
summary: ""
tags:
- "techniques: radial velocities"
- "methods: data analysis"
- "Sun: activity"
- "stars: activity"
title: Identifying Exoplanets with Deep Learning VI. Enhancing neural network mitigation of stellar activity RV signals with additional metrics
url_code: ""
url_dataset: ""
url_pdf: "https://drive.google.com/file/d/18qL7ovq-sgRNA6lCVabl_CGMWPhlY449/view?usp=sharing"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

{{% callout note %}}
Paper has been submitted to MNRAS on December 2023 and is currently under peer review
{{% /callout %}}