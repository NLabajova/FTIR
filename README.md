# FTIR Evaluation

Python-based FTIR analysis pipeline for protein secondary-structure characterization, developed for α-synuclein experiments.

## Features

- Import FTIR spectra from tab-separated TXT files.
- Extract the Amide I region (1600–1700 cm⁻¹).
- Perform linear baseline correction.
- Fit five Gaussian components with fixed peak positions.
- Calculate Gaussian peak areas and relative contributions.
- Visualize experimental spectra, fitted components, and residuals.
- Process multiple FTIR files automatically.
- Export results to Excel and plots to PNG.

## Requirements

Python, JupyterLab, NumPy, SciPy, Matplotlib, Pandas, and OpenPyXL.

## Usage

Open `FTIR.ipynb` in JupyterLab, configure the input and output directories, and execute the analysis cells.

## Scientific limitations

The Gaussian components use fixed peak positions originally selected for proteins measured in D₂O. Relative fitted peak areas should not be interpreted as independently validated secondary-structure fractions.

## Attribution

Adapted from the FTIR analysis code by Anastasia Ragulskaya:

https://github.com/anastasia-ragulskaya/FTIR_code

Redistribution of adapted source code is subject to the original project's licensing terms.
