# Digital Archives & Methods

This Github repository contains two projects from Aarhus University's Digital Archives and Methods (Summer 2026) course.

## Overview

Two projects were completed as part of this course:
1. **Monarchs** - an analysis of reign durations of the last 50 British monarchs
2. **Dementia and Alzheimer's Morality** - a final project exploring dementia and Alzheimer's disease mortality statistics in the UK

Both projects aim to produce a reproducible workflow in R, using the 'tidyverse' package for data cleaning and 'ggplot2' for visualisation.


## Repository Structure
``` r
au814638_law_petula
├── monarchs
├── data
│ ├── Monarchs.csv
│ ├── Monarchs.Rmd
│ └── Monarchs.html
└── README.md
├── final_project
│ ├── data
│ │ ├── dementia_deaths.csv
│ │ ├── dementia_deaths_by_sex_2019.csv
│ │ ├── dementia_deaths_by_age_sex_2019.csv
│ │ └── dementia_deaths_by_region_cause_2019.csv
│ │ └── dementia_diagnoses.csv
└── README.md
└── Final_project.Rmd

```


## Projects

### 1. Monarchs
This explores the reigning duration of the last 50 British monarchs
- Loads and cleans reign start/end dates
- Calculates each monarch's reign duration in years, and in days for the three longest-reigning monarchs
- Calculates the average reign duration and identifies monarchs who reigned longer than average
- Visualises reign duration over time with a scatterplot and smoothed trend lime

### 2. Dementia and Alzheimer's mortality rates

Looks at trends in dementia and Alzheimer's disease mortality in England and Wales using Office for National Statistics (ONS) and NHS England Digital data.

- Plots the number of registered deaths between 2001 and 2019
- Compares 2019 deaths by sex, and by age group and sex
- Compares age-standardised mortality rates by region, with 95% confidence intervals
- Plots the number of dementia diagnoses recorded in GP practices in England under primary care, October 2022 - March 2026



### Prerequisites
- Install R(>=4.2) and RStudio
- Required R package: "tidyverse"


### Installation
Clone the repository:

```bash
git clone https://github.com/Digital-Methods-HASS/au814638_law_petula.git
```

Install the required package:

```r
install.packages("tidyverse")
```


### How to use
Each project is inside its own folder and can be ran independently.

### Data Sources
- **Monarchs** — dataset of British monarchs' reign dates, compiled for the Digital Archives and Methods course.
- **Dementia and Alzheimer's Mortality** — Office for National Statistics (ONS) registered deaths and age-standardised mortality rates for dementia and Alzheimer's disease in England and Wales and NHS England Digital prevalence rates for dementia and Alzheimer's disease in the UK.

## Data License

The ONS data used in the dementia and Alzheimer's mortality project is made available under the [Open Government Licence v3.0 (OGL)](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/), which permits free use, copying, and redistribution provided the source is acknowledged. Source: Office for National Statistics, licensed under the Open Government Licence v3.0.

The NHS England Digital data is also made available under the Open Government Licence v3.0 (OGL). Source: NHS England Digital, Primary Care Dementia Data, licensed under the Open Government Licence v3.0.

The R code, analysis, and figures in this repository are the original work of the author, covered separately by the License section below.

## Author
**Petula Law**

**Institution:** Aarhus University

**Course:** Digital Archives and Methods

**Contact**: au8146368@uni.au.dk

## License

This project is submitted for academic assessment purposes.
