# Sarcasm Detection using Machine Learning

## Overview
This project builds a text classification model to detect sarcasm in news headlines using Natural Language Processing (NLP).

The model classifies text as either:
- Sarcasm
- Not Sarcasm

---

## Dataset
The dataset contains news headlines labeled as sarcastic or not sarcastic.

- Input: headline text
- Output: sarcasm label (0 or 1)

---

## Workflow

### 1. Data Preprocessing
- Loaded JSON dataset
- Mapped labels to readable format
- Extracted headline text as input feature

### 2. Feature Extraction
- Applied Bag of Words using CountVectorizer

### 3. Model Training
- Split data into training and testing sets (80/20)
- Trained Bernoulli Naive Bayes model

### 4. Prediction
- Tested model on custom sentences
- Classified text as sarcasm or not sarcasm

---

## Model Used
- Bernoulli Naive Bayes

---

## Evaluation
- Accuracy score on test data

---

## Example Predictions
- "Cows lose their job as milk prices drop." → Sarcasm
- "Stranger Things as the most viewed series in America." → Not Sarcasm

---

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn

---

## Author
Arwaa Mamdoh
