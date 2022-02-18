---
tags: [programming, stats, r]
---

# Overview

1. Formulas should have roles/positions to help identify their roles in the corresponding DAG. These formulas should also be _expandable_ as needed to encompass the variety of relationships. 
1. Formulas should have multiple levels.  Essentially should have a "top level" formula that can be broken into separate or related DAGs. This is probably the back-bone structure.
1. DAG should be visualized with both weights (like SEM), and unweighted, to understand relationships. This might best be done based off of `ggdag` and `dagitty` as the backbone. 
1. Model and model lists are also needed. They are essentially the _fit_ version of the formulas and have an additional, associated test type. 
1. Models cannot have a the same scope as the "top level" formula, they must be simplifed to a single testable item. However, they can likely be grouped into model lists that are related.

### Key Concepts

| Concept |  Models | Formulas |
| --- | --- | --- | 
| Relationships | Multiple | Multiple |
| Expandable | Yes | Yes |
| Collapsable | No | Yes |
| Directionality | Specified | Specified |
| Levels | Multiple | Multiple |
| Core | No | Yes |

# Major Classes

The major classes that would be needed are...

- Formula List (a clean way to combine formulas for a shared interspace)
- Paths (a combination of formula lists that represent a hypothesis or causal model)
- Maps (a combination of paths that may come from the same data set)

Exploration of these classes and potential implementation in S3 and S4 are here [[programming-dag-classes]].