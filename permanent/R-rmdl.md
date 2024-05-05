---
date: 2024-01-16
category: structure
stage: working
tags:
  - R 
  - programming 
  - software
  - epidemiology 
  - causality
  - methods 
---

The `R` package `{rmdl}` is a software package built to handle and organize multiple models when performing causal-oriented analyses.  The package documentation is located on the [website](https://shah-in-boots.github.io/rmdl) and software development is on [Github](https://github.com/shah-in-boots/rmdl).


# Development

This package is under active development. 
The summary of the versions is below, and serves as an implementation timeline. 
Additionally, descriptions of the major classes, and their development, are described. 
The most up-to-date descriptions will be on the package website.
Additional expansion of the documentation and development process are listed:

- Creation of the major new class `<fmls>` is described at [R-rmdl-formulas](R-rmdl-formulas.md)
- Development of the `<mdl_tbl>` class and its visualization using the `{gt}` package is described at [R-rmdl-tables](R-rmdl-tables.md)

# Versions

## v0.1.0

This milestone represent the initial package release. 
The major introduction is the creation of basic and complex fundamental classes to 

## v0.2.0

This second major milestone for this project is aimed at data visualization. This is essentially a version that allows for expansion of `gt` tables for production quality figures based on styles seen in high-impact journals. The purpose of this package really comes through here, because it flexes the idea that models are related to each other and should be displayed _together_ when appropriate.

The major functionality that is brought in here is these invisible `gt` table constructs. Every model that is stored in a `<mdl_tbl>` may be related, and we can describe those exposure/outcome relationships as a single cell, which is a building block for multiple columns, and multiple rows.

Although the directionality can be flipped, generally speaking each column explains a different `outcome ~ exposure`, and each row changes or modifies the _context_ of that relationship.

With this, more complex display tables can be formed. For example...

1. Forest plots for both stratified analyses and interaction analyses
2. Hazard/survival tables
3. Generalized/linear model tables with sequential (or other) adjustment sets

## v0.3.0

Additional descriptive relationships:

- Adjusted means through the `{emmeans}` package