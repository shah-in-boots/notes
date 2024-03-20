---
date: 2024-03-19
category: project
stage: building
tags:
  - todo
  - electrocardiogram
  - genetics
---

1. Introduction
	- Reason for this project 
	- Importance of substrate in AF
	- Role of genetics in AF pathogenesis
	- Hypothesis and proposal
1. Methods
	- Electrocardiography
	- Genetic variant selection
	- Machine learning methods
	- Sensitivity analyses
1. Results
	- Cohort description
	- TTN variants
	- ECG data collection 
	- Machine learning approach
1. Discussion
	- Key findings
	- Role of ECG in AF analysis
	- Future directions
	- Conclusion

# Introduction

## Background

- @Chaudhari2023 looked at ECG predictors of myocardial ischemia/injury
- @Verweij2020 shows markers on the ECG associated with genetic variants from the UK Biobank
- ECG can supplement genetic and clinical factors to predict risk of AF, such as work by @Wang2023
- @vandeLeur2021 identifies ECG features that mark certain genetic arrhythmic conditions, such as phospholambdan mutants
- @Tereshchenko2018 looked at GWAS for patients with abnormalities in GEH
- @Kerr2017 looked at heart rate variability and genetic variants

## Substrate phenotypes

AF arrhythmogenesis is predicated on:
1. Afterdepolarization-based triggered events
1. Areas of automaticity in the atria
1. Atrial tissue that can maintain and sustain re-entry (driven by the above)

## Proposal

# Methods

## Cohort description

## Electrocardiography

## Genetic variants

## Machine learning approach

@Siontis2021 notes that artificial intelligence methods can be used in CVD risk prediction.
@vandeLeur2021 describes the methodology of using deep neural networks.
Using a similar approach to the phospholambdan paper, [vandeLeur2021](../literature/vandeLeur2021.md), we will evaluate the relationship of TTN loss-of-function (LOF) genes and atrial fibrillation risk in a sample of individuals with WES. 

@Selvaraju2020 describes the Grad-CAM approach, annotated in [Selvaraju2020](../literature/Selvaraju2020.md). 
We can visualize and explain the ECG findings and their weights using [gradient-weighted-class-activation-mapping](../permanent/gradient-weighted-class-activation-mapping.md) methods.

# Results

# Discussion

## Limitations

There are pitfalls in the usage of "big data" approaches, particularly with external validity, as described by @vandeLeur2020