# Canonical Analysis: Community Welfare & Water Access 💧🏘️

This project examines the relationship between **community welfare** indicators (such as education, life expectancy, and poverty rates) and **household water access and sanitation** indicators using **Canonical Correlation Analysis (CCA)**. The analysis is based on data from Indonesian provinces, aiming to uncover how sanitation and water access impact community well-being.

### Key Focus:
- **Manual Computation of CCA**: While modern statistical software offers automated methods for CCA, this project manually computes the Canonical Correlation Analysis from first principles. This approach highlights the fundamental workings of the analysis and offers deeper insights into the statistical relationships.

## Introduction

In many developing countries, access to clean water and proper sanitation is closely tied to community welfare, affecting education, health, and economic outcomes. This project focuses on analyzing these relationships in the context of Indonesia using **Canonical Correlation Analysis (CCA)**, a multivariate statistical method that uncovers the relationships between two sets of variables.

### Objectives:
- To understand how **sanitation and water access** correlate with **community welfare** indicators across Indonesian provinces.
- To manually compute **Canonical Correlation Analysis (CCA)** for deeper statistical understanding.

The dataset used in this project comes from Badan Pusat Statistika Indonesia (BPS) for the year 2023 and includes indicators like handwashing facilities, access to safe drinking water, educational attainment, life expectancy, and poverty rates.
## Usage

The **manual-CCA.Rmd** file contains all the steps for manually calculating Canonical Correlation Analysis.

1. Open **manual-CCA.Rmd** in RStudio.
2. Execute the code cells step by step to see how CCA is computed manually.
3. Adjust the parameters or datasets to explore different relationships between variables.

## Project Results

The analysis reveals a strong relationship between **community welfare** and **household water access** indicators. Here are some key findings:

- **Higher educational attainment** and **lower poverty rates** are positively associated with better access to sanitation and clean water.
- The first canonical correlation was significant at **0.870**, suggesting a strong link between sanitation practices and improved community welfare.
- Further canonical variates showed no significant correlations, indicating that the first pair of canonical variates captured most of the shared variance.

For a more detailed breakdown of the results, refer to the **R Markdown** file or the .pdf file.
