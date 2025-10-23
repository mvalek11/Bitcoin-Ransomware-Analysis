```markdown
# Bitcoin Ransomware Transaction Analysis

## Overview
Machine learning analysis of Bitcoin transactions to classify ransomware activity using the BitcoinHeist dataset.

## Results
- 88% accuracy with tuned XGBoost model
- Income identified as most important feature
- Successfully handled class imbalance (93% legitimate transactions)

## Installation
```bash
git clone https://github.com/yourusername/Bitcoin-Ransomware-Analysis.git
cd Bitcoin-Ransomware-Analysis
pip install -r requirements.txt
python cis_5450_final_project.py
```

## Dataset
BitcoinHeist Ransomware Dataset from Kaggle - 2.9M+ transactions with features including length, weight, count, looped, neighbors, and income.

## Models
- XGBoost: 88% accuracy
- k-Nearest Neighbors: 81% accuracy  
- K-Means Clustering: Unsupervised analysis

## Key Findings
Income (transaction value) was the strongest predictor of ransomware activity, followed by looped transactions and transaction length.

## Technologies
Python, pandas, scikit-learn, XGBoost, TensorFlow, matplotlib, seaborn

## Academic Context
Completed as part of CIS 5450 - Big Data Analytics at the University of Pennsylvania.
```
