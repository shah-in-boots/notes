---
date: 2026-07-29
tags:
  - todo
  - causality
  - epidemiology
---

Do-calculus incorporates the concept of the *do-operator* by Judea Pearl. 

As an example, traditional cardiovascular risk factors use the ...

$$P(CHD | SBP = s)$$

...while in reality it is the interventional probability that matters, represented as...

$$
P(CHD | do(SBP \leftarrow s))
$$

... which essentially means the process of changing a blood pressure, regardless of hte patients actual baseline characteristics. Practically speaking, clinicians will treat to a target blood pressure, and that risk is not including the comorbid characteristics (and thus). 
