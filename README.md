# CARE_PA_PM2.5_Aug2nd_2023
Ten-minute average PM2.5 concentrations (µg m^-3) measured by Community Air Research Experience PurpleAir sensors on August 2nd, 2023.

## Overview
This project:
- Processes 10-minute PurpleAir data
- Applies QA/QC filtering
- Computes corrected PM2.5 concentrations
- Generates time series and boxplots
- Produces daily summary statistics

## Repository Structure
- `data/` raw PurpleAir dataset
- `code/` R scripts for analysis
- `output/` figures and processed data

## Methods
Key steps include:
- Averaging channels A & B
- Removing high humidity and inconsistent readings
- Applying correction (Mousavi & Wu, 2021)
  
## Requirements
R packages:
- dplyr
- ggplot2
- lubridate
- readr

## How to Run
1. Clone the repository:
