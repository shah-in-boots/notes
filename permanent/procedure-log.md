---
date: 2024-06-14
category: reference
stage: building
tags:
  - clinical
  - procedures
---

I wanted a dynamic way to log clinical procedures that could be used to update my procedure counts over my career as an internist, cardiologist, and electrophysiologist.
The general requirements are:

1. Logs include both clinical encounters and procedures performed
1. Use a similar heading system for both to allow for a common log form (e.g. a single excel sheet)
1. Fits the general procedure categories assigned by COCATS for general cardiology 
1. Works for the more detailed/intricate procedures done in electrophysiology

When considering these needs, there are three categories of headings that help organize the data:

- Common
	- Hospital
	- MRN
	- Date
	- Diagnoses
	- Notes
	- Special documentation
- Procedures
	- Procedure category (e.g. coronary angiography)
	- Procedure subcategory
	- Procedure "location" (such as access location)
	- Device type or procedure modifier (e.g. *closure* using *Angioseal*)
	- Device compnay or type (like CIED interrogations)
- Patient encounters:
	- Setting, such as inpatient or outpatient... if a procedure, could be in lab or at bedside
	- Type = consultation, follow-up, primary service
	- Level of care = floor, stepdown, ICU

To create common headings requires some generalizations that may lose specificity in the headings. 
This seems like it would occur most often with procedures.
For example, if a defibrillator was interrogated, the information to know would be: 1) what type of device, 2) what company, 3) programming changes.
The headings in the example could be specific langauge to the main event type.

| event | category | specification | modifier | setting | level
 | - | - | - | - | - | - |
| procedure | coronary angio | femoral | - | - | - | 
| procedure | PCI | LAD | - | - |  - | 
| procedure | RHC | subclavian | - | bedside | - | 
| procedure | TTE | - |  - | bedside | - |
| procedure | TTE | - | - | - | - |
| procedure | TEE | - | - | bedside | - |
| procedure | TEE | - | - | - | - | 
| procedure | CIED | interrogation | S-ICD | - |
| encounter | follow-up | - | - |  outpatient | - | 
| procedure | EPS | PVI | cryo | - | - |
| procedure | closure | manual | femoral | - | - |
| encounter | follow-up | - | - | outpatient | - |
| encounter | consultation | - | - | inpatient | ICU |

From these "random" examples, it seems like there is a clear pattern switch between patient encounters and procedures.
Patient encounters utilize the *category* column and the *setting* $\pm$ *level* when inpatient.  
Procedures are more complex, as they seem to require *specification* and *modifier* not uncommonly, but never need *level*. 