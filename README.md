# Survival Analysis of Ice Cream Machines

Analysis of censored survival times of ice cream machines: how warranty period and manufacturer relate to failure risk.
Course project for *Counting Processes*.

**Project page:** https://parsa-kamali.de/projects/survival-analysis-machines.php

## Methods
- Nelson-Aalen and Breslow estimators of the cumulative hazard
- Cox proportional hazards models, including time-dependent covariates
- Parametric relative risk regression
- Hypothesis tests and a simulation study

## Repository contents
| File | Description |
|---|---|
| `FinalReport.Rmd` | Final report with all models and results |
| `dataset_summary.Rmd` | Dataset description and summary statistics |
| `Counting_Process_Final (1).ipynb` | Main analysis notebook (R kernel) |

## Tech stack
R (survival, survminer, MASS), R Markdown, Jupyter with the R kernel

## How to run
Run `install.packages(c("survival", "survminer", "MASS"))`, then open the notebook with an R kernel (IRkernel) or knit `FinalReport.Rmd` in RStudio.
