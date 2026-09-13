![](figures/Maruyama2014/fig-4-x44-y95.png)---
date: 2026-09-07
tags:
  - maneuvers
  - electrophysiology
  - equation
  - electrogram
---

The post-pacing interval (**PPI**) is a way to assess distance from an arrhythmia circuit, but is primarily informative when the circuit can be entrained, and not just overdrive suppressed.

Further information on [entrainment-maneuvers](permanent/entrainment-maneuvers.md) 

$$
PPI = TCL + 2x
$$

... where $x$ is distance from the circuit

# Fundamental assumptions

When assessing PPI, specific assumptions are required...
1. Paicng captures
1. Pacing does not alter the circuit path or conduction times
1. Depolarization at the pacing site (local EGM) can be identified

Certain situations arise when the $PPI < TCL$...
1. Measurement of a far field potential (error)
1. Unstable reentry circuit
1. Inadvertent capture of distant tissue at high output pacing

# $N+1$ method

@Soejima2001 worked with [William-G-Stevenson-MD](permanent/William-G-Stevenson-MD.md) to present an alternative method for measuring entrainment responses. 
Due to increased stimulation artifact, the local EGM was often hard to evaluate. 
Alternative was to use a QRS that was $N+1$ from the stimulus, and then measure a subsequent EGM to its corresponding $N+1$ QRS

The main conceptual idea is that the measurement is from stimulus to a reliable, repeating fiducial point, like a QRS or a V-signal on a distant structure (e.g. RV apical catheter).
Then, assessing the $EGM_{N+1} \textemdash QRS_{N+2}$ difference with the $S \textemdash QRS_{N+1}$ would provide a difference that is equivalent to the $PPI - TCL$ assessment.
Following examples from [Soejima2001](literature/Soejima2001.md)

![Entrainment of VT from outerloop and response](figures/Soejima2001/fig-5-x117-y471.png)

![Entrainment of VT at adjacent bystander position and response](figures/Soejima2001/fig-5-x116-y213.png)

The summary steps to perform this maneuver are...

1. Measure from $S \textemdash QRS_{N+1} = x \ms$
1. After the tracing recovers from stimulation artifact, measure backwards from the reference fiducial point that was seen on $QRS_{N+1}$ and measure backwards $x\ ms$ to the stimulating electrode. 
1. Measure distance from identified position on the local catheter to the the local potential (if in the circuit, for example, would be 0)

# Other entrainment attributes

Another important concept is the idea of __number needed to entrain__ (**NNE**).

![X axis represents numbers needed to entrain and Y axis represents the distance from circuit in miliseconds, by @Maruyama2014](figures/Maruyama2014/fig-4-x44-y95.png)

[Maruyama2014](literature/Maruyama2014.md) showed that the could estimate the distance based on how long it took to achieve entrainment, with $NNE \ge 20$ getting closer to over 30 ms away.