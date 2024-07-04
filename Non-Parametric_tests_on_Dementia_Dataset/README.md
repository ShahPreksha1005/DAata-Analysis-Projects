# Dementia Data Exploration using Non-Parametric Methods

## Overview
This project aims to explore and analyze a dementia dataset using various non-parametric statistical methods. The goal is to gain insights into the factors associated with dementia and understand the relationships and differences between different groups within the data. The analysis includes a thorough exploratory data analysis (EDA) and the application of non-parametric tests to derive meaningful conclusions.

## Project Structure
The repository contains the following files:
- `Non_Parametric_Tests_on_Dementia_Dataset.ipynb`: The main Jupyter Notebook containing the detailed analysis.
- `README.md`: This file providing a high-level overview of the project.
- `dementia_dataset.csv`: The dataset used for the analysis (if permissible to include, otherwise include instructions on how to obtain the dataset).

## Table of Contents
1. Introduction and Problem Statement
2. Importing Libraries and Dataset
3. Exploratory Data Analysis (EDA)
   3.1 Univariate Analysis
   3.2 Bivariate Analysis
4. Non-Parametric Methods
   4.1 Spearman Rank Correlation
   4.2 Mann-Whitney U Test
   4.3 Why not Wilcoxon Signed-Rank Test and Friedman Test?
5. Key Insights 
6. Key Achievements
7. Conclusion
8. Future Work
9. References

## Introduction and Problem Statement
This project explores a dementia dataset to understand the patterns and factors associated with dementia. By using non-parametric methods, the analysis aims to uncover relationships and differences between various groups within the dataset. The insights gained could contribute to better understanding and managing dementia.

## Dataset
The dataset used in this project contains various attributes related to subjects and their MRI scans. Key attributes include:
- Subject ID, MRI ID
- Group (demented, non-demented, converted)
- Visit number, MR delay
- Demographic details (age, gender, handedness, education, socioeconomic status)
- Cognitive assessments (MMSE, CDR)
- MRI measurements (eTIV, nWBV, ASF)

## Exploratory Data Analysis (EDA)
The EDA section involves both univariate and bivariate analyses:
- **Univariate Analysis**: Distribution and frequency of individual variables using histograms, count plots, and box plots.
- **Bivariate Analysis**: Relationships between pairs of variables using scatter plots, pair plots, and correlation matrices.

## Non-Parametric Methods
This section applies various non-parametric statistical methods to the data:
- **Spearman Rank Correlation**: Assessing monotonic relationships between numerical variables.
- **Mann-Whitney U Test**: Comparing distributions across different groups.
- **Wilcoxon Signed-Rank Test**: Comparing paired samples (if applicable).
- **Friedman Test**: Comparing multiple paired samples (if applicable).

## Key Achievements
- Thorough exploration of the dementia dataset using statistical and visualization techniques.
- Application of non-parametric methods to derive meaningful insights.
- Identification of significant relationships and differences between groups.

## Future Work
- Further analysis on additional variables and their interactions.
- Implementation of machine learning models to predict dementia stages.
- Exploration of time-series analysis for longitudinal data.