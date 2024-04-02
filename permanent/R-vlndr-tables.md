---
date: 2024-04-01
category: project
stage: building
tags:
  - programming
  - causality
  - R
---

The major purpose of having a new `<fmls>` class was the creation of multiple related models that are stored in the `<mdl_tbl>` class. 
This sequence of models help describe the evolution of an $exposure \rightarrow outcome$ relationship (e.g. sequential adjustment).
The raw data itself is stored within the `<mdl_tbl>`, but the visualization process is a separate issue altogether.
The visualization process requires using the `{gt}` package, but extending it to create a novel multi-model type.

# Visualization of multiple models

To create a new `{gt}`-based class for using and pulling together multiple models, the fundamental features of model tables needs to be explored. 

Below are notes and examples seen on how multiple models can be visualized.

- Forest plots that show hazard ratios on RHS of table, like the subgroup analyses in @Vaccarino2021a
- Sequential adjustment
- Interaction



Forest plots based on interaction terms
Interaction terms need:

```r
> X <- model.matrix(mod)
> dof <- nrow(X) - ncol(X)
> coefs_var <- vcov(mod)
```
