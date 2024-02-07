---
date: 2024-01-17
category: project
stage: building
---

Using deep learning, I hope to identify features from a single ECG beat over the standard 12-leads that contribute to a certain diagnosis. This is similar to the work by @vandeLeur2021. 

A key part of this is the use of signal processing techniques to prepare the data. There are certain properties that should be evaluated before feeding them to a model.

1. The center of the data matrix of interest should be the **R wave peak**. This is the most reliable position and easiest to detect algorithmically. 
2. The data range should be the same for all beats being fed. The two major options are: pad the sides of the QRS to fit a set time period (e.g. 500 ms), or stretch the ECG *horizontally* to fit within the set time period.
3. Sampling frequency. If different samples are collected at different frequencies, this may require up (or down) sampling to match frequencies. 

Using `R` as the primary scripting language for my projects, which interfaces well with a variety of other statistical and programming languages, allows me to leverage `{tensorflow}` and `{keras}` packages. These, by passing data through `{reticulate}`, allow to utilize the deep learning models from [TensorFlow](https://tensorflow.rstudio.com/). 

# Approaches

[[../literature/vandeLeur2021|vandeLeur2021]] describes an approach that uses signal averaged *median* beats for analysis. I'm wary of this as certain specific details are lost and information from other beats are thrown away. The use their ECG data to create a classifier model for evaluating phospholamban mutations.

#electrocardiogram 
#signal_processing
#machine_learning
#programming
#R 


