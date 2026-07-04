# 🏠 House Price Prediction

## Overview
This project predicts house prices in California using Machine Learning models.

## Dataset
- **California Housing Dataset** (built-in from scikit-learn)
- 20,640 houses
- 8 features

## Models Used
| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | 0.6295 | 0.6867 |
| Random Forest | 0.4806 | 0.8173 |
| XGBoost | 0.3819 | 0.8468 |

## Best Model
**XGBoost** with R² Score of **0.8468** 🏆

## Steps
1. Data Loading
2. EDA (Exploratory Data Analysis)
3. Data Cleaning (Outliers + Cap Removal)
4. Feature Engineering
5. Feature Scaling
6. Model Training
7. Evaluation

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Results
- Best RMSE: **0.3819** (~$38,000 average error)
- Best R² Score: **0.8468** (84% accuracy)