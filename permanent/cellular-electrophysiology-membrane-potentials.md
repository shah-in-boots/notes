---
date: 2026-08-03
tags:
  - physiology
  - biology
  - equation
---


# Membrane potential

At rest, the inside of a cell is approximately $-90\ mV$, and $0\ mV$ on the extracellular side.
The extracellular concentration of ions are typical of what is seen on a metabolic panel

- $[Na^+] = 140\ mM$
- $[K^+] = 4\ mM$

On the intracellular side the concentration is 

- $[Na^+] = 10\ mM$
- $[K^+] = 140\ mM$

That is driven by the original Nernst equation.
 
 $$
 E_{m} = \frac{RT}{zF} \times log_{10}(\frac{[C]_{o}}{[C]_{i}})
 $$
   
$E_m$ = resting membrane potential  
$R$ = gas constant ~ 8.3 J/K  
$T$ = temperature (Kelvin)  
$F$ = Faraday's constant = $9.65 \times 10^4 C/mol$

For potassium, which calculates out to be around $-90\ mV$, that looks like...

$$
E_{K^+} = 61.5 log_{10} \frac{[K^+]_{out}}{[K^+]_{in}}
$$

At rest, the primary $Na^+$ channel is closed, thus there both a concentration and electrical gradient from outwards to inwards that is maintained.
Simultaneously, at rest, there is a $K^+$ channel that is an inward rectifier that is open at rest, which allows some $K^+$ to be driven inwards down the electrical gradient preferentially over the concentration gradient. 

In the setting of hyperkalemia, the resting membrane potential can be depolarized, which in turn would lead to opening of sodium channels and sodium influx. 
If $[K^+]_{out} = 10\ mM$, then by the Nernst equation then $E_{K^+} = -67 mV$.

More details on how these are measured are in [patch-clamping](permanent/patch-clamping.md)

