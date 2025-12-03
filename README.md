# Uirapuru Receiver Project Documentation

This repository contains the documentation and analysis code for the Uirapuru Receiver project, which focuses on RF characterization of horn antenna reception components.

## Contents

- `Receptor_Uirapuru.ipynb`: Main Jupyter Notebook with analysis
- `S_parameters/`: Directory with S-parameter measurement data in CSV format
- `generate_figures.py`: Script to generate figures for the documentation
- `Uirapuru_Project.tex`: LaTeX source for the project documentation
- `.gitignore`: Git ignore file for project management

## Prerequisites

To work with this project, you need:

1. Python 3.7 or higher
2. Required Python packages:
   ```bash
   pip install pandas matplotlib numpy jupyter
   ```

## Generating Figures

To generate the figures used in the documentation:

```bash
python generate_figures.py
```

This will create PNG files in the `figures/` directory.

## Compiling the LaTeX Document

To compile the LaTeX document into a PDF, you need a LaTeX distribution installed (such as TeX Live, MiKTeX, or MacTeX).

Compile the document using:

```bash
pdflatex Uirapuru_Project.tex
```

You may need to run this command twice to properly generate the table of contents and references.

## S-Parameter Files

The `S_parameters/` directory contains CSV files with S-parameter measurements. Each file has the following structure:

1. Header row with column names
2. Empty row
3. Data rows with frequency (Hz) in the first column and S-parameter values (dB) in the second column

Common files include:
- S11 measurements for different ports of the hybrid component
- S21 measurements for various components (filter, LNA, isolator, receptor)
- S22 measurements for some ports

## Project Overview

The Uirapuru Receiver project focuses on characterizing the RF properties of horn antenna reception components. Key components analyzed include:

- Horn antenna
- Low Noise Amplifier (LNA)
- Hybrid coupler
- Isolator
- Filters
- Digital backend (SKARAB)

Measurements were performed using a Rohde & Schwarz ZNB Vector Network Analyzer, providing high-precision S-parameter data across the frequency band of interest.