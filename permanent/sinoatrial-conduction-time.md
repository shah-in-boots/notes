---
date: 2026-08-31
tags:
- electrophysiology
- electrogram
---

![Examples of the effect of S2 extrastimuli on the response of the SA node when assessing SA conduction time](resources/sinoatrial-conduction-time.png)

Circuit here that we are assessing is the SA node and there can be different responses. 
Responses are broken into different zones based on timing.
Different than in other arrhythmia testing because of unique automatic properties of the SA node.
These are the potential responses below, as initially described by @Straus1973 and @Dhingra1975

There nomenclature was...

$$
\begin{align}
A = A1 &= \text{spontaneous atrial beat} \\
A_T = A2 &= \text{atrial premature beat} \\
A_R = A3 &= \text{atrial return beat}
\end{align}
$$

## Collision

Collision is where the time between the last native beat and the first return beat is double the BCL. 

$$
A1 \textendash A1 \times 2 = A2 \textendash A3
$$

In this case, $A1 \textendash A2 = 530\ ms$, and the return beat $A2 \textendash A3 = 730\ ms$,  which adds up to 1320 ms (which is exactly double of the BCL, with $A1 \textendash A1 = 660\ ms$), thus the S2 must have collided with the already activated SA node.

## Reset

 Resetting is similar to the expected result of the maneuver with other re-entrant circuits. 
 Return beat is delayed, but by the S2 coming in early the SA node was captured and the next beat brought in as well. 

$$
\begin{align}
A1 \textendash A1 &< A2 \textendash A3 \\
A1 \textendash A2 + A2 \textendash A3 &< A1 \textendash A1 \times 2
\end{align}
$$
 
Resetting response is the only situation where SACT can be measured... 

$$
SACT = \frac{A2 \textendash A3 - A1 \textendash A1}{2}
$$

In this case, the $A2 \textendash A3 - A1 \textendash A1 = 100\ ms$, meaning the $SACT = 50\ ms$

## Interpolation

Interpolation is similar with other phenomenon, like PVC or PACs, where it does not reach or lead to a pause or delay in the next beat at all. 
The definition is...

$$
A1 \textendash A2 + A2 \textendash A3 = A1 \textendash A1
$$

## Reentry

Reentry occurs when the S2 enters the SA node and is able to exit through a different pathway than it entered, thus allowing it to exit earlier than the normally expected return beat.

$$
A1 \textendash A2 + A2 \textendash A3 < A1 \textendash A1
$$
