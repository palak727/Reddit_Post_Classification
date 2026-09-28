# Reddit Post Moderation Classification using NLP and Machine Learning

## Overview

This project analyzes Reddit posts and predicts whether a post is likely to be removed by moderators using Natural Language Processing (NLP) and Machine Learning techniques.

The workflow includes exploratory data analysis, feature engineering, text preprocessing, TF-IDF vectorization, class imbalance handling, model training, and model interpretation.

---

## Dataset

The dataset consists of Reddit posts containing:

- Post title
- Score
- Number of comments
- Original Content (OC) status
- NSFW status
- Moderation outcome

Target Variable:

- 0 → Not Removed
- 1 → Removed

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- NLTK
- SMOTE (Imbalanced-Learn)

---

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. Text Preprocessing
5. TF-IDF Vectorization
6. Class Imbalance Handling (SMOTE)
7. Random Forest Classification
8. Feature Importance Analysis
9. TruncatedSVD Visualization

---

## Model Performance

| Metric | Score |
|----------|----------|
| Accuracy | 91.01% |
| Precision | 60.67% |
| Recall | 51.22% |
| F1 Score | 55.44% |

---

## Key Findings

- Community engagement strongly influences moderation outcomes.
- Original Content (OC) posts have significantly lower removal rates.
- Score and comment count are the most important metadata features.
- TF-IDF features capture meaningful moderation-related patterns.
- TruncatedSVD preserved approximately 97.8% of variance while reducing dimensionality.

---
