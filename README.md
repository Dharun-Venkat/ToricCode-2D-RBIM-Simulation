# 2D RBIM Simulation to find the Critical Point

Author: Dharun Venkateswaran \\
Affiliation: Dept. of Physics, Imperial College London \\
Date of Upload: 15/09/2026 \\
Contact: dharun.venkateswaran@eng.ox.ac.uk; dharun.v2003@gmail.com 

------------------------------------------------------

Purpose: As part of the Quantum Fields and Fundamental Forces (QFFF) MSc summer research project (dissertation) at Imperial College London, the Quantum Error Correction (QEC) to Statistical Mechanics (StatMech) map proved by Dennis et al. [1] was investigated. The project aim was to numerically find the error threshold of the Toric Code by finding where the Nishimori line [2] and the phase-boundary of the 2D Random-Bond Ising Model (RBIM) intersected, the so-called Nishimori point $N$. 

------------------------------------------------------

## Brief Introduction

The central challenge of quantum computing to reach fault-tolerant quantum computation (FTQC); QEC is the current best method we have for getting to FTQC. A type of QEC scheme is the surface code, and the toric code, as initially defined by Kitaev [3], is the specific example considered. Surface codes have so-called _error thresholds_ such that if the error-rate of the code is below this quantity then FTQC can be carried out to an arbitrary length scale, even on noisy hardware. Ref. [1] found that there is a one-to-one correspondence with the error threshold of the Toric Code and the Nishimori point of the 2D RBIM. Thus, existing statistical mechanics techniques, like those described by Honecker et al. [3, 4], used to find the Nishimori point can be used to investigate the error thresholds for QEC codes.  \\

This repository contains the code written for the project. It evaluates transfer-matrices on a cylindrical lattice using finite-size scaling, reproducing the work done by Honecker et al. [3, 4]. It culminates in estimating the Nishimori point of the 2D RBIM which is equivalent to the error threshold of the toric code. 

------------------------------------------------------

## How To Use



------------------------------------------------------

## Sources

[1]: E. Dennis, A. Kitaev, A. Landahl, and J. Preskill. “Topological quantum memory”. In: Journal of Mathematical Physics 43.9 (2002), doi: 10.1063/1.1499754. \\
[2]: H. Nishimori. “Exact results and critical properties of the Ising model with competing interactions”. In: Journal of Physics C: Solid State Physics 13.21 (1980), doi: 10.1088/0022-3719/13/21/012. \\
[3]: A. Honecker, M. Picco, and P. Pujol. “Nishimori Point in the 2D ±J Random-Bond Ising Model”. In: Physical Review Letters 87.4 (2001), doi: 10.1103/PhysRevLett.87.047201. \\
[4]: M. Picco, A. Honecker, and P. Pujol. “Strong disorder fixed points in the two-dimensional random-bond Ising model”. In: Journal of Statistical Mechanics: Theory and Experiment (2006). doi: 10.1088/1742-5468/2006/09/P09006. \\
