# Spam Detection - ML Classification Project

## Overview
A machine learning project that detects spam SMS messages using 
two classification algorithms — Naive Bayes and Logistic Regression.

## Dataset
- Source: UCI ML Repository - SMS Spam Collection
- Total Messages: 5,572
- Classes: Ham (86.6%) and Spam (13.4%)

## Tech Stack
- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- TF-IDF Vectorization

## Model Results
| Model               | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Naive Bayes         | 98.48%   | 99.25%    | 89.26% | 93.99%   |
| Logistic Regression | 97.85%   | 100.00%   | 83.89% | 91.24%   |

## Conclusion
Naive Bayes outperforms Logistic Regression for this task
based on F1 Score and Recall — meaning it catches more spam
while keeping false alarms near zero.

## How to Run
1. Open the .ipynb file in Google Colab or Jupyter Notebook
2. Run all cells in order
3. Results and charts generate automatically

## Internship
Built as Task 1 of the AI Internship at InternSpark.
