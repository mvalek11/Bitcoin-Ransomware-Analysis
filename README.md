# Bitcoin Ransomware Transaction Analysis

## Overview
Machine learning analysis of Bitcoin transactions to classify ransomware activity using the BitcoinHeist dataset. This project implements multiple ML models to detect patterns indicative of ransomware money laundering through comprehensive feature engineering and hyperparameter tuning.

## Key Results
- 88% Accuracy with tuned XGBoost model
- Income identified as most important feature (0.29 importance score)
- Successfully handled class imbalance (93% legitimate transactions)
- Comprehensive analysis including EDA, multiple models, and feature importance

## Project Structure
Bitcoin-Ransomware-Analysis/
├── notebooks/
│ └── cis_5450_final_project.py
├── data/
│ └── dataset_info.md
├── requirements.txt
└── README.md
