# Assignment 4: Machine Learning Model Application & Evaluation

**Course:** Introduction to Data Science
**Name:** Areeb Fatima | **Roll No:** SU92-BCSFM-F26-039

## Problem
Predict the selling price of houses in Melbourne (a **regression** problem).

## Dataset
Melbourne Housing Snapshot (Kaggle): https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot
The cleaned file `cleaned_melbourne_housing.csv` is included in this repository.

## Models Compared
| Model | MAE | RMSE | R² (Test) | R² (Train) |
|---|---|---|---|---|
| Linear Regression | 251,814 | 371,768 | 0.640 | 0.624 |
| Decision Tree | 231,493 | 398,983 | 0.586 | 1.000 |
| Random Forest | 168,051 | 290,988 | 0.780 | 0.971 |

## Result
**Random Forest** performed best (MAE about $168,000, R² = 0.78). The Decision Tree overfits
(train R² 1.000 vs test 0.586) and Linear Regression underfits.

## Files
- `assignment4-ml-areebfatima.ipynb`: full notebook with code, outputs and conclusion
- `cleaned_melbourne_housing.csv`: cleaned dataset
