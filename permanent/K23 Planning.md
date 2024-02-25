---
date: 2024-02-10
category: project
stage: building
tags:
  - grants
  - research
---

I will apply for the K23 award sometime in 2025 and/or 2026. 
This should be a continuation of my [T32 and F32 Research Years](T32%20and%20F32%20Research%20Years.md) in terms of topics. 
As its a training grant, the areas of research need to be somewhat innovative but more importantly have areas to be trained in.

I will need to build off of strengths from previous research mentors and the institution and new/active mentors. 
Particularly, I will need to reference the [University of Utah Research](University%20of%20Utah%20Research.md) opportunities.


# Big hairy audacious goal

zhe **BHAG**, as described by [Emelia J. Benjamin, MD, ScM](Emelia%20J.%20Benjamin,%20MD,%20ScM.md) from the AFGen fellowship, is the big picture that I need to be working towards in my research efforts.
My area of interest is in how stress can precipitate arrhythmia.
Stress physiology is complex, and involves the entirety of the neurocardiac axis. 
What I want to focus on is how, mechanistically, stress changes electrophysiological properties locally and how that leads to a propensity for arrhythmia.

My focus is more so on AF as a model disease, as it has multiple "flavors" (vagally-mediated, adrenergically-mediated, etc), multiple phenotypes, and fits well with the *Coumel's triangle* of arrhythmology.

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

1. Phenotype AF based on ECG, echo, and MRI parameters to evaluate progression. Utah Database + AF registry. 
2. EP lab to look at differences in stress / functional repolarization abnormalities during AF mapping. EP lab. Needs patients with minimal AF burden prior to start.
3. Mendelian randomization to evaluate phenotypes of AF risk using AFGen consortium data, UK Biobank, Utah Population Database based on subphenotype. Would need to confirm and explore genetic variants in the Stress Reactivity dataset from Emory.



# Mentorship, Coaching, and Sponsorship

I have started developing a research and mentorship network that will be critical for this project. I will need a key sponsor to "fund" my work, and other field-specific mentors.

- [Amit-j-Shah-MD-MS](Amit-j-Shah-MD-MS.md) 
- [Alvaro-Alonso-MD-PhD](Alvaro-Alonso-MD-PhD.md)
- [Emelia J. Benjamin, MD, ScM](Emelia%20J.%20Benjamin,%20MD,%20ScM.md)
- [Dawood-Darbar-MD-MBChB](Dawood-Darbar-MD-MBChB.md)
- [Ravi Ranjan, MD, PhD](Ravi%20Ranjan,%20MD,%20PhD.md)

- [ ] These sections below need to be cleaned up 
- [ ] They are an amalgam of ideas from previous attempts to present my work to mentors but are not very accurate



# Drafted Ideas

## K23 hypothesis

Sympathetically-mediated paroxysmal AF is a [distinct mechanistic phenotype of AF]{.underline} that has unique [clinical]{.red} and [electrophysiological characteristics]{.red} that associate with more frequent, *staccato* episodes of AF, occurring more commonly in structurally normal atria.

[*This is in comparison to [scar-mediated phenotypes of AF]{.underline}.*]{.grey}

## Aims

1. Identify electrocardiographic phenotypes of paroxysmal AF with structurally normal atria.
2. [Determine the electrophysiological characteristics of sympathetically-mediated paroxysmal AF.]{.red}
3. Evaluate the role of genetic variants in cardiovagal receptors in sympathetically-mediated paroxysmal AF.

## Current status

- Collected 800k ECG of patients with AF, along with clinical histories, burden, medication changes
- Collected ~600 genomes of patients with AF of various comorbidity burdens
- Working on research to help identify phenotypes of AF, and understand trajectory/progression of AF

## Goals for EP fellowship

- Research project that can align with being a clinical EP, e.g. collect data from EPS (leveraging background in signal processing and machine learning)
- Focus on autonomic association with atrial arrhythmias (particularly AF)
- Consider mental stress testing and cardiovagal control during EPS

## Electrophysiology mechanisms {.smaller}

- APD variability in the atria precede onset of AF at rapid pacing rates [@vanStaveren2020]
- AERP measurement durnig extrastimuli protocols (e.g. bottom quintile of fibrillatory intervals from endocardium) [@Capucci1995]
- Two studies that have looked at mental stress and EPS are quite small (`n = 10` & `n = 12`), but neither looked at atrial properties [@Insulander2003; @Finlay2016]

## Proposal ideas

1. Measure of EPS parameters during mental stress: evaluate HRV changes and intracardiac changes simultaneously 
1. Measure neuropeptide Y, epinephrine, and galanin levels before, during, and after
1. Cardiac autonomic modulation with vagal stimulation $\pm$ atropine during EPS
1. 24-hour Holter monitor before and after AF ablation to assess changes in ANS, and potentially more distant recordings to assess "autonomic recovery"

## Significance {.smaller}

-   Knowledge gaps:
    -   biomarkers of response to neuromodulation therapy, including ablation
    -   understanding of regional variation in innervation affects arrhythmogenesis
    -   translation from single-cell studies to human models
-   Research priorities:
    -   role of ANS signaling in emergence and maintenance of cardiac arrhythmias
    -   target modulation of ANS to attenuate electrical remodeling
    -   predict underlying biomarkers
    -   understand time course of ANS remodeling and neuropeptide expression
    -   sex/race differences in cardiac arrhythmogenesis

::: aside
NIH and NHLBI released 2022 Research Report on ANS in CV disease, with a focus on AF and VT/VF.
ANS = autonomic nervous system; CV = cardiovascular; AF = atrial fibrillation; VT/VF = ventricular tachycardia/fibrillation;
:::

------------------------------------------------------------------------

![ANS and atrial arrhythmias](../figures/mehra-2022_ans-atrial-arrhythmias.png){#fig-af}

------------------------------------------------------------------------

![ANS and ventricular arrhythmias](../figures/mehra-2022_ans-vt-vf.png){#fig-va}

## Research skills {.smaller}

| Category                 | Description                                                                              |
|-------------------|-----------------------------------------------------|
| [Clinical]{.red}         | cardiac electrophysiology, echocardiography, electrocardiography                         |
| [Translational]{.orange} | genetic analysis, electrophysiology studies, molecular mechanisms                        |
| [Epidemiology]{.blue}    | causal inference, biostatistics, survival analysis with recurrence, study design         |
| [Computational]{.green}  | programming (R, MATLAB, python, C++, Julia), digital signal processing, machine learning |

: Research skills to be developed {#tbl-skills}


::: columns
::: {.column width="50%"}
**Electrophysiology Study**

-   Baseline and post-procedural atrial conduction properties
-   Coronary sinus + circulating blood samples (including DNA)
-   Surface + intracardiac mapping and electrophysiological signal
-   Vagal nerve stimulation
:::

::: {.column width="50%"}
**Big Data**

-   Cohort generated from population-level data (UIC/CCTS, ARIC, MVP/VAMC)
-   Computational model to classify AF based on clinical + cardiac imaging features
-   Whole exome sequencing of DNA in pAF patients to identify autonomic variants
-   Extraction of intracardiac features from EPS (volume, scar, voltage, etc...)
:::
:::

::: aside
UIC = University of Illinois at Chicago; CCTS = Center for Translational Research; ARIC = Atherosclerotic Risk in Communities;
:::

## Outcomes

-   Mechanisms explored could identify candidate subjects for NPY2R/Gal1R receptor blockade or VNS therapy
-   Efficacy of VNS therapy could be quantified through serum testing
-   Genetic variants that affect autonomic function along the neurocardiac axis may interplay with known inherited arrhythmis, such as the vagal-mediated triggers of SCD in LQTS patients

::: aside
SCD = sudden cardiac death; LQTS = Long QT syndrome
:::

# Background

## Autonomic control of the heart {.smaller}

-   Neurocardiac axis is a hierarchical system of SNS and PNS afferent/efferent circuits that interact at multiple levels [@Armour1997]
    -   Cortex ↔ brainstem
    -   Spinal cord ↔ extracardiac ganglia (e.g. stellate)
    -   Intrinsic cardiac nervous system (ICNS) ↔ heart
-   Autonomic regulation is critical in the development of most CV disease
    -   Disregulated catecholamines in heart failure
    -   Post myocardial infarct VF
    -   Triggered arrhythmias such as VT

::: aside
SNS = sympathetic nervous system; PNS = parasympathetic nervous system;
:::

------------------------------------------------------------------------


![Cardiac sympatho-vagal crosstalk @Herring2012](../figures/herring-2012-cellular-sympathovagal-crosstalk.png){#fig-ans-crosstalk}

------------------------------------------------------------------------

![Increased sympathetic activity and NPY @Hoang2020](../figures/hoang-2020-npy-blockade.png){#fig-npy-blockade}

# Aim #1

## 

{{< include _aim-one.qmd >}}

## Premises {.smaller}

1.  **Paroxysmal** AF requires both a trigger and a substrate to progenerate
2.  Paroxysmal, early AF rallies primarily through triggered activity
3.  Firing mechanisms occurs primarily from pulmonary veins due to:
    -   Enhanced automaticity
    -   Myocardial micro-reentry
    -   Triggered activity
4.  Electrical abnormalities preceed ± cause mechanical changes (fibrosis, myocardial disarray, leading to increased pre-disposed substrate
5.  Long-standing, chronic/persistent AF sustains primarily through substrate

---

```{mermaid}
flowchart LR
	t1[Automaticity]
	t2[Reentry]
	t3[DAD]
	trig[Triggers]
	
	s1[LA size]
	s2[Diastology]
	s3[Fibrosis]
	
	epaf[Early AF]
	ppaf[Progressing AF]
	lpaf[Late AF]
	
	subgraph focus [Phenotyping]
	t1 --> trig
	t2 --> trig
	t3 --> trig
	trig --> epaf
	end
	
	s1 --> ppaf
	s2 --> ppaf
	s3 --> ppaf
	
	epaf --> ppaf --> lpaf
```

---

## Phenotyping {.smaller}

:::: {.columns}
::: {.column width="40%"}
__Identify patients with early (in terms of natural history) paroxysmal AF that have higher trigger burden (compared to fibrosis burden)__
:::
::: {.column width="60%"}
Currently, phenotyping is limited. PhenoKB uses binary diagnosis of AF (2012), while recent studies showed 4 potential clusters may exist. [@Pastori2020; @Vitolo2021]

1. Younger, lower comorbidities
2. High CV risk factors
3. High CV comorbidities
4. High rates of non-CV comorbidities (e.g. cancer)
:::
::::

## EMR-based data

NLP ontologies already exist for major cardiovascular diseases, with basic models using UMLS-derivations such as cTakes, MetaMapper, MetaThesaurus.

```{mermaid}
flowchart TB
	icd[ICD codes]
	nlp[UMLS]
	notes[Unstructured text]
	lstm[Long-short term memory]
	bert[BERT encoders]
	dl[Deep Learning]
	
	subgraph a [Increasing complexity]
	icd --> nlp --> notes --> lstm --> bert --> dl
	end
```

::: aside
UMLS = Unified Medical Language System
:::

## Cardiology data points {.smaller}

:::: {.columns}
::: {.column width="40%"}
__ECG markers__:

- HF HRV
- "Coarse" AF based on F-wave amplitude
- P-wave morphology (dispersion, variability, terminal forces, summation)
- Electrical heterogeneity
:::
::: {.column width="60%"}
__TTE markers__:

- LA size
- Diastology
- LVEF
- LVIDD
:::
::::


## Significance {.smaller}

- Knowledge gaps:
	- biomarkers of response to neuromodulation therapy, including ablation
	- understanding of regional variation in innervation affects arrhythmogenesis
	- translation from single-cell studies to human models
- Research priorities:
	- role of ANS signaling in emergence and maintenance of cardiac arrhythmias
	- target modulation of ANS to attenuate electrical remodeling 
	- predict underlying biomarkers
	- understand time course of ANS remodeling and neuropeptide expression
	- sex/race differences in cardiac arrhythmogenesis

::: aside
NIH and NHLBI released 2022 Research Report on ANS in CV disease, with a focus on AF and VT/VF.
ANS = autonomic nervous system;
CV = cardiovascular;
AF = atrial fibrillation;
VT/VF = ventricular tachycardia/fibrillation;
:::

---

![ANS and atrial arrhythmias](../figures/mehra-2022_ans-atrial-arrhythmias.png){#fig-af}

---

![ANS and ventricular arrhythmias](../figures/mehra-2022_ans-vt-vf.png){#fig-va}

## Research skills {.smaller}

| Category | Description |
| - | --- |
| [Clinical]{.red} | cardiac electrophysiology, echocardiography, electrocardiography |
| [Translational]{.orange} | genetic analysis, electrophysiology studies, molecular mechanisms | 
| [Epidemiology]{.blue} | causal inference, biostatistics, survival analysis with recurrence, study design |
| [Computational]{.green} | programming (R, MATLAB, python, C++, Julia), digital signal processing, machine learning |

: Research skills to be developed {#tbl-skills}

## Committee {.smaller}

| Mentor | Field | Specialty |
| --- | --- | --- | 
| Amit J. Shah MD/MS | CV/EPI | mental stress, autonomic dysfunction, digital biomarkers |
| Dawood Darbar MBCHB/MD | CV/EPI | atrial arrhythmias, genetics |
| Mark McCauley MD/PHD | CV/EP | atrial arrhythmias | 
| Alvaro Alonso MD/PHD | EPI | atrial fibrillation, ARIC investigator | 
| Rachel Lampert MD | CV/EP | mental stress, autonomic dysfunction |

: Potential committee members {#tbl-mentors}

::: aside
Goal for next 1-2 years is to increase collaboration within committee in support of K23
:::

---

```{r}
#| label: fig-dag
#| fig-cap: "Graphical representation of specific aims"
dag <-
	dagify(
		stress ~ eps,
		egm ~ eps,
		labs ~ stress + eps,
		pheno ~ ecg + dna + egm + clin,
		clin ~ epi,
		ecg ~ epi,
		dna ~ epi + labs,
		snp ~ dna,
		labs ~ snp,
		stress ~ snp,
		dna ~ eps,
		ead ~ ipsc,
		ipsc ~ labs + stress + snp,
		exposure = c("eps", "epi", "ipsc"),
		outcome = c("labs", "pheno", "ead"),
		labels = list(
			eps = "Electrophysiology study",
			labs = "Cardiac biomarkers",
			ead = "Early After Depolarizations",
			stress = "Physiologic stress",
			ecg = "Surface electrocardiography",
			egm = "Intracardiac signals",
			epi = "Big data",
			ipsc = "Cardiac Myocytes",
			pheno = "Clinical phenotypes",
			clin = "Clinical features",
			snp = "Mutations/variants",
			dna = "Genetic data"
		)
	) |>
	tidy_dagitty(layout = "tree") |>
	node_status() 

ggplot(dag, aes(x = x, y = y, xend = xend, yend = yend, color = status)) +
	geom_dag_point() +
	geom_dag_edges(
		arrow_directed = grid::arrow(length = grid::unit(10, "pt"), type = "closed"),
		arrow_bidirected = grid::arrow(length = grid::unit(10, "pt"), type = "open", ends = "both"),
		edge_alpha = 0.8
	) +
	geom_dag_label_repel(
		aes(label = label),
		force = 1,
		nudge_y = 0.5,
		alpha = 0.9
	) +
	scale_color_manual(values = c("exposure" = green[2], "outcome" = orange[2]), na.value = grey[5]) +
	geom_segment(aes(x = 0, xend = 0.0, y = -0.5, yend = 3.5, color = grey[1]), linetype = "dashed", linewidth = 1) + 
	geom_segment(aes(x = 0, xend = 3, y = 1.5, yend = 1.5, color = grey[1]), linetype = "dashed", linewidth = 1) + 
	annotate("text", label = "Aim #1", x = -1.5, y = 0.0, size = 7) +
	annotate("text", label = "Aim #2", x = 2.5, y = 2.5, size = 7) +
	annotate("text", label = "Aim #3", x = 2.5, y = 0.0, size = 7) +
	theme_dag(legend.position = "none") 
```

## Methods {.smaller}

:::: {.columns} 
::: {.column width="50%"}
__Electrophysiology Study__

- Baseline and post-procedural atrial conduction properties
- Coronary sinus + circulating blood samples (including DNA)
- Surface + intracardiac mapping and electrophysiological signal
- Vagal nerve stimulation
:::
::: {.column width="50%"}
__Big Data__

- Cohort generated from population-level data (UIC/CCTS, ARIC, MVP/VAMC)
- Computational model to classify AF based on clinical + cardiac imaging features
- Whole exome sequencing of DNA in pAF patients to identify autonomic variants
- Extraction of intracardiac features from EPS (volume, scar, voltage, etc...)
:::
::::

::: aside
UIC = University of Illinois at Chicago;
CCTS = Center for Translational Research;
ARIC = Atherosclerotic Risk in Communities;
:::

## Outcomes

- Mechanisms explored could identify candidate subjects for NPY2R/Gal1R receptor blockade or VNS therapy
- Efficacy of VNS therapy could be quantified through serum testing
- Genetic variants that affect autonomic function along the neurocardiac axis may interplay with known inherited arrhythmis, such as the vagal-mediated triggers of SCD in LQTS patients

::: aside
SCD = sudden cardiac death;
LQTS = Long QT syndrome
:::

# Background

## Autonomic control of the heart {.smaller}

- Neurocardiac axis is a hierarchical system of SNS and PNS afferent/efferent circuits that interact at multiple levels [@Armour1997]
	- Cortex &harr; brainstem
	- Spinal cord &harr; extracardiac ganglia (e.g. stellate)
	- Intrinsic cardiac nervous system (ICNS) &harr; heart
- Autonomic regulation is critical in the development of most CV disease
	- Disregulated catecholamines in heart failure
	- Post myocardial infarct VF
	- Triggered arrhythmias such as VT

::: aside
SNS = sympathetic nervous system;
PNS = parasympathetic nervous system;
:::

---

![Cardiac neurotransmission @Shivkumar2016a](../figures/shivkumar-2022_neurocardiac-axis.png){#fig-neurocardiac-axis}

## Neurovisceral integration

- **Lower levels** of networked structures (ICNS, hypothalamus) integrate afferent information about metabolic demands
- **Higher levels** of networked structures (amydala, cortex) integrate lower networks and generate conscious/uncscious CV state representations
- Allows for environmental/psychological factors to interplay with cardiac physiology, e.g. [mental stress]{.blue} causing [arrhythmia]{.orange}

## Critical role of the vagus {.smaller}

- Embryologically, vagus nerve sprouts from medulla and extends to distant organs (thus long pre-ganglionic axons) e.g. heart, lung, intestines
- Parasympathetic control is evolutionarily more primitive in vertebrates, preceeding sympathetic control
	- Sharks exhihibt phasic HRV without sympathetic innervation [@Taylor2022]
	- Mammalian vagal control is more complex, with multiple nuclei, e.g. polyvagal [@Porges2009]
- Mammalian vagal outflow is particularly coupled with cardiorespiratory control
	- Leads to [respiratory sinus arrhythmia]{.orange}
	- Respiratory changes occur at a high-frequency, can be [measured by HRV]{.green}

::: aside
Stephen Porges proposed the Polyvagal Theory during his tenure at UIC.
HRV = heart rate variability;
:::

## Vagal therapeutic interventions {.smaller}

- Chronic VNS reduces drop in ejection fraction in different animal models of cardiomyopathy, including MI, but studies have mixed results in humans
	- NECTAR-HF ~ VNS or sham, no difference at 6 months in LV size/function, n = 96
	- INOVATE-HF ~ right VNS + GDMT vs. GDMT, no difference in mortality, n = 700
	- ANTHEM-HF ~ non-randomized VNS, improved LV function, pilot study (*required titrated VNS to cause decrease in HR*)
- VNS may be anti-arrhythmic in animal models, with decreased VT/VF, but minimal human studies
	- GANGLIA-AF, paroxysmal AF randomized to PVI or atrial GP ablation, decreased AAD dosages in GP group, n = 102

::: aside
VNS = vagal nerve stimulation;
MI = myocardial infarction;
LV = left ventricle;
GP = ganglionated plexi;
AAD = anti-arrhythmic drugs
:::

## Sympathovagal crosstalk {.smaller}

- Arrhythmia thresholds affected by sympathetic and vagal activity 
- Intracardiac cross-talk between adrenergic (sympathetic) and cholinergic (vagal) neurons in the hierarchy of neurocardiac axis is critical for arrhythmogenesis during mental stress
- Atria are heavily innervated by autonomic ganglionic plexi, leading to the complex activity that regulates cardiac conductive properties[@Hoover2009; @Armour1997] 
- Sympathetic nervous activity is slower onset, but vagolysis is rapid, thus being a more likely causal component of arrhythmogenesis

## Molecular mechanisms {.smaller}

- Sympathetic/adreneric neurons release catecholamines (NE) that directly affect the myocardium
- NPY and galanin is also released, which both inhibit cholinergic activity [@Herring2015; @Herring2012]
- Both inhibit firing and leading to vagolytic effects on the myocardium[@Kalla2020; @Herring2008]
	- Galanin released as a adrenergic co-transmitter, binding to GalR1 receptors
	- NPY binds to cholinergic neurons through the Y2 receptor
	- Both directly/indirectly involve protein kinase C
- NPY receptors exist along the neurocardiac axis, including adrenal medulla (Y3) and cardiac tissue (Y2)[@Coote2013]

::: aside
NE = nor epinephrine;
NPY = neuropeptide Y
:::

---

![Cardiac sympatho-vagal crosstalk @Herring2012](../figures/herring-2012-cellular-sympathovagal-crosstalk.png){#fig-ans-crosstalk}
	
---

![Increased sympathetic activity and NPY @Hoang2020](../figures/hoang-2020-npy-blockade.png){#fig-npy-blockade}


# Aim #1

{{< include _aim-one.qmd >}}

## Premises {.smaller}

1. __Paroxysmal__ AF requires both a trigger and a substrate to progenerate
1. Triggered mechanisms occurs primarily from pulmonary veins and occur due to:
	- Enhanced automaticity
	- Myocardial micro-reentry
	- Triggered activity
1. Electrical abnormalities preceed &pm; cause mechanical changes (fibrosis, myocardial disarray, 

## Modeling progression of AF

```{mermaid}
flowchart LR
	t1[Enhanced automaticity]
	t2[Micro-reentry]
	t3[Delayed after-depolarization]
	trig[Triggered ]
	epaf[Early paroxysmal AF]
	ppaf[Progressing paroxysmal AF]
	lpaf[Late paroxysmal/persistent AF]
	
	epaf --> ppaf --> lpaf
```


