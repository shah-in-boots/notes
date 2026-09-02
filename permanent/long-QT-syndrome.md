---
date: 2026-08-28
tags:
- drugs
- arrhythmia
- genetics
---

Parent note to organize this is[inherited-arrhythmia-syndromes](permanent/inherited-arrhythmia-syndromes.md)

Overall the top 3 (LQT1 ~ 45%, LQT2 ~ 45%, LQT3 ~5%) make up 95% of the cases.
Reported rate of about 1:2000

When autosomal dominant, considered *Romano Ward Syndrome*.
When autosomal recessive, considered *Jervell and Lange Neilsen syndrome* when associated with congenital deafness.
The last common form of this is through acquired long QT. 
LQTS can cause syncope, sudden death, seizures, and sudden infant death syndrome.

In regards to the ECG...
QT measurement, generally in lead II and V5-V6, will measure the $QTc > 480\ ms$.
Borderline QTc measurements include $>440\ ms$ in men, and $>450\ ms$ in women.
This eventually can lead to *Torsades de pointe* and macroscopic T wave alternans.
ECGs also form characteristic pattern, as documented by @Krahn2022 in [Krahn2022](literature/Krahn2022.md)

Generally, beta-blockers (*nadolol*) show efficacy in LQT1 and LQT2, and can be assessed via repeat ECG stress testing. 
In LQT3, beta-blockers less clear and more likely to receive ICD and sodium blockade to reduce VT risk. 
ICD otherwise reserved for high risk individuals (prior aborted SCA or syncope). 

Risk stratification in LQTS is difficult due to differences in penetrance and the type of mutation, with original paper in [Priori2003](literature/Priori2003.md). 
The overall $QTc > 500\ ms$ remains a classical risk factor for increased SCA, and there appeared to be pattern by differences in sex.

![4th quartile are patients with $QTc > 500\ ms$](figures/Priori2003/fig-5-x78-y547.png)

![Schema from @Priori2003 showing gender differences, with men who have LQT3 have higher risk as well.](figures/Priori2003/fig-7-x136-y464.png)

We generally now consider high risk to be:

- $QTc > 500\ ms$
- Prior sudden death event
- Syncope or symptoms of VT while on beta-blocker therapy
- Gene-specific risk, such as LQT3

Other contexts worth knowing:

- Pregnancy doesn't increase risk except for LQT2 in the early post-partum time period
- Siblings with SCD don't increase risk, *however highly malignant families do exist and warrant intervention*
- Boys have $\uparrow$ risk over girls until puberty
- After puberty, $\uparrow$ risk in women
- After age 40, overall risk decreases
- LQT3, as beta-blockade don't work

Acquired long QT is possible as well, as seen in [acquired-long-QT-syndrome](permanent/acquired-long-QT-syndrome.md)

# LQT1

Caused by $LOF$ mutation in *KCNQ1*

*KCNQ1* is primarily responsible for the $I_{Ks}$ current, which is one of the few $K^+$ channels, in this case named *KvLQT1*, that is affected by beta-phosphorylation, leading it to be responsive to adrenergic stimulation.

Exercise-induced QT prolongation actually happens because certain LQT1 genotypes are no longer responsive to beta-phosphorylation and thus are unable to compensate and adapt at higher heart rates.
Unopposed $I_{CaL}$ occurs, which is augmented when *Cav1.2* is phosphorylated, leading to longer APD due to longer phase II. 
Summarized by @Schwartz2012

When autosomal dominant, considered *Romano Ward Syndrome*.
When autosomal recessive, considered *Jervell and Lange Neilsen syndrome* when associated with congenital deafness.
The last common form of this is through acquired long QT. 

When *KvLQT1* is mutated in both alleles, can lead to deafness though decreased production of endolymph in the cochlea.

![Broad-based, normal, but long, T wave due to $LOF$ in $I_{Ks}$](figures/Krahn2022/fig-7-x141-y513.png)

# LQT2

Caused by $LOF$ mutation in *KCNH2*

Pregnancy: In the acute post-partum period, there is increased risk of SCA 


![Bifid T waves seen due to $LOF$ in $I_{Kr}$](figures/Krahn2022/fig-7-x144-y377.png)

Genotype specific treatment has been to add $K^+$ supplementation or aldosterone antagonist to increase serum $K^+$ levels to counteract the deficiency of the HERG protein and the faulty $I_{Kr}$ current

# LQT3

Caused by $GOF$ mutation in *SCN5A*

![Long iso-electric component of QT due to the GOF in $I_{Na}$](figures/Krahn2022/fig-7-x124-y245.png)

Genotype-specific treatment here includes sodium blockade with mexiletine or flecainide, however can also induce a Brugada-like pattern.
Not yet shown to decreae mortality, but does shorten QTc


# LQT7 (Andersen-Tawil syndrome)

- Considered a pseudo prolonged QT condition but actually a prolonged QU and prominent U waves (often fused to prior T wave)
- Associated with intermittent muscle weakness (periodic paralysis with hypokalemia) 
- Due to $LOF$mutation  in *KCNJ2* which leads to decrease in $I_{K1}$ inward rectifier current
- Leads to depolarized resting membrane potential
- High burden of ventricular ectopy seen
- Appears to respond to flecainide therapy, doesn't respond to beta-blockers
