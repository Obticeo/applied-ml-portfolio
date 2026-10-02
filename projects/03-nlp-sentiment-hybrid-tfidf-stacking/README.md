# 03. NLP Sentiment Analysis via Hybrid N-Gram Ensembles

## Project Repository
`nlp-sentiment-hybrid-tfidf-stacking`

## Objective
Design a multi-class sentiment classifier for short text reviews using hybrid vectorization and ensemble modeling.

## Key Contributions
- Combined word n-grams and character n-grams via TF-IDF feature unions
- Examined review length and class imbalance to tune vectorizer parameters
- Evaluated logistic regression, linear SVM, Naive Bayes, and SGD variants
- Applied cross-validation and stacking to improve generalization

## Technical Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- NLP feature engineering

## Main Results
- Achieved approximately 65% macro accuracy across sentiment classes
- Increased robustness to short-text noise and misspellings through character-level embeddings at the feature level

## Key Learnings
- Character n-grams improve performance when handling short, noisy, or misspelled text
- Complement Naive Bayes helps when class imbalance is present in text classification tasks

## Recruiter-Friendly Summary
This project reflects strong NLP competence, robust feature design, and methodical model selection for real-world text classification tasks.
