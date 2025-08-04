
# Relationship between Previous International Collaboration and International Mobility of Researchers

This repository provides data, R scripts, and figures for analyzing the relationship between prior international collaboration and subsequent international mobility of researchers, focusing on country, region, and income group patterns.

---

## Repository Structure

.
section 1/
├── n of researchers--first year.csv
├── mobility rate--country--2023--more than 500.csv
├── Fig QSS1--first year--researchers_2023.png
├── Fig QSS2--visualization.png
├── Fig QSS3--mobility ratio--country level 2019.png
├── Fig QSS4--Top15.png
├── Fig QSS5--mobility rate_2023.png
├── Fig QSS--A1--world map--CMR_o--2023.png
├── Fig QSS--A2--mobility rate--region and income.png
└── section 1-prior international collaboration and international mobility.R

section 2/
├── mobility ratio--origin and destination from--more than 100--1990-2019_2023.csv
├── Gini index.xcel
├── Fig QSS--A3--mobility and collaboration--chord diagram between regions.png
├── Fig QSS--A4--mobility and collaboration--chord diagram between income.png
├── Fig QSS7--mobility rate--origin and detinaiton.png
├── Fig QSS8--countries--mobility rate--origin and detinaiton_2023.png
├── Fig QSS10--mobility rate_2023.png
└── section 2-prior international collaboration and international mobility.R

README.md

---

## Contents

### Section 1

**Data Files**

- `n of researchers--first year.csv`  
  Number of researchers by first publication year.

- `mobility rate--country--2023--more than 500.csv`  
  Researcher mobility rates by country of origin (countries with >500 researchers).

**Figures**

- `Fig QSS1--first year--researchers_2023.png`  
  Number of researchers by first year of publication.

- `Fig QSS2--visualization.png`  
  Visualization of general mobility and collaboration.

- `Fig QSS3--mobility ratio--country level 2019.png`  
  Scatterplot: mobility rates for researchers with/without prior collaboration.

- `Fig QSS4--Top15.png`  
  Bar plot comparing mobility rates among the top 15 countries.

- `Fig QSS5--mobility rate_2023.png`  
  Combined figure for region and income group analysis.

- `Fig QSS--A1--world map--CMR_o--2023.png`  
  World map of Collaboration Mobility Ratio (CMR_o) by country.

- `Fig QSS--A2--mobility rate--region and income.png`  
  Heatmap of mean CMR_o by region and income group.

**Script**

- `section 1-prior international collaboration and international mobility.R`  
  R script for data processing, analysis, and visualization for Section 1.

---

### Section 2

**Data Files**

- `mobility ratio--origin and destination from--more than 100--1990-2019_2023.csv`  
  Researcher mobility rates by origin and destination country pairs.

- `Gini index.xcel`  
  Gini index results for mobility/collaboration flow inequality.

**Figures**

- `Fig QSS--A3--mobility and collaboration--chord diagram between regions.png`  
  Chord diagrams showing mobility and collaboration flows between global regions.

- `Fig QSS--A4--mobility and collaboration--chord diagram between income.png`  
  Chord diagrams showing flows between income groups.

- `Fig QSS7--mobility rate--origin and detinaiton.png`  
  Scatterplot of country pair-level mobility rates.

- `Fig QSS8--countries--mobility rate--origin and detinaiton_2023.png`  
  Heatmap of mobility ratios between the top 15 countries.

- `Fig QSS10--mobility rate_2023.png`  
  Combined plots for income group analyses.

**Script**

- `section 2-prior international collaboration and international mobility.R`  
  R script for all data processing and visualization in Section 2.

---

## How to Reproduce the Results

1. **Install R and required packages:**

   ```r
    install.packages(c("tidyverse", "ggplot2", "circlize", "ineq", "scales", "ggrepel", "gridExtra"))
    ```

2. Run the scripts in section 1 and section 2 to reproduce all analyses and figures.

---   
    
## Notes
All analyses are based on bibliometric data and custom R scripts.

Figures illustrate patterns of international mobility and collaboration across different scales (country, region, income group), as well as network and inequality features (Gini index, chord diagrams).

Please refer to the individual R scripts for detailed analysis steps and comments.

## License
For academic or research use only. Please contact the author for collaboration, feedback, or reuse requests.

