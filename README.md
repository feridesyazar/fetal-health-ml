# 🩺 Fetal Health Classification

### Machine Learning | Supervised Learning | Multiclass Classification

## Project Overview

This beginner-friendly project uses cardiotocography (CTG) measurements to classify fetal health as **Normal, Suspect, or Pathological**.

The goal is to practice a simple Machine Learning workflow, from data exploration to model evaluation. This project is for **educational purposes only**, not medical diagnosis.

## Dataset

- **Source:** [Fetal Health Classification – Kaggle](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
- **Original source:** [UCI Cardiotocography](https://archive.ics.uci.edu/dataset/193/cardiotocography)
- **Original dataset:** 2,126 records, 21 input features, 1 target variable
- **Data Cleaning:** 13 exact duplicate rows removed
- **Final dataset:** 2,113 records

## Project Workflow

1. Exploratory Data Analysis (EDA)
2. Data Cleaning
3. Train-Test Split (80/20)
4. Model Training – Gaussian Naive Bayes & Decision Tree
5. Model Evaluation – Accuracy, Precision, Recall, F1-score
6. Confusion Matrix & Feature Importance

## Model Results

| Model | Accuracy | Macro F1 |
|---|---:|---:|
| Gaussian Naive Bayes | 79.7% | 0.670 |
| Decision Tree | **92.4%** | **0.877** |

The **Decision Tree** performed better on this test set. However, class-specific metrics are important because the dataset is imbalanced.

## Tools & Libraries

Python · Pandas · Matplotlib · Seaborn · Scikit-learn · Jupyter Notebook


## Limitations & Future Improvements

The dataset does not contain patient identifiers. Therefore, we cannot confirm whether identical measurements belong to the same patients. Exact duplicate rows were removed to reduce potential evaluation bias.

Future improvements could include cross-validation and additional models such as Random Forest.
