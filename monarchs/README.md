# Monarchs Assignment
This is the monarchs portfolio assignment for Aarhus University's Digital Archives and Methods course which explores the reign durations of the last 50 British monarchs.


## Overview
This contains a tidy datset of the last 50 British monarchs, alongisde the associated R script.


## Features
- **Monarchs.csv** - clean CSV file containing monarch names, reign start/end years and dates, and birth/death dates
- **Monarchs.rmd** - R Markdown file with data cleaning, reign duration calculations, and visaulisation
- **Monarchs.html** - knitted HTML report generated and ready to view in a browser


## Repository Structure
``` r
monarchs
├── data
│ ├── Monarchs.csv
│ ├── Monarchs.Rmd
│ └── Monarchs.html
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
cd au814638_law_petula/monarchs/data
```


Install the required package:
```r
install.packages("tidyverse")
```


### Usage

1. Make sure Monarchs.csv is located in a data/ subfolder relative to the .rmd file
2. Open the monarchs.rmd in RSudio
3. Knit the document to HTML


## Author

**Petula Law**

**Institution:** Aarhus University

**Course:** Digital Archives and Methods

**Contact:** petulalaw@gmail.com

## License

This project is submitted for academic assessment purposes.
