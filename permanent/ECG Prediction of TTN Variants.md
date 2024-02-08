---
date: 2024-02-06
category: project
stage: building
---

In this project, I hope to predict abnormalities in the TTN protein based on functional characterization using surface electrocardiogram.

This project has two major components: (1) Genetic assessment of TTN variants, both pathogenic and VUS subtypes, (2) ECG-based machine learning to predict the likelihood of a TTN variant. They will require effort on multiple fronts, with the goal of having presentation-ready data by early March of 2023 (prior to the AFGen fellowship meeting presentation).

1. ECG-beat segmentation: Each ECG beat that is "sinus" has to be split into individual beats. 
2. ECG data cleaning: These beats should be centered such that the R peak is the center of the beat, so relationships before and after the R can be interpreted temporally. This function is being developed in [[../docs/Computational/{shiva}]].
3. Guided Gradient Class Activation Mapping: Visualization technique that will be used to identify which parts of the ECG are contributing the most. [[../permanent/Gradient-Weighted Class Activation Mapping (Grad-CAM)|Gradient-Weighted Class Activation Mapping (Grad-CAM)]] which is described by @Selvaraju2020a.

#electrocardiogram 
#genetics 
#research 