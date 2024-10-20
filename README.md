# Comprehensive Analysis of Cancer Incidence and Contributing Factors Across the United States

This project provides an in-depth data analysis of cancer incidence rates across different states in the United States. By examining various socioeconomic factors and population trends, we aim to identify patterns and insights that can help guide healthcare resource allocation and cancer prevention programs.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Analysis Questions](#analysis-questions)
- [Key Findings](#key-findings)
- [Methodology](#methodology)
- [Usage](#usage)
- [Results](#results)
- [Contributors](#contributors)

## Project Overview

Cancer remains a significant public health concern in the U.S. This project aims to understand how various factors such as income, poverty levels, healthcare studies, and population size are associated with cancer incidence rates. We conduct several statistical analyses, including regression analysis, correlation analysis, and ANOVA, to examine relationships between cancer rates and contributing factors across states.

## Data Sources

The dataset used for this project includes:
- State-wise cancer incidence rates
- Median income levels
- Poverty percentage
- Population estimates
- Study counts (representing healthcare research or case studies)
- Five-year trend data for cancer incidence and death rates

## Analysis Questions

1. Which regions in the U.S. have the highest cancer incidence rates?
2. Does the stability or decline in cancer trends affect current cancer rates?
3. Does the number of health studies or monitoring initiatives in an area impact cancer rates?
4. How does median income relate to cancer incidence rates?
5. What factors (income, poverty, population size, etc.) correlate most strongly with cancer rates?

## Key Findings

1. **Regional Differences**: Southern states such as Kentucky, Alabama, and Louisiana show higher cancer incidence rates, suggesting a greater need for cancer-related healthcare resources in these areas.
   
2. **Stability in Cancer Trends**: Areas with stable cancer rates still exhibit high cancer incidence, indicating the need for continuous healthcare resources and preventive efforts.

3. **Study Count Impact**: Areas with a higher number of health studies show slightly elevated cancer rates, suggesting that while monitoring is important, further measures may be needed to address underlying health concerns.

4. **Income and Cancer**: While median income shows a slight positive correlation with cancer rates, the relationship is weak, suggesting other factors might contribute more to cancer risk.

5. **Correlation Findings**: The strongest correlation is observed between cancer incidence rates and cancer death rates, indicating that areas with more cancer cases also experience worse outcomes.

## Methodology

- **Descriptive Statistics**: To analyze regional cancer incidence and compare them across states.
- **Two-Sample T-Tests**: Conducted to determine whether stable vs. declining cancer trends and high vs. low study count groups show significant differences in cancer rates.
- **ANOVA**: Used to assess how median income levels affect cancer incidence rates across income categories.
- **Correlation Analysis**: Examined the relationships between cancer rates and factors such as poverty percentage, income, and population size.
- **Regression Analysis**: Built models to explore how factors such as income, poverty, study count, and five-year trends influence cancer rates.


## Usage

1. To explore the data and run the statistical analyses, navigate to the main Jupyter notebook or Python file.

2. Modify the inputs, such as state selection or income grouping, to test other hypotheses.

3. The final output will include plots, tables, and statistical results that offer insights into how various factors impact cancer incidence rates across the U.S.

## Results

### Key Visualizations:
- **State-wise Cancer Incidence Distribution**: Visual representation of cancer rates by state.
- **ANOVA Income Groups**: Box plots and statistical tests show how income levels impact cancer rates.
- **Correlation Matrix**: Shows the relationships between various factors, highlighting the strongest connections with cancer rates.
- **Regression Model Residuals**: Visualization of model fit and predictive accuracy.

The project's findings underscore that while factors like income and poverty show some association with cancer rates, the strongest predictor remains the cancer death rate, pointing toward broader systemic healthcare issues in areas with high cancer incidence.

## Contributors

- **Parth Chaudhari** 

