# Dose-Response-Analysis
Dose-Response Analysis of Drug1 and Drug2 on Cancer Cell Lines using RStudio

## Keywords
`#dose-response` `#Rstats` `#cancer-research` `#IC50` `#drug-discovery`

# Dose-Response Analysis of Anti-Cancer Compounds

This repository contains R scripts for analyzing dose-response relationships of experimental compounds on cancer cell lines. The code is designed to calculate IC50 values and generate publication-quality dose-response curves.

## Key Features
- Dose-response curve plotting with ggplot2
- IC50 calculation using drc package
- Support for multiple replicates and time points
- Fully customizable analysis pipeline

## Getting Started

### Prerequisites
- R (version 4.0 or higher)
- RStudio (recommended)

### Installation
1. Clone this repository
2. Install required R packages:
```R
install.packages(c("ggplot2", "drc", "tidyr", "dplyr"))

Usage
Replace placeholder values in the scripts:

value1, value2 etc. → Your experimental concentrations

drug1, drug2 → Your compound names

Cancer Cell Line 1/2 → Your cell line names

Run the analysis scripts in order:

01_data_preparation.R

02_dose_response_analysis.R

03_visualization.R

File Structure

├── README.md
├── data/                   # Example data files
├── scripts/
│   ├── 01_data_preparation.R
│   ├── 02_dose_response_analysis.R
│   └── 03_visualization.R
└── results/                # Output figures and tables

Customization
Adjust dose ranges in doses vector

Modify plotting parameters in ggplot2 commands

Change statistical models in drc functions

Outputs
The scripts will generate:

Dose-response curves (PDF/PNG)

IC50 values with confidence intervals

Statistical summary tables

Acknowledgments
Built with R and RStudio

Uses ggplot2 for visualization

drc package for dose-response modeling

Important Notes
This repository contains generic template code only

No actual research data is included

Designed for users to input their own experimental data

Original research data cannot be shared as the study is currently under review for publication
