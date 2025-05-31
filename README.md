# Fraud Detection System

A Python-based system to detect credit card fraud using machine learning.

## Features
- Preprocessing with SMOTE
- Random Forest training
- Evaluation with precision, recall, F1-score
- CLI interface for testing

## How to Use
1. Run the script: `python fraud_detection_system.py`
2. Enter 30 comma-separated values for a transaction
3. Get fraud prediction

## How the Fraud Detection System Works (for beginners):

   It learns from past transactions — which ones were normal and which were fraud.

- Every transaction has 30 numbers (like secret clues).

- The system is trained using these clues to understand fraud patterns.

- When you enter a new transaction (30 numbers), it checks:

-"Does this look like the fraud cases I learned?"

- If it looks normal → It says Legitimate.

- If it matches fraud patterns → It says Fraudulent

## Dataset
Uses the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
