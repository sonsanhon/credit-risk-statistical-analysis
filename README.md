# Statistical Analysis of Credit Risk Data

## Overview
This project performs an exploratory and statistical analysis on credit risk data from LendingClub.
The goal is to analyze distributions, relationships between categorical and quantitative variables,
and validate statistical assumptions used in risk modeling.

## Dataset
- Source: LendingClub Credit Risk Dataset (Kaggle)
- Main file: loan.csv (~440 MB)
- Dataset is not included in this repository due to GitHub size limits

📌 Dataset link:
https://www.kaggle.com/datasets/jorgealvaredo/lending-club-loan-data

## Analysis Performed
- Descriptive statistics
- Histograms and KDE
- Boxplots by categorical variables
- Crosstab analysis (categorical vs categorical)
- Statistical relationship analysis
- Normality tests:
  - Shapiro-Wilk
  - Kolmogorov-Smirnov
  - Anderson-Darling
  - D’Agostino-Pearson
  - Lilliefors

## Project Structure
credit-risk-statistical-analysis/
│
├── README.md
└── notebooks/
└── credit_risk_analysis.ipynb


## Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn
- scipy, statsmodels

## How to Run
1. Download the dataset from Kaggle
2. Place `loan.csv` locally (path explained in notebook)
3. Open `notebooks/credit_risk_analysis.ipynb`
4. Run all cells

## Author
Aristophane Bah
