# COVID-19 Impact Analysis on Different Age Groups in Florida

## Project Overview

This data visualization project investigates the impact of COVID-19 and related illnesses on mortality rates across various age groups and locations within the state of Florida. Our goal was to explore relationships between age, gender, illness severity, and place of death to understand patterns of COVID-19-related mortality from 2020 to 2023.

### Team Members
- Anubha Jain
- Sri Mahalakshmi Pendyala
- Vansh Pathria
- Vedaswaroop Dasagrandhi
- Lochan Kunkalaguntla

## Executive Summary

The project aimed to provide insights into how COVID-19 and associated infections affected mortality rates among different age groups, with a particular focus on the elderly and the role of gender and illness severity. By analyzing data from [DATA.CDC.GOV](https://data.cdc.gov), we sought to identify patterns and propose targeted interventions.

## Data Description

- **Source**: [CDC COVID-19 Deaths by Place of Death and Age](https://data.cdc.gov/NCHS/Provisional-COVID-19-Deaths-by-Place-of-Death-and-/4va6-ph5s), [CDC COVID-19 Deaths by Sex and Age](https://data.cdc.gov/NCHS/Provisional-COVID-19-Deaths-by-Sex-and-Age/9bhg-hcku)
- **Scope**: COVID-19 deaths, total deaths, and deaths from other respiratory illnesses in Florida.
- **Structure**: Dataset contains 123,930 rows and 15 columns, detailing deaths by age group and place of death.

## Data Cleaning Process

Outlined the R programming techniques used for data cleaning, including missing value imputation and data frame preparation for analysis.

## Insights and Findings

### Key Hypotheses Tested
1. **Age and COVID-19 Vulnerability**: Higher mortality rates in individuals aged 74-85 due to weakened immune systems and age-related health issues.
2. **Seasonal Pattern of Influenza Mortality**: Influenza mortality follows a seasonal pattern, unaffected by COVID-19 peaks.
3. **Place of Death**: A significant percentage of COVID-19 and pneumonia-related fatalities occurred in inpatient healthcare settings.
4. **Gender Disparity**: Males exhibited higher mortality rates from pneumonia and influenza during the pandemic.
5. **COVID-19 and Pneumonia Link**: While COVID-19 contributed to pneumonia cases, not all pneumonia fatalities were directly COVID-19 related.

## Conclusions

The project highlights the nuanced impact of COVID-19 on mortality across different demographics and settings in Florida. Our findings underscore the importance of targeted public health interventions to mitigate the pandemic's effects on vulnerable populations.

## How to Use This Repository

### Folder Structure
- `/data`: Contains raw and cleaned datasets used in the analysis.
- `/scripts`: R scripts for data cleaning and analysis.
- `/visuals`: Data visualizations and charts generated from the analysis.

### Running the Analysis
1. Ensure you have R and the necessary libraries installed.
2. Clone the repository and navigate to the `/scripts` directory.
3. Run the data cleaning and analysis scripts in sequence.

## Contributions

We welcome contributions to improve the analysis or extend the study to other regions. Please see the [CONTRIBUTING.md](./CONTRIBUTING.md) file for guidelines on how to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE.md) file for details.
