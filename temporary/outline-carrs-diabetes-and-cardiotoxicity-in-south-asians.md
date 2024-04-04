---
date: 2024-04-03
category: temporary
stage: considering
tags:
  - todo
---

# Introduction

CARRS: 

- The CARRS study (**C**entre for c**A**rdiometabolic **R**isk **R**eduction in **S**outh-Asia) is described in @Nair2012. 
- It's purpose was initially to evaluate the role of risk factors for cardiovascular disease progression in South Asian (primarily India). 
- CARRS is a large study of >30k South Asians, who have particularly high risk for DM s- morbid obesity 
- Not fully understood how DM causes increased CV mortality/morbidity 
- Diﬀicult to assess risk in Western populations due to high comorbid obesity 
- ECG changes may identify part of the cardiotoxicity of diabetes

Cardiovascular mortality is a growing epidemic in South Asians, with estimates showing that South Asian ethnicity associates with a 2-fold increased risk of developing cardiovascular disease. 
Diabetes has been implicated in this excess risk because of its high prevalence and association with ischemic heart disease, cardiomyopathy, and arrhythmia. 
Diabetes in South Asians is of particular interest as this population experiences early beta-cell dysfunction and decreased insulin production, which contrasts with other races and ethnicities. 
A higher diabetes incidence is also found in South Asians with normal weight compared with normal-weight individuals in other races/ethnicities.  
Previous research has shown that diabetes may be an independent risk factor for sudden cardiac death, but this relationship in South Asians is not clear [@Lee2021].
Furthermore, the electrophysiological mechanisms through which this may occur are not clear and have important implications on diabetes management and prognosis. 

Diabetes and GEH:

- Diabetes mellitus leads to changes in global electrical heterogeneity independent of traditional cardiovascular risk factors. 
- ECG parameters have different implications in different disease states 
- Persistent hyperglycemia leads to cardiac changes that are mediated through insulin resistance (e.g. myocardial fibrosis) 
- Can control for insulin resistance (HOMA), obesity, persistent hyperglycemia, age, hypertension, and cardiovascular disease to assess relationship between diabetes and ECG findings (cardiotoxicity)

Recently, several ECG-based metrics have been discovered as important prognostic markers of sudden cardiac death, including the spatial QRS-T angle (SA), frontal T-axis, QT interval, and sum absolute QRST integral (SAI QRST) [@Tereshchenko2018a]. 
These metrics may help to uncover some of the subclinical and clinical mechanisms underlying heart disease in diabetics, including myocardial fibrosis, amyloidosis, atherosclerosis, and microvascular disease [@Tereshchenko2018a; @Waks2016].

Hypothesis/proposal: 

- We proposed to evaluate the role of cardiotoxicity from diabetes to help explain some of the additional risk, focusing on the effect of hyperglycemia and insulin resistance on global electrical heterogeneity.

In this study, we evaluate the relationship of diabetes with the aforementioned cardiac repolarization metrics in a cohort of South Asians who were sampled from Delhi sample and underwent electrocardiographic monitoring. 
We hypothesized that diabetes and its diagnostic components (fasting glucose, hemoglobin A1c) associated with worsened electrocardiographic markers of sudden cardiac death. 

# Methods

## Study Population

-   Subset of CARRS that have ECG data
-   Exposure = diabetes status
-   Outcome = ECG changes measured by global electrical heterogeneity (GEH)
-   Covariates = insulin resistance, obesity, age, sex, hypertension, cardiovascular dz
-   Model relationship with consideration of potential modifiers, confounders, and interaction terms

## Diabetes

-   Diabetes defined by FBG, A1c, or treatment
    -   FBG \>= 126
    -   HbA1c \>= 6.5%
    -   HOMA = (insulin mU/L / 6 \* FBG mg/dL) / 405 ... marker of insulin resistance [@Matthews1985]

## Clinical Measures

-   Obesity
    -   **BMI**
        -   underweight: \< 18.5
        -   normal: \>= 18.5 & \< 23
        -   overweight: \>= 23 & \< 27
        -   obese: \>= 27
    -   Body fat percentage (potential): impedance, skin fold measurements
-   Hypertension (AHA): SBP \>= 130, diastolic \>= 80, or treatment
-   Coronary dz: reported or document hx of heart dz
-   Age
-   Sex

## Global Electrical Heterogeneity

ECG collected on CARRS patients from Delhi, converted to XML for processing, an GEH parameters were created.[@Waks2016] GEH:

- SVG magnitude
- spatial QRST angle

Additional Parameters:

- QT intervals
- RR intervals
- Wilson's vector gradient

## Statistical Analysis

- descriptive/frequentist statistics of cohort clinical and GEH parameters
-  unadjusted linear regression models
-  adjusted linear regression models
-  analysis of impact of additional covariates on GEH parameters
-  causal analysis of insulin resistance and acute hyperglycemia

# Discussion

## Key Findings

- Diabetes is strongly associated with changes in GEH, particularly magnitude of SVG and spatial QRST angle, even after covariate adjustment 
- Diabetes leads to a decrease in SVG magnitude, and an  increase in QRST angle 
- Diabetic cardiotoxicity may be mediated through changes to the myocardium 
- Insulin resistance appears to mediate a majority of the increase  in QRST angle and SVG magnitude 

Support from literature: 
- SVG is well-supported clinial tool for evaluating cardiac abnormalities [@Hurst2005]
- GEH is associated with SCD in ARIC and CHS [@Waks2016a] 
- Diabetes and SVG has not yet been studied

## Potential Mechanisms

- Decreases in SVG magnitude suggests a fibrosing process 
- Diabetes is known to cause myocardial fibrosis  [@Jia2018; @Russo2016]
- Increased QRST angle is seen in amyloidosis [@Medvedovsky2020]
- Diabetes may mimic amyloidosis due to similarities with fibrosis 

## Limitations

- Although GEH has increased SCD risk, this study is cross-sectional and SCD outcomes were not includedavailable  
- Subset is only 5k participants, availability of  treatment/medications was limited, located in a single city, not powered to adjust for additional risk factors (diet, sedentary lifestyle) 
- More refined markers of insulin resistance not available

## Conclusion

- GEH changes in diabetes are mediated through persistent hyperglycemia and insulin resistance. 
- GEH changes may serve as an early, non-invasive marker of myocardial fibrosis