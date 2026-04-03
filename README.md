📊 Credit Card Fraud Detection Dashboard

 View Tableau Dashboard https://public.tableau.com/app/profile/palak.5572/viz/Creditcardfraud_17752262897350/Dashboard1?publish=yes

🚀 Project Overview

This project presents an end-to-end data analytics pipeline for detecting and analyzing fraudulent credit card transactions using Python, Excel/Google Sheets, and Tableau.

The objective is to uncover hidden fraud patterns, understand transaction behavior, and build an interactive dashboard that supports data-driven decision-making in fraud prevention.

Credit card fraud is a major financial challenge globally, requiring efficient data analysis and visualization to identify suspicious activities and reduce risk.

🛠️ Tech Stack
Python (Colab) → Data Cleaning & Feature Engineering
Pandas, NumPy → Data Processing
Google Sheets / Excel → Data Preparation
Tableau → Dashboard & Visualization
🔄 Project Workflow
1️⃣ Data Collection
Dataset sourced from Kaggle (credit card transactions)
2️⃣ Data Cleaning (Python)
Removed irrelevant columns
Handled data types
Created new features:
hour (time-based analysis)
age & age_group
distance (customer vs merchant)
3️⃣ Exploratory Data Analysis (EDA)
Analyzed fraud distribution
Checked feature importance
Identified weak vs strong predictors
4️⃣ Data Preparation (Excel / Sheets)
Renamed columns
Created:
fraud_label (Fraud / Normal)
Removed unnecessary columns
Prepared dataset for visualization
5️⃣ Dashboard Creation (Tableau)
Built interactive dashboard with:
KPIs
Charts
Filters
Map visualization
📊 Key Dashboard Features
🔹 KPI Cards
Total Transactions
Fraud Rate (%)
Most Affected City
Most Affected Age Group
🔹 Visualizations
Fraud vs Non-Fraud Distribution
Fraud by Transaction Category
Fraud by Hour of Day
Fraud by Age Group
Geographical Fraud Analysis (Map)
🔹 Interactivity
Filters (City, Category, Gender, Amount)
Clickable charts for dynamic exploration
🔍 Key Insights
📉 1. Fraud is Highly Imbalanced
Fraud cases represent a very small percentage of total transactions
Indicates real-world class imbalance problem
⏰ 2. Time-Based Fraud Patterns
Fraud activity varies across hours
Certain time windows show higher fraud risk
Similar studies show fraud often peaks during low-surveillance hours like early morning
💰 3. Transaction Amount Matters
High-value transactions tend to have higher fraud probability
Indicates risk increases with transaction size
🛒 4. Category-Based Risk
Some transaction categories show higher fraud concentration
Helps identify high-risk merchant types
🌍 5. Location Insights
Certain cities show higher fraud activity
Useful for identifying fraud hotspots
👥 6. Demographic Patterns
Specific age groups are more affected
Helps understand user vulnerability patterns
📏 7. Distance is NOT a Strong Indicator
Customer vs merchant distance showed minimal difference between fraud and non-fraud
Indicates fraud detection requires multi-feature analysis, not a single variable
💡 Business Impact

This dashboard helps:

🏦 Banks → Identify high-risk transactions
🔐 Security Teams → Monitor fraud patterns
📊 Analysts → Explore trends interactively

It enables faster decision-making and improves fraud detection strategies.

🧠 Key Learnings
Handling imbalanced datasets
Importance of feature validation
Building interactive dashboards
Translating data into business insights
🔮 Future Improvements
Add Machine Learning model (Fraud Prediction)
Real-time fraud detection system
Advanced anomaly detection
Integration with live transaction streams
📌 Conclusion

This project demonstrates how combining data cleaning, analysis, and visualization can effectively uncover fraud patterns and support smarter financial decisions.

It highlights that fraud detection is a multi-dimensional problem, requiring a combination of behavioral, transactional, and temporal features.

🙌 Author

Palak
Aspiring Data Analyst | Data Science Enthusiast 🚀
