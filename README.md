# Statistical Analysis of Credit Risk Data

## Overview
This project performs an exploratory and statistical analysis on credit risk data from LendingClub.
The objective is to analyze distributions, categorical vs quantitative relationships, and validate statistical assumptions.

## Dataset
- Source: LendingClub Credit Risk Dataset
- Main file used: loan.csv (~440 MB)
- Dataset not included due to GitHub size limits

## Analysis
- Descriptive statistics
- Histograms and KDE
- Boxplots by categorical variables
- Crosstab analysis
- Normality tests:
  - Shapiro-Wilk
  - Kolmogorov-Smirnov
  - Anderson-Darling
  - D’Agostino-Pearson
  - Lilliefors

## Tools
- Python
- pandas, numpy
- matplotlib, seaborn
- scipy, statsmodels

## Author
Aristophane Bah

Dataset not included due to GitHub size limits.

You can download the dataset here:
https://www.kaggle.com/datasets/jorge-salas/credit-risk-dataset

After downloading, extract the file and use:
loan.csv

## How to Load the Data

1. Download the dataset from Kaggle:
   https://www.kaggle.com/datasets/jorge-salas/credit-risk-dataset

2. Extract `loan.csv`

3. Create a local folder called `data/`

4. Place `loan.csv` inside the `data/` folder

5. In the notebook, load the data using:

```python
import pandas as pd

df = pd.read_csv("data/loan.csv")
