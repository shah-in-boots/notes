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
The inspiration for this comes from articles and tables seen in publication, which seem to show repeating patterns that likely can be replicated and atomized.

- In work by @Vaccarino2021, several examples are seen. The most helpful are *Table 3* and *Figure 2*, which are a Cox model regression table and forest plots for interaction, respectively.  These are seen in [Vaccarino2021](../literature/Vaccarino2021.md)
	- Table 3
		- Vertical columns: incidence by event, rate differences, hazard ratios
		- Vertical groups: cohorts
		- Horizontal groups: outcome types
	- Figure 2
		- Verticle groups: none
		- Vertical columns: incidence by event, rate per 100-patient years, absolute rate difference (per 100-years), hazard ratios
		- Plot (vertical): forest plot (left and right of x-intercept of neutral/null has directional labels), P-values by interaction
		- Horizontal groups: categorical variables, p-values for interaction in forest plot
		- Horizontal rows: levels of categorical/binary variables
		- Horizontal axis: relegated to only forest plot, axis with labels

# Structure of model tables

The most atomic element is the point-estimates $\pm$ confidence intervals. 
This atom represents a relationship between an `outcome ~ exposure`. 
That may be in the form of a regression, risk ratio, incidence, etc.

This relationship can be of different types:

- beta estimates
- risk ratio
- rate ratio
- odds ratio
- hazard ratio
- incidence/prevalence
- mean $\pm$ adjustment

This relationship can be compared in a variety of *contexts*:

- sequential adjustment
- parallel adjustment