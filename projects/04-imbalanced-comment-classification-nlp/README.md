# 04. Imbalanced Comment Classification

## Project Repository
`imbalanced-comment-classification-nlp`

## Objective
Build a large-scale multi-class classification pipeline for comment data with severe class imbalance and mixed structured metadata.

## Key Contributions
- Audited class distribution and evaluated metadata feature predictive power
- Performed text analytics including length distribution and word cloud diagnostics
- Used GPU-accelerated classification workflows and sparse matrix concatenation
- Implemented stratified cross-validation to preserve minority representation

## Technical Stack
- Python
- cuML / RAPIDS acceleration
- SciPy
- Scikit-learn
- Sparse matrices
- NLP preprocessing pipelines

## Main Results
- Demonstrated methods for robust minority-class modeling in large imbalanced datasets
- Maintained computational efficiency through sparse matrix design and strategic feature assembly

## Key Learnings
- Stratified validation is essential when rare classes must retain representational integrity
- Sparse matrix concatenation prevents memory bottlenecks in high-dimensional NLP tasks

## Recruiter-Friendly Summary
This project highlights the ability to handle large-scale, imbalanced text datasets while balancing model performance with computational practicality.
