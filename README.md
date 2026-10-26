# Serum Butyrylcholinesterase and MASLD: NHANES 2021–2023

## Research title

**Serum Butyrylcholinesterase Catalytic Activity and Concentration in Relation to Transient Elastography-Quantified MASLD in U.S. Adults**

## Overview

This repository is intended to contain the R analysis workflow and shareable outputs for a study of serum butyrylcholinesterase (BChE) measures in relation to metabolic dysfunction-associated steatotic liver disease (MASLD) among U.S. adults, using NHANES August 2021–August 2023 data.

The finalized analysis dossier is the authoritative source for reported results. Repository updates should preserve those results and should not silently alter model specifications or estimates.

## Key finalized findings

- Analytic sample: **N = 5,122**
- MASLD cases: **N = 1,616**; weighted prevalence **31.10%**
- Fully adjusted association between BChE catalytic activity and MASLD: **aOR = 1.184** (95% CI 1.069–1.312; *P* = 0.0031)
- Significant fibrosis (LSM ≥ 8.0 kPa), Model 3: **aOR = 0.913** (95% CI 0.770–1.083; *P* = 0.2744)
- CAP association: **β = +4.45 dB/m** (95% CI 3.00–5.90; *P* < 0.0001)
- Cross-validation complete cases: **N = 4,941**; baseline AUC **0.8267**, enhanced AUC **0.8339**, ΔAUC **+0.007164** (corrected *P* = 0.0136); ΔBrier **−0.003830** (*P* = 0.0024)

These figures are recorded here for project orientation and should be checked against the final validated dossier before any publication or reuse.

## Repository contents

The repository is being prepared to include:

- The single master R script for the finalized analysis
- Reproducible, publication-ready figures and tables
- Documentation of the workflow and required packages

Files will be added as they are prepared and checked. Do not assume that a file is present until it appears in the repository.

## Data and privacy

NHANES is a public survey program. This repository should contain analysis code and appropriately shareable outputs, **not raw data files copied into the repository**. Obtain source data from the official NHANES website and follow applicable data-use guidance. Do not commit credentials, private information, temporary files, or unreviewed participant-level exports.

## Reproducibility

Before running the analysis:

1. Install a compatible version of R.
2. Review the package dependencies and data-input paths in the master script.
3. Obtain the required NHANES source files from their official source.
4. Run the master script from the documented project directory.
5. Compare generated outputs with the finalized validated dossier.

## Authors and supervision

- **Haron Mohammed Ali** — School of Computing and Artificial Intelligence, Lovely Professional University, Punjab, India
- **Robin Prakash Mathur** — School of Computing and AI, Lovely Professional University, Punjab, India; research supervisor and Head of Department

## Status

Research analysis and documentation repository in preparation. Do not describe the manuscript as accepted or published unless that status has been formally confirmed.
