# RDE-GAIT
Cycle-resolved 3D gait symmetry analysis (RDE-GAIT) from single-ankle IMU data; code for paper and figures.

This repository contains the Python implementation of the Reza Dimensional Equilibrium-Gait (RDE-GAIT) method for cycle-resolved 3D gait symmetry analysis from single-ankle IMU data.

Main features:
- Load IMU .mat / APDM .h5 files
- Reconstruct leg vector and estimate hybrid leg length
- Compute per-cycle equilibrium index E and classify cycles as consistent, inconsistent, or semi-consistent
- Export CSV/JSON summaries and diagnostic plots

This code accompanies the manuscript:
RDE-GAIT: A Novel Mirror-Equilibrium Approach to Cycle-Resolved 3-D Gait Symmetry, Contrasted with Traditional DFA
