Credit Card Fraud Detection 
**Tabaleu Dashboard**
https://public.tableau.com/app/profile/palak.5572/viz/Creditcardfraud_17752262897350/Dashboard1?publish=yes

<img width="1512" height="982" alt="Screenshot 2026-03-31 at 8 04 37 PM" src="https://github.com/user-attachments/assets/705a0200-7de1-418e-9c15-edab73d7a061" />


**Overview**

This project presents an end-to-end data analytics solution for detecting and analyzing fraudulent credit card transactions. It combines data preprocessing, exploratory analysis, and interactive visualization to uncover fraud patterns and support decision-making.

**Objectives**

Identify hidden fraud patterns
Analyze transaction behavior
Build an interactive dashboard for fraud monitoring

**Tech Stack**

Python (Colab): Data cleaning and feature engineering
Pandas, NumPy: Data manipulation
Excel / Google Sheets: Data preparation
Tableau: Data visualization and dashboard development

**Workflow**

1. Data Collection
Dataset sourced from Kaggle
2. Data Cleaning & Feature Engineering
Removed irrelevant columns and handled data inconsistencies
Created new features: hour, age, age group, and distance
3. Exploratory Data Analysis
Analyzed fraud distribution and class imbalance
Evaluated feature importance
Identified key fraud indicators
4. Data Preparation
Created fraud labels (Fraud / Normal)
Structured dataset for visualization
5. Dashboard Development
Built an interactive Tableau dashboard with:
KPIs (Total Transactions, Fraud Rate, etc.)
Time-based and category-based analysis
Geographical fraud visualization
Dynamic filters for user interaction

**Key Insights**

Fraud cases are highly imbalanced
Fraud risk varies by time of day
High-value transactions have higher fraud probability
Certain transaction categories are more vulnerable
Specific locations show higher fraud concentration
Distance is not a strong standalone predictor

**Business Value**

Helps financial institutions detect high-risk transactions
Enables security teams to monitor fraud patterns
Supports analysts with interactive data exploration
Future Enhancements
Machine learning-based fraud prediction model
Real-time fraud detection system
Advanced anomaly detection techniques
Integration with live transaction data

**Conclusion**

This project demonstrates the importance of combining data analysis and visualization to solve real-world fraud detection problems. It highlights the need for multi-dimensional analysis using behavioral and transactional features.
