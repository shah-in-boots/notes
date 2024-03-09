---
date: 2024-02-25
category: project
stage: building
tags:
  - programming
  - R
  - survival
  - statistics
  - epidemiology
---

The `R` package `{rcr}` is focused on recurrent events, both for outcomes and covariates/exposures. 
The package is built not to perform the analysis, but to simplify the data-cleaning process and extends the `{survival}` package in `R`. 

# Versions

## v0.1.0

The first milestone will be the simple `recur()` function to handle outcomes.

## v0.2.0 

The second milestone will be the simple `recur()` function to allow inclusion of exposure/covariate terms. 
This argument needs to be available but limited in version __v0.1.0__ to simplify package updates.

## v0.3.0

# Development

Development:
- Consider implementing time-dependent covariates in data reshaping
- Remove for loops from data cleaning method
