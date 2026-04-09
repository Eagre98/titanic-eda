# Titanic Survival — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## What this project is
Analysis of 891 Titanic passengers to find what factors
determined survival. Built as my first data science project
using real historical data.

## Key findings
- Overall survival rate: **38.4%**
- Women survived at **74.2%** vs men at **18.9%** — nearly 4x difference
- 1st class survival: **63%** vs 3rd class: **24%**
- Fare and passenger class both correlate with survival
- Children under 10 had relatively higher survival rates

## What I learned
- Loading and exploring real datasets with Pandas
- Cleaning missing data (177 missing Age values fixed with median)
- Creating statistical visualizations with Matplotlib and Seaborn
- Finding and interpreting patterns in data

## Tools used
| Tool | Purpose |
|------|---------|
| Python | Main language |
| Pandas | Data loading and cleaning |
| Matplotlib | Basic charts |
| Seaborn | Statistical visualizations |
| Google Colab | Development environment |

## Dataset
Kaggle Titanic Competition — 891 passengers, 12 columns.
[View dataset](https://www.kaggle.com/competitions/titanic/data)

## How to run
1. Open `titanic-eda.ipynb` in Google Colab
2. Upload `train.csv` from Kaggle
3. Run all cells in order
