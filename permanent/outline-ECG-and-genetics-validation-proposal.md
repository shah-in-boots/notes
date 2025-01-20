---
date: 2024-05-02
category: reference
stage: questioning
tags:
  - research
  - afib
  - arrhythmia
  - electrocardiography
  - genetics
---


# Current Literature

- @Verweij2020 looked at ECG and correlated it with GWAS for cardiac genetic variants
	- Used 80K ECG from UK Biobank and created single-beat based ECGs (stretched out to 500 samples per ECG)
	- GWAS against 10 million genetic variants
	- Found 300 genetic loci associated with the ECG
	- Also tested specific ECG traits (QT, PR, RR, QRS voltage, AF patterns, etc)

- @Holmqvist2015 showed that heart rate independently is associated with AF progression independent of underlying rhythm, suggesting that AV node health contributes to the AF trajectory

- @Weng2020 showed that there are genetic contributions to P wave duration with specific genetic variants, as its already known that PWD is associated with AF
	- Identified 21 common loci and 14 new loci associated with PWD, including sarcomere genes (*TTN* and *MYH6*)
	- Also found some variants that associated wiht longer PWD but lower AF risk

- @Libiseller-Egger2022 reviewed how ECG-based age was genetically associated with CVD phenotypes
		- Used UK Biobank to assess $\Delta age$ to identify novel loci - they found 8
		- This included genes like SCN5A and TTN, suggesting ECG-age is more likely a cardiovascular phenomenon

- @Husser2009 was a publication with [Dawood-Darbar-MD-MBChB](../permanent/Dawood-Darbar-MD-MBChB.md) and Roden which showed that in a small sample, certain genes in ion-channels associated with fibrillatory rates

- @Wang2023 looked if ECG could predict AF as well as genetic susceptibility
	- Used an ECG-AI model to predict incident AF from 40k UK Biobankers **without** known AF
	- Then did GWAS of predicted AF risk and compared it with AF-GWAS risk
	- Found ECG-AI correlated better with AF then clinical GWAS

- @Choi2020 looked at monogenic and polygenic contributions to AF risk, which found that polygenic factors seemed to increase the susceptibility to AF more than monogenic contributors alone

- @Choi2021 also published on ECG intervals to identify monogenic arrhythmia susceptibility genes
	- Found that normal ECG intervals identified potassium channel and sodium genes, all associated with AF

- @Tereshchenko2018 looked at GEH patterns in the ARIC and CHS study, and found that there were associations with GEH (GEH x GWAS)
	- ARIC + CHS has roughly 13k patients with ECG

# Validation Cohorts

UK Biobank:

- `72,485` ECG are available, covering `68,081` participants
- `469,779` whole exome sequence data are available in VCF format

ARIC:

- `11,478` participants with genotype and phenotype datasets (including ECG)

Cardiac Heart Study:

- `5,888` individuals with WES/WGS and ECG data, with 31% CVD prevalence, 16% AA, and 58% female


# Aims

Key questions:

- Can an ECG that was trained on AF polygenic risk scores predict future risk of AF? 
- Can ECG-AI be used to differentiate between types of pro-arrhythmic gene effects? Essentially can it explain the genotype-phenotype relationship? 

1. Define polygenic risks using known/studied PGS scores for AF. Train model to predict AF-PGS from ECG. Evaluate for rare/novel variants in those that are considered high risk by PGS.
1. Separate known ~140 arrhythmia genes into ion-channel or structural proteins. Train based on LOF or severely pathogenic variants as predicted outcome from ECG.
1. Attempt to understand the types of effects on AF risk from genetic mutations associated with AF in structural genes, ion channel genes, metabolic genes, and inflammatory genes. 



