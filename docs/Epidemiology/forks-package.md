---
tags: [r, programming, stats]
---

The `{forks}` package is an attempt to improve upon the formula class. Ideally, it will create the basis for extending formulas in R. 

Developmental needs:

- Formula lists
- Formula prescriptions
- `{broom}` like fit of formulas for multiple models
- Model lists 
- Term descriptions (including roles, labels)
- Operations (such as transformations) prior to creating a model frame
- Comparison of formulas 

The basic functions are a new definition for how formulas should be parsed and handled. Formulas have properties that exist at three levels:

1. Data = how the term relates to a corresponding data vector
1. Terms = how the term itself is positioned within the formula, via its role
1. Formula = how the formula itself is versioned or subset or related to itself (e.g. mediation)

This can be hopefully encapsulated by a vectorized version of a formula, with each term being a base type of `term` with specific properties that emerge into a `formula_frame` object when combined. For example, an individual term will have a side, role, position, type, etc. A vector of formula terms would create a data frame that could be represented as a formula. 

Expansion of this concept is in the [[programming-formula-lists]].