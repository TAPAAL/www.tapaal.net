---
title: TAPAAL 3.0.0 Released 
date: 2014-02-26T20:40:02+01:00
draft: false
---

The TAPAAL team is very happy to announce a major upgrade of TAPAAL. The new release of 3.0.0 includes numerous GUI improvements and bug fixes, together with the following selected new features.

- GUI and verification support for timed workflow analysis (available under Tool/Workflow analysis) that allow to check for soundness and strong soundness of workflow nets and computing the shortest and longest execution times.
- A brand new dedicated verification engine verifypn that supports an efficient verification of untimed nets and allows for a quick linear over-approximation test even for timed nets.
- A new optimized broadcast translation to UPPAAL timed automata, supporting all the new features like weighted arcs and urgent transitions, and providing performace optimizations for nets containing untimed places.