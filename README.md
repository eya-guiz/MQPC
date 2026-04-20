# Model Predictive Quantum Control – Code

This repository contains the code used to generate the results for the paper on Model Predictive Quantum Control.

## Implemented Schemes

- Terminal Equality Constraint (TEC) – free (only input constraints)
- Terminal Equality Constraint (TEC)
- Tracking

## Numerical Studies

- Comparison of different schemes  
- Runtime and convergence analysis for varying prediction horizon lengths \( L \)  
- Robustness comparison of TEC-MPQC with optimal control using GRAPE (open-loop)  
- Runtime comparison of the MPQC algorithm using different optimizers:
  - IPOPT
  - GRAPE
  - Krotov

## Notes

- The code is intended to reproduce the results presented in the paper.
- It is not fully optimized or cleaned, but all relevant scripts are included.
