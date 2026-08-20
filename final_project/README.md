# Dementia and Alzheimer's mortality rates in England and Wales
My final project for Aarhus University's Digital Archives and Methods course explores dementia and Alzheimer's mortality rates in England and Wales.


## Overview
Using Office for National Statistics (ONS) data, this project aims to explore trends in dementia and Alzheimer's mortality in England and Wales. The analysis produces several visualisations examining how deaths rates have changed over time (2001-2019) and how they vary by demographic and geographic factors.


## Features
- **`dementia_deaths.csv`** — registered deaths due to dementia and Alzheimer's disease, England and Wales, 2001–2019
- **`dementia_deaths_by_sex_2019.csv`** — 2019 death counts broken down by sex
- **`dementia_deaths_by_age_sex_2019.csv`** — 2019 death counts by age group and sex
- **`dementia_deaths_by_region_cause_2019.csv`** — 2019 age-standardised mortality rate by region, with confidence intervals
- **`Final_project.Rmd`** — full analysis script producing all plots below



## Repository Structure
``` r
final_project
├── data
│ ├── dementia_deaths.csv
│ ├── dementia_deaths_by_sex_2019.csv
│ └── dementia_deaths_by_age_sex_2019.csv
│ └── dementia_deaths_by_region_cause_2019.csv
└── README.md
```


## Getting started

### Prerequisites
- Install R(>=4.2) and RStudio
- Required R package: "tidyverse"


#### Installation

Clone the repository:
```bash
git clone https://github.com/Digital-Methods-HASS/au814638_law_petula.git
cd au814638_law_petula/final_project
```


Install the required package:
```r
install.packages("tidyverse")
```


### Usage

1. Open 'Final_project.Rmd' in RStudio
2. Ensure the four '.csv' files are located in a subfolder relative to the '.Rmd' file.
3. Run the script or knit to generate all plots


## Data Source
All data was sourced from the Office for National Statistics (ONS), covering registered deaths and age-standardised mortality rates attributed to dementia and Alzeimer's disease in England and Wales


## Data License

The ONS data used in this project is made available under the [Open Government Licence v3.0 (OGL)](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/), which permits free use, copying, and redistribution provided the source is acknowledged. Source: Office for National Statistics, licensed under the Open Government Licence v3.0.

## Author

**Petula Law**

**Institution:** Aarhus University

**Course:** Digital Archives and Methods

**Contact:** au8146368@uni.au.dk

## License

This project is submitted for academic assessment purposes.
