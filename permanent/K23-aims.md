---
date: 2024-04-15
category: concept
stage: building
tags:
  - research
  - grants
  - afib
---

I need to break apart my __BHAG__ into a overarching hypothesis that leads me towards it, as it needs to be a small enough project that can be tested and finished within 5 years (at 50% protected time).
This is described in [K23](K23.md).
The hypothesis then needs to be approached using 3-4 specific aims, building on my skills and prior research.

- Signal processing: ECG and EGM data
- Biostatistics: statistical analyses, recurrent events
- Harmonic regression: cosinor analysis
- Computational genetics: Ensembl-VEP software, rare variant analysis
- Coding/programming: R, MATLAB, Python
- Electrophysiology procedures: animal and human studies, access to specific EP data

My overall interest is in using the K23 to explore how research can be performed in the EP lab, while also advancing my skills in epidemiology, signal processing, and genetics. 
The most important element is that the proposal must be novel, innovative, and *worth* investing in from a research perspective.
These aims need to be related but independent, and will use atrial fibrillation as the model disease. 
They need to reflect expertise from the institution/primary mentors & sponsors.

The areas of expertise of the mentorship group and institutions revolve around the following:

- Mental stress and autonomic dysfunction with [Amit-J-Shah-MD-MS](Amit-J-Shah-MD-MS.md) at Emory
- Genetic data and whole exome sequencing with [Yan-Sun-PhD](Yan-Sun-PhD.md) at Emory
- Atrial fibrillation modeling using MRI and EPS with [Ravi-Ranjan-MD-PhD](Ravi-Ranjan-MD-PhD.md) and [Robert-MacLeod-PhD](Robert-MacLeod-PhD.md) at Utah
- AF genetics and translational work with [Dawood-Darbar-MD-MBChB](Dawood-Darbar-MD-MBChB.md) at UIC

# Versions of Aims

The aims are oriented around different topics, methodologies, and datasets that may be available.
There looks to be three major themes here that *pull together* my aims - there is a __mapping__ oriented aim in the EP lab, a __ECG__ based aim looking at phenotypic differences based on genetics (and null variants), and an exploratory aim on __novel variants__. 
Below I go over potential working titles and conceptual aim ideas, which are then expanded subsequently. 
Aims are presented in reverse chronological order. 


## v0.2.3

Draft:

The overarching goal is to develop a precision-medicine framework for the management of AF by integrating autonomic triggers, imaging measures of atrial substrate, and genetic and epigenetic correlates that predispose to adrenergically-driven episodes of AF. 
1. **Profile the autonomic phenotypes of paroxysmal AF who may benefit from combined cardioneuroablation and PVI ablation approaches.** *Hypothesis: Heightened sympathetic activity and impaired vagal activity will associate with an adrergic phenotype of AF, which will have increased rates of AF recurrence.* Sympathetic outflow, measured through stellate ganglia activity surrogates (skin sympathetic nerve activity, cardiac biomarkers of NPY and Gal1) and parasympathetic outflow (baroreceptor reflex, heart rate variability) are somewhat antagonistic, with exaggerated antagonism being predictive of those at risk of future AF despite PVI. The identification of an adrenergic phenotype of AF can help identify autonomic-targeted therapies in AF.
1. **Characterize the dynamic atrial substrate and fibrillatory area using MRI-based computational modeling to identify potential ablation targets.** *Hypothesis: Sympathovagal imbalance amplifies conduction heterogeneity in fibrotic tissue, augmenting the dynamic fibrillatory and re-entry area, increasing propensity for AF initiation under stress.*  Cardiac MRI before and after PVI can assess scar and fibrosis burden of the atria in static manner. By including the dynamic information of autonomic tone, the true potential fibrillatory thresholds can be determined, which can be obtained and verified during EP study. Moreso,  ablation approaches for specific atrial substrates can be tailored to increase efficacy.
1. **Explore the genetic and epigenetic determinants of autonomic dysfunction that predispose to AF.** *Hypothesis: Genetic variants associated with neurocardiac regulation, and epigenetic changes on similar trait loci, increases the risk of future AF occurrence.* By creating a polygenic risk for abnormal neurocardiac responses to mental stress (the Emory Myocardial Ischemia and Mental Stress study), key neurocardiac genes can be identified. By evaluating those genes, and their epigenetic modifications, in large biobank databases (Million Veterans Project, UK Biobank), we can quantifiy part of the polygenic and allostatic contribution to AF.

Atrial fibrillation (AF) is the most common sustained arrhythmia and a major contributor to morbidity and mortality [Reference]. While pulmonary vein isolation (PVI) has improved AF outcomes, recurrence rates remain high, suggesting that additional pathophysiologic mechanisms—including autonomic dysregulation—play a central role [Reference]. Autonomic triggers, mediated by the sympathetic and parasympathetic nervous systems (e.g., ganglionated plexi), remain understudied in a systematic way that can inform targeted interventions [Reference]. My overarching goal is to develop a precision-medicine framework for AF by characterizing autonomic contributions, integrating imaging markers of atrial substrate, and identifying genetic/epigenetic correlates that predispose to autonomic-driven AF.


**SPECIFIC AIMS**

Atrial fibrillation (AF) is the most common sustained arrhythmia and a major contributor to morbidity and mortality [Reference]. While pulmonary vein isolation (PVI) has improved AF outcomes, recurrence rates remain high, suggesting that additional pathophysiologic mechanisms—including autonomic dysregulation—play a central role [Reference]. Autonomic triggers, mediated by the sympathetic and parasympathetic nervous systems (e.g., ganglionated plexi), remain understudied in a systematic way that can inform targeted interventions [Reference]. My overarching goal is to develop a precision-medicine framework for AF by characterizing autonomic contributions, integrating imaging markers of atrial substrate, and identifying genetic/epigenetic correlates that predispose to autonomic-driven AF.

**Aim 1: Determine the autonomic phenotype of AF and identify patients who may benefit from combined ganglionated plexus (GP) ablation and PVI.**  
**Rationale:** While GP ablation in addition to PVI may benefit certain AF patients, there is no established method to identify who will respond [Reference].  
**Hypothesis:** Patients with heightened sympathetic tone, as evidenced by elevated neuropeptide Y (NPY) levels and impaired baroreflex sensitivity, exhibit a higher burden of sympatho-triggered AF and will demonstrate improved outcomes with adjunctive GP ablation.  
**Approach:**

1. Prospectively enroll patients undergoing PVI.
2. Quantify autonomic markers (e.g., NPY, baroreflex sensitivity) at baseline and during controlled autonomic perturbation (e.g., isoproterenol infusion).
3. Randomize high-sympathetic phenotype patients to PVI vs. PVI + GP ablation.
4. Compare AF recurrence, arrhythmogenic triggers, and clinical outcomes over 12 months.  
    **Expected Outcomes:** Identification of an “adrenergic phenotype” that predicts which patients will derive maximal benefit from GP ablation.  
    **Impact:** This will lay the groundwork for precision autonomic-targeted therapies in AF.

**Aim 2: Characterize dynamic interactions between autonomic triggers and the structural substrate to refine ablation strategies.**  
**Rationale:** Atrial fibrosis, revealed on late gadolinium-enhanced MRI, partially explains AF propensity, but scar burden alone incompletely predicts arrhythmic risk [Reference]. Autonomic inputs may modify conduction in fibrotic regions, further promoting arrhythmogenesis [Reference].  
**Hypothesis:** Sympathetic–parasympathetic imbalance amplifies conduction heterogeneity in scarred tissue, increasing propensity for AF re-initiation under autonomic stress.  
**Approach:**

1. Perform high-resolution atrial MRI to quantify scar burden pre-ablation.
2. Correlate scar distribution with in-lab EP assessments under sympathetic (isoproterenol) and parasympathetic (e.g., glycopyrrolate) challenges.
3. Assess changes in action potential duration (APD) and conduction velocity in scarred vs. non-scarred regions in response to autonomic modulation.
4. Evaluate whether dynamic “fibrillatory area” during these maneuvers predicts AF recurrence.  
    **Expected Outcomes:** A refined understanding of how autonomic–fibrotic interactions shape AF vulnerability, enabling personalized lesion sets that better target arrhythmic triggers.  
    **Impact:** Results could support integrating autonomic provocative testing into routine AF mapping to guide ablation strategy.


**Aim 3: Investigate genetic and epigenetic determinants of autonomic dysfunction that predispose to AF.**  
**Rationale:** Emerging data suggest that AF risk has a strong hereditary component, with both polygenic risk and epigenetic modifications implicated [Reference]. However, the contribution of specific autonomic-related genetic pathways remains underexplored.  
**Hypothesis:** Genetic variants and epigenetic markers (e.g., differential methylation) in autonomic regulatory genes confer heightened sympathetic responses and increase AF susceptibility.  
**Approach:**

1. Develop a polygenic risk score based on existing mental stress and autonomic dysfunction datasets [Reference].
2. Measure candidate gene methylation patterns from peripheral blood in patients stratified by autonomic phenotype (Aim 1).
3. Correlate these genetic/epigenetic profiles with AF incidence and recurrence following ablation.  
    **Expected Outcomes:** Identification of novel biomarkers and mechanistic links between autonomic dysregulation and AF at the molecular level.  
    **Impact:** Findings will pave the way for future genetic risk stratification, facilitating personalized approaches to AF screening and therapy.


**Overall Significance and Career Development**  
Through this K23 award, I will develop expertise in (1) advanced autonomic physiology testing in the electrophysiology lab, (2) cardiac MRI for substrate characterization, and (3) translational genomic/epigenetic methodologies. These skills will enable me to integrate mechanistic insights into targeted AF interventions, ultimately improving patient outcomes and reducing the burden of this prevalent arrhythmia.

Outline:

**Aim 1** = Phenotype ANS in pxAF
- phenotype AF by ANS factors to assess future AF 
- SKNA measurement with high frequency ECG patches before ablation along with baroreflex testing prior to ablation (minimizing sedation by bispectral index)
- identify those who would benefit from GP ablation (e.g. similar to baroreceptor delta and future AF risk)
- Measure NPY levels

**Aim 2** = Personalize ablation lines in pxAF based on ANS substrate
- measure ANS parameters of dynamic atrial substrate and compare with MRI substrate and assess "delta" on future AF risk
- get fibrillatory dynamic area predictions/models to understand future AF
- predict change in fibrillatory area with GP ablation

**Aim 3** = Genetic and Epigenetic ANS markers in AF
- Emory dataset on MS HRV and WGS
- VA MVP dataset with methylation patterns
- Role of neurocardiac genes in future AF risk (polygenic risk score for autonomic dysfunction)

Notes:

1. AIm 1 focuses on which patient would benefit from considering their autonomic phenotype
	- NPY and Gal may be associated with *adrenergic* AF in otherwise low scar burden atria
	- can measure NPY levels, S100B (neural damage), along with baroreflex testing
1. Aim 2 looks at how to decrease fibrillatory area and considers dynamic and autonomically influenced substrate
	- MRI perspective helps as the gold standard for scar
2. Aim 3 looks at  how genetic and epigenetic factors influence the autonomic phenotype in AF
	- NPY and Gal are released from sympathetic terminals and inhibit cholinergic activity
	- Gene variants in NPY
	- Look at genetic variants in ANS related genes to understand their association with atrial arrhythmias

## v0.2.2

Overarching hypothesis: The autonomic phenotype of AF is an alternative and novel mechanism that should be understood and may lead to potential treatments.

**Aim 1: Quantify the effect of the ANS on the atrial substrate to assess the variable threshold for arrhythmias.**
During EPS, the ANS can be modulated through pharmacological intervention and pacing maneuvers (such as vagal stimulation). 
ANS modulation will have varying effects on the atrial substrate based on the burden of underlying scar.
Hypothesis: The changes in electrophysiological parameters in response to ANS modulation will reflect the underlying propensity for episodes of AF.

**Aim 2: Compare the efficacy of computational scar-based models of atrial arrhythmias with models including ANS parameters.**
Current computational models for arrhythmia prediction are predicated on the differential conductive properties of scar.
Hypothesis: The effect of ANS innervation on cardiac conduction will improve prediction of clinical-relevant arrhythmias.
As a secondary hypothesis, the ANS parameters obtained from **Aim 1** will validate the computational models.

**Aim 3: Explore the contribution of ANS genetic variants in the polygenic risk of atrial arrhythmias.**
Hypothesis: Genetic variants associated with the perturbations of the ANS, particularly stress-related disorders, may overlap with and contribute to both risk and resilience to future development of AF. 
Using a two-sample Mendelian randomization study design, we will identify SNPs that contribute to stress-related disorders, including potentially novel loci, and assess their impact on the polygenic risk of AF in a validation cohort (UK Biobank).

I received early feedback from [Ravi-Ranjan-MD-PhD](Ravi-Ranjan-MD-PhD.md) about these aims, and his major thoughts were to consider the specific hypothesis and how the implementation would happen.
- For aim 1, there isn't a clear "big picture". Perhaps using prediction to help identify which patients would be strong respondeds to GP ablation. But this would require an implementation tool or measurement that was safe and was already part of an EP study to some degree.
- For aim 2, the MRI findings could be helpful to understand which patients would benefit from more or less aggressive treatment at time of first ablation. This could be a measurement of pre- vs. post- fibrillatory area that accounts for "modulation" from ANS to increase or decrease size.
- Aim 3 is the weakest, and will require a conversation with [Martin-Tristani-Firouzi-MD](Martin-Tristani-Firouzi-MD.md). 

## v0.2.1

**Aim 1: Determine the differences in APD heterogeneity of scar tissue in the context of modulated autonomic activity.** 
Our working hypothesis is that the interaction between APD heterogeneity and autonomic modulation will predict differential risk for future AF, particularly in cases of abnormal baseline autonomic activity such as PTSD.

**Aim 2: Determine the effect of autonomic changes in computational models of arrhythmia to predict differential risk for atrial arrhythmias.** 
Our working hypothesis is that by modifying dromotropic and lusitropic properties of computational models of atria, clinically-relevant arrhythmias can be elicited over that of fibrosis-based models alone.

**Aim 3: Evaluate the association of polygenic risk scores for chronic stress disorders with risk of atrial arrhythmias.** 
We hypothesize that SNPs associated with stress disorders have differential susceptibility (or resilience) to future arrhythmias. 
We will validate our findings in the UK Biobank using a two-sample Mendelian randomization study design.

We tried to pull together the aims even more in a meeting with [Amit-J-Shah-MD-MS](Amit-J-Shah-MD-MS.md).  His revisions:

- Change verbiage of aim 1 to be simpler and talk about sympathovagal balance instead of autonomic modulation
- Consider each aim as an attempt at phenotyping, with the focus being on comparing the different phenotypes. E.g.
	- Aim 1 i s all about the electrical and autonomic phenotype, and its definition
	- Aim 2 is more about comparing it with scar-based phenotypes
	- Aimd 3 is about comparing the role of autonomic phenotypes against that of genetic phenotypes (e.g. 20% of the population)

## v0.2.0

At this point, have decided that the aims may be disparate enough that two different applications are likely more conducive - one through a VA-CDA and another through the NIH-K23 mechanism.
[Amit-J-Shah-MD-MS](Amit-J-Shah-MD-MS.md) however suggested a way to unify the aims more clearly, under the auspice of stress and arrhythmias.

1. EPS to evaluate measures of how a "mental stress cocktail" can help evaluate the properties of atrial tissue and islands of cholinergic neurons. 
	- Build a cohort to identify features of "atrial resilience" to arrhythmia (particularly AF). 
	- Obtain bloodwork to help measure autonomic responses and whole genome sequencing data to create polygenic risk
1. Apply autonomic variables to algorithm in computational geometry maps that predict arrhythmia. Use weights of variables based off of (1) to help with prediction. Compare those to future EP studies with multiple arrhythmias that are found.
1. Evaluate association of polygenic risk score for chronic stress disorders (e.g. PTSD, depression, anxiety) with cohort of 50-100 individuals undergoing EP study. 
	- Identify the "difficulty" in inducing arrhythmia and rank PGS against that to identify "susceptible" and "resiliency" SNPs. 
	- Obtain additional SNPs using abnormal HRV response from mental stress cohort from Emory
	- Perform Mendelian Randomization using those SNPs in UK Biobank

## v0.1.5

__Contextual Evolution of Substrate-Based Atrial Fibrillation Phenotypes__  
*By understanding how the multifactorial substrate for AF is modulated by context, we can better understand the risk for AF arrhythmogenesis and potential tailor treatment strategies.*
1. Generate ECG-based phenotypes of AF based on (A) patterns of scar/fibrosis generated by EPS and CMR/LGE and (B) rare/common variants that are associated with AF. 
1. Identify differences in APD heterogeneity by scar-burden in context of modulated autonomic outflow.
1. Identify novel rare variants for AF in diseases/states that are associated with altered autonomic tone, including PTSD, abnormal HRV, etc. Utilize mendelian randomizatino approach.

Feedback from Ravi Ranjan...
- The ECG phenotypes from aim 1 need to be written in such a way that PVI (the mainstay) is not thrown out or goes against dogma (e.g. paroxysmal without myopathy needs PVI, regardless of ECG characteristics)
- The second aim requires understanding how to measure APD effectively
- The third aim is not cohesive with the others

## v0.1.4

__Dynamicity in Substrate-Based Atrial Fibrillation Phenotypes__   
*Identify the interaction between substrate and context lead to more accurate prediction of arrhythmia type and progression. If AF can be more accurately phenotyped, then future risk can be better mitigated.*
1. Phenotype AF based on scar properties and scar contribution. Evaluate genetic contribution.
1. Assess intracardiac and MRI-based AF dynamics in context with EP studies. Evaluate in stress-related conditions (e.g. PTSD).
1. Identify novel variants for AF risk in MR-based study

## v0.1.3

__Genetic Interaction with Substrate-Based Atrial Fibrillation Phenotypes__  
*The underlying drivers of atrial fibrillation likely evolve along the pathways of Coumel's triangle (triggers -> substrate). This work tells us how AF evolves, and how different structural and ion-channel changes contribute, to be able to identify and understand disease progression.*
1. Classify AF phenotypes and their trajectories (A) based on markers of scar/fibrosis found on MRI/EPS, and (B) based on genetic variants that are causal for AF, based on structural/ion-channel mutations.
1. Evaluate the effect of AF thresholds based on scar burden in EP studies prior to PVI, utilizing differential autonomic contexts, including vagal stimulation, vagolysis, and sympathetic stimulation.
1. __Exploratory:__ Evaluate the role of common and rare variants in stress-related disorders (abnormal response to acute and chronic stress) with future arrhythmia risk using a two-sample Mendelian randomization approach.

Feedback...
- This doesn't seem like it comes together very well as an overall project however. It needs more sup
- Needs to be more inline with research done at Utah (e.g. EP lab/mapping aim, scar-mediation) and previous resources (AF genetics and stress/autonomic function)

## v0.1.2

Title: Genetic Interaction with Substrate-Based Atrial Fibrillation Phenotypes  
Bottom Line: If we know how AF phenotypes evolve, we can understand and target/tailor therapies based on underlying trajectories.
1. Substrate phenotyping (with outcomes)
1. Scar interaction with contextual triggers
1. Triggering states with genetic risk of AT/AF

## v0.1.1

Title: Substrate-based Trajectory of Atrial Fibrillation Phenotypes
1. Quantify dynamic atrial conduction properties in scar-based AF.
1. Compare the ECG-based substrates and their evolution in monogenic mutants for AF.
1. Identify novel, stress-related variants and their impact on AF risk.


## v0.1.0

Title: Substrate-Based Phenotypes of Paroxysmal Atrial Fibrillation
1. __Substrated-based phenotypes of AF: (A) CMR burden of LGE, EAM scar, and ECG phenotyping of AF. (B) EPS-based phenotyping of scar, and scar-responsiveness to triggering events in APD heterogeneity. E.g. what does scar look like, and how does scar respond to initiate arrhythmia in the atria?__ Regions of scar seen on MRI/EAM are areas that may lead to the initiation and maintaenance of AF. Can evaluate these areas to look for repolarization abnormalities and characteristics associated with AF onset and maintenance. Can try to evaluate APD heterogeneity in AF at boundaries of scar in different conditions.  Apply these findings to MRI-based maps to consider AF prediction (modeling of AF). Future studies can look at how MRI can be used to predict AF episodes and future burden. Will model the effect of action potential duration heterogeneity at scar borders with AF episode maintenance. Prospective approach to mapping in EP lab. Study monophasic action potentials in paroxysmal AF cases undergoing ablation. Evaluate under influence of isoproterenol $\pm$ atropine $\pm$ vagal stimulation. Why? Assess repolarization abnormalities and affect of stress/triggers on AF threshold. 
1. __Sarcomeric and Ion-Channel Based ECG phenotypes of AF: *Wild-type* and *mutant* ECG patterns of paroxysmal AF. Relationship of monogenic variants in AF with changes in substrate pathology and ion channel remodeling in categorization AF subtypes.__ Can evaluate the ECG-based association with specific "substrate" genes and "ion channel" genes, and "wild-type" AF. See if ECG patterns can categorize patients utilizing UIC dataset, and UK Biobank.  This extends the [ECG-prediction-of-TTN-variants](ECG-prediction-of-TTN-variants.md) project. May also validate using *All of Us* dataset.
1. __Identify novel/rare variants associated with AF (Exploratory Aim): Mendelian randomization of triggered arrhythmias approach focusing on high-risk/high-stress conditions (PTSD, anxiety, reduced stress-induced HRV reactivity).__ Look at Emory HRV stress reactivity data, and evaluate association with common/rare variants in GWAS data. Then, test association of these rare variants with future arrhythmia risk (both in local Emory data) and in UK Biobank. 

## v0.0.3 

*Genetic and Epigenetic Interactions with Substrate-Based Phenotypes of Atrial Fibrillation*  
*Substrate-Based Evolution of Atrial Fibrillation Phenotypes*  
1. Phenotype substrates of AF based on LGE/EPS scar models from Utah, with ECG-based reference/training. Explore EPS relationship with scar-burden modulation by context (pacing rate, vagal maneuvers, vagolysis).
1. Evolution of ECG-based phenotypes in *mutants* and *wild-types* of AF using WES/WGS datasets. Assess relationship of ECG-findings with amount of expected change based on genetic variants.
1. Evaluation of rare/novel variants of AF using mendelian randomization of stress-related disorders associated with AF. 

## v0.0.2

*Autonomic-Mediation of Atrial Fibrillation Pathways*  
*Drivers of Triggered Episodes of Paroxysmal Atrial Fibrillation*  
*Contextualized Substrate-Based Phenotypes in Atrial Fibrillation*
1. Substrate-mapping using CMR and phenotyping areas of LGE pattern.
1. EP lab based evaluation of scar-interaction with different vagal maneuvers for propagation of AF
1. Creation of novel prediction maps for AF and arrhythmia pathways

## v0.0.1

*Substrate and Ion Channel-Mediated Phenotypes of Paroxysmal Atrial Fibrillation*  
*Tissue and Ion Channel-Mediated Phenotypes of Paroxysmal Atrial Fibrillation*
1. (A) substrate phenotyping based on LGE patterns on CMR; (B) EP lab evaluation of properties of substrate in "trigger" conditions
1. Substrate by genotypes on ECG in UIC and Utah datasets.
1. Novel variants that are stress-related with Emory data.

