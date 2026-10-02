# 02. Hotel Booking Churn Prediction

## Project Repository
`hotel-cancellation-prediction-pipeline`

## Objective
Build a production-ready binary classification system to predict hotel booking cancellations using booking metadata, pricing signals, customer behavior patterns, and temporal features.

## Key Contributions
- Engineered domain features such as total nights, party size, price-per-night, and lead time signals
- Built leak-free preprocessing using scikit-learn Pipeline and ColumnTransformer
- Compared multiple classification models including KNN, Random Forest, XGBoost, and LightGBM
- Implemented stacking architecture with a diverse set of base learners

## Technical Stack
- Python
- Scikit-learn
- XGBoost
- LightGBM
- Pandas
- NumPy

## Main Results
- Robust, leak-safe classification workflow suitable for production-style deployment
- Competitive performance across accuracy, F1-score, and confusion matrix evaluation

## Key Learnings
- Feature invariance matters: legitimate business outliers should not be removed prematurely
- Pipeline integrity prevents leakage across cross-validation folds and hidden test sets

## Recruiter-Friendly Summary
This project showcases practical classification modeling, disciplined preprocessing, and production-oriented design patterns in structured data workflows.
