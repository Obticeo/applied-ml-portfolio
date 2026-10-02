# 01. Real Estate Price Regression

## Project Repository
`tabular-housing-price-regression`

## Objective
Develop an end-to-end regression pipeline to predict real estate prices from multi-modal tabular data containing continuous physical measurements, geographic information, and categorical property attributes.

## Key Contributions
- Handled missing numerical values with imputation and feature distribution normalization
- Applied log transforms to target and skewed feature variables
- Used one-hot encoding with train/test schema alignment
- Benchmarked Ridge regression, LightGBM, and CatBoost
- Built a weighted ensemble blending linear and boosting models

## Technical Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- CatBoost

## Main Results
- Weighted blend configuration: 0.2 Ridge + 0.4 LightGBM + 0.4 CatBoost
- Validation log-RMSE: 0.3105

## Key Learnings
- Log-transforming right-skewed price targets improves model stability and reduces outlier dominance
- Combining linear and nonlinear models captures complementary signals in tabular data

## Recruiter-Friendly Summary
This project demonstrates strong tabular ML capability, feature engineering discipline, and ensemble modeling for real-world regression tasks.
