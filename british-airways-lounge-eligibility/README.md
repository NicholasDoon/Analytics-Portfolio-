# British Airways Lounge Eligibility Analysis

## Business Question
This project analyzes passenger characteristics to predict eligibility for British Airways airport lounges. The goal is to evaluate tradeoffs between correctly identifying eligible passengers and minimizing incorrect lounge access decisions.

## Data Description
The dataset contains passenger-level information such as ticket class, frequent flyer status, and route characteristics, along with labels indicating lounge eligibility.

## Methods Used
- Data cleaning and preprocessing  
- Exploratory data analysis  
- Logistic regression classification  
- Model evaluation using recall, precision, and ROC-AUC  

## Key Findings
The model prioritizes recall for eligible passengers, reducing the likelihood of incorrectly denying lounge access at the cost of increased false positives.

## Evaluation
Accuracy alone was insufficient due to class imbalance. Model performance was evaluated using recall and ROC-AUC to better reflect operational tradeoffs.

## Limitations
This analysis is based on historical data and does not account for real-time operational constraints. Results are not causal and may not generalize beyond the dataset.

## Tools Used
- Python (pandas, scikit-learn, matplotlib)

## Files
british-airways-lounge-eligibility/Predicting Consumer Buying Behavior Modelling.ipynb
