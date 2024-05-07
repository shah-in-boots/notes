---
date: 2024-03-26
category: project
stage: questioning
tags:
  - afib
  - research
  - treatment
---

flecainide and sotalol response
missing data of AF 
have ECG, Holter, loop at random
Have AFEQT
have echo data?

The treatment response for atrial fibrillation can be measured across three different axes:

1. Symptoms = perception of quality of life, include exertional capacity, cardiovascular hemodynamics, and psychological correlations that contribute
1. Structural = atrial remodeling, positive and negative, in setting of atrial fibrillation
1. Functional = characteristics defined by the elecrical capacity for maintaining atrial fibrillation

Interventions or treatment strategies include:

- increasing rate control with VW II or VW IV agents
- rhythm control strategy with initiation of VW I or III agents
- electrical cardioversion
- pulmonary vein isolation
- AV nodal ablation with cardiac resynchronization therapy


# Programmatic Approach (in R)


## Input 

__Inputs__ should reflect the potential and optional variables that will compose the weighted score.

- current date to help reference recency of previous data

### Electrical burden

- ECG data from past XXX months?

### Cardiomyopathy burden

- LVEF
- LA size
- LA strain

### Symptom burden

- AFEQT global score 
- AFEQT individal domain scores

## Output

__Outputs__ should be the potential "weight" to help categorize or make a decision about the treatment response status.

- Relative value on some scale... e.g. Likert 1-7?
- Category of treatment response (e.g. yes/no, or categorical/ordinal)

## Map

```mermaid
flowchart LR
	ECG["ECG(n)"] --> ECGs["ECG Density"]
```