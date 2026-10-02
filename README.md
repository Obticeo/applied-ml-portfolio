# Applied Machine Learning & Deep Learning Portfolio

This repository is a recruiter-friendly portfolio of production-oriented machine learning and deep learning projects spanning tabular regression, churn prediction, NLP, and audio classification. Each project demonstrates end-to-end workflow execution from data cleaning and feature engineering to model benchmarking, evaluation, and deployment-minded architecture.

## Portfolio Overview

The portfolio highlights work across four core problem areas:

- Tabular regression with ensemble modeling and log-target normalization
- End-to-end classification pipelines with leak-free preprocessing and stacking
- Multi-class NLP using hybrid TF-IDF and text-robust modeling techniques
- Deep learning for noisy audio classification using spectrogram transformers and CRNN architectures

## Project Summary

| Project | Domain | Focus | Result |
| :--- | :--- | :--- | :--- |
| 01. Real Estate Price Regression | Tabular Regression | Weighted ensemble of Ridge + LightGBM + CatBoost | Validation RMSE: 0.3105 |
| 02. Hotel Booking Churn Prediction | Tabular Classification | Leak-free pipelines, temporal feature engineering, stacking | Strong production-style classification workflow |
| 03. NLP Sentiment Analysis | Multi-class NLP | Hybrid TF-IDF + linear models + stacking | ~65% macro accuracy |
| 04. Imbalanced Comment Classification | Multiclass NLP | Sparse high-dimensional text + metadata, stratified CV | Robust minority-class handling |
| 05. Audio Genre Classification | Deep Learning / Audio | CRNN, ResNet-18, AST, noisy mashup augmentation | ~0.94-0.97 macro F1 |

## Project Repositories

- `tabular-housing-price-regression`
- `hotel-cancellation-prediction-pipeline`
- `nlp-sentiment-hybrid-tfidf-stacking`
- `imbalanced-comment-classification-nlp`
- `audio-spectrogram-transformer-mashup-classifier`

## Why This Portfolio Matters

This portfolio is designed to show that I can:

- build reliable, reproducible ML pipelines using real-world data constraints
- evaluate multiple models with proper validation strategies
- engineer domain-aware features and handle skewed or imbalanced data
- design modular systems that are production-minded rather than notebook-only
- work across classical ML and modern deep learning stacks

## Core Skill Areas

### Classical Machine Learning
- Feature engineering and transformation
- Pipelines and leakage prevention
- Cross-validation and model benchmarking
- Ensembling, bagging, and stacking
- Handling missing data, skewness, and imbalance

### Deep Learning and Audio
- Log-Mel spectrogram pipelines
- Transfer learning with pretrained audio models
- CRNN and transformer-based architectures
- Noisy audio augmentation and robustness training
- Experiment tracking with Weights & Biases and PyTorch Lightning

### NLP and Text Analytics
- Word and character n-gram vectorization
- TF-IDF with sparse matrix pipelines
- Class imbalance handling and calibration
- Multi-class classification evaluation with macro metrics
- Feature importance and text diagnostics

## Tech Stack

### Core
- Python
- NumPy
- Pandas
- Scipy
- Scikit-learn

### Gradient Boosting and Structured Data
- LightGBM
- CatBoost
- XGBoost
- SHAP / explainability workflows where applicable

### Deep Learning
- PyTorch
- PyTorch Lightning
- Torchaudio
- Librosa
- Hugging Face Transformers
- Timm

### NLP
- Scikit-learn vectorizers
- Sparse matrices and feature unions
- Hyperparameter tuning with GridSearchCV / RandomizedSearchCV

### Experiment Tracking
- Weights & Biases (W&B)
- KaggleHub
- MLflow-style workflow discipline

## Recommended Recruiter Narrative

This portfolio demonstrates end-to-end applied ML capability across tabular, text, and audio domains. The work emphasizes not only model accuracy, but also practical engineering concerns such as data leakage prevention, imbalanced-class handling, robust feature design, and deep learning workflows that generalize to noisy or complex real-world inputs.

## Portfolio Structure

```text
applied-ml-portfolio/
├── README.md
├── projects/
│   ├── 01-tabular-housing-price-regression/
│   │   └── README.md
│   ├── 02-hotel-cancellation-prediction-pipeline/
│   │   └── README.md
│   ├── 03-nlp-sentiment-hybrid-tfidf-stacking/
│   │   └── README.md
│   ├── 04-imbalanced-comment-classification-nlp/
│   │   └── README.md
│   └── 05-audio-spectrogram-transformer-mashup-classifier/
│       └── README.md
└── LICENSE
```

## Next Steps

This repository can be extended with:

- architecture diagrams
- notebook links and experiments
- GitHub badges and project screenshots
- deployment demos or Streamlit apps
- a portfolio landing page using GitHub Pages

## Contact

Open to opportunities in machine learning engineering, applied AI, and data-driven product development.

---

Built as a unified portfolio for showcasing applied ML and deep learning work across multiple domains.
