---
date: 2026-07-28
category: concept
stage: raw
tags:
  - todo
  - electrogram
  - physics
---

Sources for this come from...
- [Lecture](https://youtu.be/MBj1Rx8zy2g?si=Y8mVmQ_DKCUTOR2c) from Warren "Sonny" Jackman

The components of a bipolar waveform include both near-field and far-field components.
 
The initial component is the far-field ventricular signal (just after the V-stimulation artifcation). The sharp terminal signal is the atrial signal and is underneath the bipole.  _Waveform amplitude reflects the amount of tissue, not its proximity to the recording bipole._

![](../resources/paste-b7828e20ed9eed0db445b75254ccce6469ab0bc3.png)

The proximity of hte electrodes effects the recording range. 

![](../resources/paste-a879f227843d09d9101f93ec45c56a5ca0f266b3.png)

The top recording is wider spacing, while the bottom recording is the most narrow spacing, which is why we have decreased far-field signal and higher resolution, sharper near-field signal.

![](../../../resources/paste-571e4e2159f3175e22f616e126b02b6e6c9f06a6.png)

Unipolar signal translation to bipolar signal is mathematical subtraction of the proximal (positive) and distal (negative) bipoles.

$$
EGM_{bipolar} = EGM_{unipolar_{distal}} - EGM_{unipolar_{proximal}}
$$

![](../resources/paste-030f2018a6899ea4a68546085359815d703d6f22.png)

The same math applied can help understand directionality. If the wavefront is coming (assumed in parallel) towards the distal and then proximal bipoles, an rSr' pattern is formed. 
If that is reversed along the same axis, a qRs pattern is seen.
And then, if hte bipole is perpendicular to the wavefront than the proximal electrode serves as a reference electrode and makes a *pseudo-unipolar* EGM, otherwise called a *close unipolar*, which even can be used for timing as it elminates the baseline current noise.

![](../resources/unipolar-and-bipolar-electrograms.png)
