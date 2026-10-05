---
date: 2026-10-01
tags:
- electrocardiogram
- device
---

__RNRVAS__ stands for repetitive non-reentry ventriculoatrial synchrony, which is a lower rate behavior that requires retrograde conduction in a dual tracking system.

Described in a review by @Sharma2016

Most commonly, a PVC will lead to retrograde PAC that falls within PVARP. 
The device will not recognize the PAC and will hit its VA clockout time, and a paced A will occur onto refractory atrial tissue, leading to functional non-capture. 
The AV clockout will then occur, leading to a PVC, which then sends a retrograde A that again falls into refractory tissue.
The largest concern is that can have an A fall during a vulnerable atrial repolarization period, leading to AT or AF events.

![Example recording strip of a PVC that then leads to RNRVAS](resources/RNRVAS.png)

RNRVAS and PMT are the two endless loop tachycardias that can happen with pacemakers.

To limit RNRVAS happening, can try multiple approaches...

1. Decrease PVARP to improve retrograde atrial sensing (increases PMT risk)
1. Decrease AV delays
1. Lower the lower rate limit 
1. Algorithms: device specific approaches, such as NCAP (non-competitive atrial pacing = delays AP by 300 ms when a retrograde A falls into PVARP), or synchronous AP-on-PVC (functional non-capture of retrograde atrial impulse)

This all essentially gets back to the atrial escape interval (**AEI**).

$$
AEI = LRI - AVD
$$

... such that a slower rate (and thus longer lower rate interval) increases time to allow for atrial escape, avoiding AP.