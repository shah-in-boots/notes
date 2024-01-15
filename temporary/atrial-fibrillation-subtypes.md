---
tags: [computational, afib, research, ideas]
---

# Atrial Fibrillation Clinical Phenotyping Using Machine Learning

## Background

- Currently use limited classification system:
	- Lone
	- Paroxysmal
	- Persistent
	- Long-standing Persistent
	- Permanent
- Does not capture underlying pathology, etiology, triggers, genetic components

## Proposal

Big data: 

1. Use "big data" approach
1. X-dimensionality clustering based on clincial covariates (support vector machines)
1. Weight importance of clinical factors

Validation: 

1. Validate with local cohorts and tie to both treatment + outcomes
1. Integration of intracardiac mapping data (voltage, geometry, volume, dominant frequency)

---

Data sources:

- UIC cohort
- ARIC cohort (visit 7 c- 2 week Holter data)
- MVP + VA (25 million records)
