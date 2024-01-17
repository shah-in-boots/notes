---
date: 2024-01-16
category: project
stage: planning
---

# Introduction

The CARRS study (**C**entre for c**A**rdiometabolic **R**isk **R**eduction in **S**outh-Asia) is described in @Nair2012. 
It's purpose was initially to evaluate the role of risk factors for cardiovascular disease progression in South Asian (primarily India). 
We proposed to evaluate the role of cardiotoxicity from diabetes to help explain some of the additional risk, focusing on the effect of hyperglycemia and insulin resistance on global electrical heterogeneity.

This is an ongoing project.

# Methods

## Study Overview

-   Subset of CARRS that have ECG data
-   Exposure = diabetes status
-   Outcome = ECG changes measured by global electrical heterogeneity (GEH)
-   Covariates = insulin resistance, obesity, age, sex, hypertension, cardiovascular dz
-   Model relationship with consideration of potential modifiers, confounders, and interaction terms

## Study Measures

-   Diabetes defined by FBG, A1c, or treatment

    -   FBG \>= 126
    -   HbA1c \>= 6.5%
    -   HOMA = (insulin mU/L / 6 \* FBG mg/dL) / 405 ... marker of insulin resistance [@Matthews1985]

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

## ECG overview

ECG collected on CARRS patients from Delhi, converted to XML for processing, an GEH parameters were created.[@Waks2016] GEH:

-   SVG magnitude
-   spatial QRST angle
-   sum absolute QRST integral 

Additional Parameters:

-   QT intervals
-   RR intervals

## Statistical Analysis

- descriptive/frequentist statistics of cohort clinical and GEH parameters
-  unadjusted linear regression models
-  adjusted linear regression models
-  analysis of impact of additional covariates on GEH parameters
-  causal analysis of insulin resistance and acute hyperglycemia

# Results

This is a summary of the most important findings.



#diabetes
#electrocardiography 
#epidemiology 
#manuscript 