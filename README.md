Credit Card Fraud Detection 

**Tabeau Dashboard**
https://public.tableau.com/app/profile/palak.5572/viz/Creditcardfraud_17752262897350/Dashboard1?publish=yes

<img width="1512" height="982" alt="credit_fraud_dashboard" src="https://github.com/user-attachments/assets/9b142bfe-49ec-4be8-b9e4-fe70b866ec0f" />



**Overview**

Designed a real-time fraud detection and revenue protection system to identify suspicious financial transactions, minimize false positives, and simulate decision-making for fraud prevention teams.

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

**Data Dictionary**

| Column Name               | Data Type         | Description                                                              |
| ------------------------- | ----------------- | ------------------------------------------------------------------------ |
| **trans_date_trans_time** | Object (Datetime) | Timestamp of the transaction (date and time when transaction occurred).  |
| **merchant**              | Object            | Name of the merchant where the transaction was made.                     |
| **category**              | Object            | Category of the transaction (e.g., grocery, shopping, travel).           |
| **amt**                   | Float             | Transaction amount (in USD or given currency).                           |
| **gender**                | Object            | Gender of the cardholder (Male/Female).                                  |
| **city**                  | Object            | City where the transaction occurred.                                     |
| **state**                 | Object            | State where the transaction occurred.                                    |
| **zip**                   | Integer           | ZIP code of the transaction location.                                    |
| **lat**                   | Float             | Latitude of the cardholder’s location.                                   |
| **long**                  | Float             | Longitude of the cardholder’s location.                                  |
| **city_pop**              | Integer           | Population of the city where the cardholder resides.                     |
| **job**                   | Object            | Occupation of the cardholder.                                            |
| **dob**                   | Object (Date)     | Date of birth of the cardholder.                                         |
| **unix_time**             | Integer           | Unix timestamp of the transaction (seconds since epoch).                 |
| **merch_lat**             | Float             | Latitude of the merchant’s location.                                     |
| **merch_long**            | Float             | Longitude of the merchant’s location.                                    |
| **is_fraud**              | Integer (0/1)     | Fraud indicator: 0 = Legitimate Transaction, 1 = Fraudulent Transaction. |


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
