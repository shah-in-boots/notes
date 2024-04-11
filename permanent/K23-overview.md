---
date: 2024-02-10
category: structure
stage: factoring
tags:
  - grants
  - research
---

I will apply for the K23 award sometime in 2025 and/or 2026. 
This should be a continuation of my [T32-and-F32-research-years](T32-and-F32-research-years.md) in terms of topics. 
As its a training grant, the areas of research need to be somewhat innovative but more importantly have areas to be trained in.

I will need to build off of strengths from previous research mentors and the institution and new/active mentors. 
Particularly, I will need to capitalize on the [University-of-Utah-research](University-of-Utah-research.md) research opportunities.

Notes: 
- Relevant literature for review in [K23-background](K23-background.md) 
- Potential dataset information and descriptions in[K23-data](K23-data.md)

# Big hairy audacious goal

The __BHAG__, as described by [Emelia-J-Benjamin-MD-ScM](Emelia-J-Benjamin-MD-ScM.md) from the AFGen fellowship, is the big picture that I need to be working towards in my research efforts.
My area of interest is in how stress can precipitate arrhythmia.
Stress physiology is complex, and involves the entirety of the neurocardiac axis. 
What I want to focus on is how, mechanistically, stress changes electrophysiological properties locally and how that leads to a propensity for arrhythmia.

My focus is more so on AF as a model disease, as it has multiple "flavors" (vagally-mediated, adrenergically-mediated, etc), multiple phenotypes, and fits well with the *Coumel's triangle* of arrhythmology.
I will have to be more specific at the level of a K23 award, but it should be focused on the above __BHAG__.

# Mentorship, Coaching, and Sponsorship

I have started developing a research and mentorship network that will be critical for this project. I will need a key sponsor to "fund" my work, and other field-specific mentors.

- [Amit-J-Shah-MD-MS](Amit-J-Shah-MD-MS.md) 
- [Alvaro-Alonso-MD-PhD](Alvaro-Alonso-MD-PhD.md)
- [Emelia-J-Benjamin-MD-ScM](Emelia-J-Benjamin-MD-ScM.md)
- [Dawood-Darbar-MD-MBChB](Dawood-Darbar-MD-MBChB.md)
- [Ravi-Ranjan-MD-PhD](Ravi-Ranjan-MD-PhD.md)

# Specific aims

I need to break apart my __BHAG__ into a overarching hypothesis that leads me towards it, as it needs to be a small enough project that can be tested and finished within 5 years (at 50% protected time).
The hypothesis then needs to be approached using 3-4 specific aims, building on my skills and prior research.

- Signal processing: ECG and EGM data
- Biostatistics: statistical analyses, recurrent events
- Harmonic regression: cosinor analysis
- Computational genetics: Ensembl-VEP software, rare variant analysis
- Coding/programming: R, MATLAB, Python
- Electrophysiology procedures: animal and human studies, access to specific EP data

My overall interest is in using the K23 to explore how research can be performed in the EP lab, while also advancing my skills in epidemiology, signal processing, and genetics. 
These aims need to be related but independent, and will use atrial fibrillation as the model disease. 

## Working Titles

The aims are oriented around different topics, methodologies, and datasets that may be available. 
There looks to be three major themes here that *pull together* my aims - there is a __mapping__ oriented aim in the EP lab, a __ECG__ based aim looking at phenotypic differences based on genetics (and null variants), and an exploratory aim on __novel variants__. 
Below I go over potential working titles and conceptual aim ideas, which are then expanded in the subsequent sections.

*Substrate and Ion Channel-Mediated Phenotypes of Paroxysmal Atrial Fibrillation*  
*Tissue and Ion Channel-Mediated Phenotypes of Paroxysmal Atrial Fibrillation*
1. (A) substrate phenotyping based on LGE patterns on CMR; (B) EP lab evaluation of properties of substrate in "trigger" conditions
1. Substrate by genotypes on ECG in UIC and Utah datasets.
1. Novel variants that are stress-related with Emory data.

*Autonomic-Mediation of Atrial Fibrillation Pathways*  
*Drivers of Triggered Episodes of Paroxysmal Atrial Fibrillation*  

*Contextualized Substrate-Based Phenotypes in Atrial Fibrillation*
1. Substrate-mapping using CMR and phenotyping areas of LGE pattern.
1. EP lab based evaluation of scar-interaction with different vagal maneuvers for propagation of AF
1. Creation of novel prediction maps for AF and arrhythmia pathways

*Genetic and Epigenetic Interactions with Substrate-Based Phenotypes of Atrial Fibrillation*  
*Substrate-Based Evolution of Atrial Fibrillation Phenotypes*  
1. Phenotype substrates of AF based on LGE/EPS scar models from Utah, with ECG-based reference/training. Explore EPS relationship with scar-burden modulation by context (pacing rate, vagal maneuvers, vagolysis).
1. Evolution of ECG-based phenotypes in *mutants* and *wild-types* of AF using WES/WGS datasets. Assess relationship of ECG-findings with amount of expected change based on genetic variants.
1. Evaluation of rare/novel variants of AF using mendelian randomization of stress-related disorders associated with AF. 

## Aim drafts

### v0.1.0

Title: Substrate-Based Phenotypes of Paroxysmal Atrial Fibrillation

1. __Substrated-based phenotypes of AF: (A) CMR burden of LGE, EAM scar, and ECG phenotyping of AF. (B) EPS-based phenotyping of scar, and scar-responsiveness to triggering events in APD heterogeneity. E.g. what does scar look like, and how does scar respond to initiate arrhythmia in the atria?__ Regions of scar seen on MRI/EAM are areas that may lead to the initiation and maintaenance of AF. Can evaluate these areas to look for repolarization abnormalities and characteristics associated with AF onset and maintenance. Can try to evaluate APD heterogeneity in AF at boundaries of scar in different conditions.  Apply these findings to MRI-based maps to consider AF prediction (modeling of AF). Future studies can look at how MRI can be used to predict AF episodes and future burden. Will model the effect of action potential duration heterogeneity at scar borders with AF episode maintenance. Prospective approach to mapping in EP lab. Study monophasic action potentials in paroxysmal AF cases undergoing ablation. Evaluate under influence of isoproterenol $\pm$ atropine $\pm$ vagal stimulation. Why? Assess repolarization abnormalities and affect of stress/triggers on AF threshold. 
1. __Sarcomeric and Ion-Channel Based ECG phenotypes of AF: *Wild-type* and *mutant* ECG patterns of paroxysmal AF. Relationship of monogenic variants in AF with changes in substrate pathology and ion channel remodeling in categorization AF subtypes.__ Can evaluate the ECG-based association with specific "substrate" genes and "ion channel" genes, and "wild-type" AF. See if ECG patterns can categorize patients utilizing UIC dataset, and UK Biobank.  This extends the [ECG-prediction-of-TTN-variants](ECG-prediction-of-TTN-variants.md) project. May also validate using *All of Us* dataset.
1. __Identify novel/rare variants associated with AF (Exploratory Aim): Mendelian randomization of triggered arrhythmias approach focusing on high-risk/high-stress conditions (PTSD, anxiety, reduced stress-induced HRV reactivity).__ Look at Emory HRV stress reactivity data, and evaluate association with common/rare variants in GWAS data. Then, test association of these rare variants with future arrhythmia risk (both in local Emory data) and in UK Biobank. 

### v0.2.0

Title: 

