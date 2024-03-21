---
date: 2024-02-06
category: project
stage: building
tags:
  - electrocardiogram
  - genetics
  - research
  - machine_learning
---

In this project, I hope to predict abnormalities in the TTN protein based on functional characterization using surface electrocardiogram.

This project has two major components: (1) Genetic assessment of TTN variants, both pathogenic and VUS subtypes, (2) ECG-based machine learning to predict the likelihood of a TTN variant. They will require effort on multiple fronts, with the goal of having presentation-ready data by early March of 2024 (prior to the AFGen fellowship meeting presentation).

The [outline-ECG-prediction-of-TTN-variants](outline-ECG-prediction-of-TTN-variants.md) will be used for the initial presentation of results (and serves as a tentative/growing outline for the paper).

## ECG approach

1. ECG-beat segmentation: Each ECG beat that is "sinus" has to be split into individual beats. These beats should be centered such that the R peak is the center of the beat, so relationships before and after the R can be interpreted temporally. This function is managed in the in [R-shiva](../docs/Computational/R-shiva.md).
1. ECG data storage: Every beat will have 12-lead data and be fixed at ~ 500 samples, creating a $12 \times 500$ matrix. That needs to be stored as the matrices within a tensor. Overall there are $n = 8000$ ECGs available, with some number of beats, likely 5-15, per ECG. 
	1. In the `{tensorflow}`  package, a matrix could be stored in a *rank 4* tensor, with the following axis order: 1 = batch, 2 = width, 3 = height, 4 = feature. 
	1. The feature classification comes from the genetic approach below, and is either a `0` or `1` if the ECG comes from a TTN variant or not.


## Genetic approach

1. Each VCF file needs to be annotated and evaluated for deleterious TTN variants.  The worfklow is partially documented in [vep-workflow-for-ttn-variants](vep-workflow-for-ttn-variants.md).

## Machine learning approach

1. Model definition: Using the work by @vandeLeur2021, can create similar model training examples. 
1. Guided Gradient Class Activation Mapping: Visualization technique that will be used to identify which parts of the ECG are contributing the most. [gradient-weighted-class-activation-mapping](gradient-weighted-class-activation-mapping.md) which is described by @Selvaraju2020.
