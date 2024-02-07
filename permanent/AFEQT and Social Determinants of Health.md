---
date: 2024-01-16
category: project
stage: working
---

This project was initialized during [[T32 and F32 Research Years]].

# Overview

The AFEQT scores are measured at baseline and at follow-up.
Clinically, patients are managed based on symptoms and then treatment offered.
However, we hypothesized that [[Social Determinants of Health]] (SDOH) factors may affect treatment decisions.

In a study like this, we would need to define informative tables and figures.
This is based on our DAG model and the roles of variables.

Exposures:

	NDI, quartiles 
	Race/Ethnicity
	Language
	Insurance
	Gender/Sex
	
Outcomes:
	
	AFEQT score changes
	Treatment escalation (increased dosage)
	Change from rate to rhythm control strategy
	Referral for intervention (EP, TEE, PVI)
	Anticoagulation recommendations (DOAC v. warfarin)

Confounders:

	Age
	CHA2DS2VASC score
	Clinical comorbidities (composite score?)
	Stroke, previous or new

# Analysis

The statistical methods to analyze these relationships are complex.
One of the outcomes, change in AFEQT score, is not truly independent of the exposure variable (AFEQT at baseline). 
The dependence on the change in AFEQT requires specific adjustment for baseline values in almost all analysis, however from a statistical perspective, there is more to it. 

# Tables & Figures

The overall list of figures and tables need to reflect these decisions
Information must show the type of patient population present

## Table 1: Cohort Description

Potential ideas
- Key grouping by at time of AFEQT baseline
- Rate versus rhythm control strategy 
- Divide by major outcome of AFEQT score change (not standard approach)

## Table 2: AFEQT Scores

Would need to break down by AFEQT score subtype


## Table 3: Predictors of AFEQT Change

## Table 4: NDI Association with AFEQT Change