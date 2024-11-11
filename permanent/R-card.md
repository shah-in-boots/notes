**---
date: 2024-02-02
category: temporary
stage: considering
tags:
  - software
  - R
  - programming
---

The `{card}` package is software written in R. 
It is primarily intended for `Cardiovascular Research Data`, and contains functions that are meant for analysis of cardiology-specific datasets (including billing, medications, electrocardiography, echocardiography, and catheterization data). 

- The major sample datasets are described in [R-card-data](R-card-data.md).


# Versions

## Development version

- Functions to help create an AF composite treatment response score, described in [AF-composite-treatment-response-score](AF-composite-treatment-response-score.md)

## v0.1.0

This version was the first software package I had released on CRAN.
It is limited however by a bug in mean population cosinors that has not yet been resolved. 

## v0.2.0

This version fixes the population cosinor methods, and warns about deprecation of the rhythm-based methods. 
This is the final version supporting cosinors, which are being moved to the developmental package `{orbs}`, described in [R-orbs](R-orbs.md).

