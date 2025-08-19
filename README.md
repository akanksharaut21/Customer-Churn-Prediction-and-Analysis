Customer Churn Prediction & Dashboard 📊
📌 Project Overview

This project focuses on predicting customer churn for a telecommunications dataset and visualizing key insights through Tableau dashboards. The workflow integrates machine learning (Python in Google Colab) with business intelligence (Tableau) to provide actionable insights for retention strategies.

🚀 Key Steps

Data Preparation (Colab)

Cleaned telco dataset (tenure, monthly charges, total charges, contract type, etc.).

Engineered new features (Tenure Buckets, Churn Flag, Churn Rate %).

Trained machine learning models to predict churn probability.

Exported churn probability results & top 20 feature importance as CSVs.

Tableau Dashboard

Imported cleaned dataset and model results.

Created KPIs: Churn Rate %, Total Customers, Avg. Monthly Charges.

Built calculated fields: Churn Flag, Tenure Buckets, Predicted Class.

Designed interactive dashboards with filters (Contract, Internet Service, Payment Method, Senior Citizen).

Added parameterized Probability Threshold for flexible churn classification.

📊 Deliverables

ML Model Output: CSV with churn predictions & top features.

Tableau Dashboard: Visual insights on churn by tenure, contract type, charges, and customer segments.

KPIs & Filters: Business-friendly indicators for decision-making.

🛠️ Tech Stack

Python (Google Colab): Data preprocessing, churn prediction, feature importance.

Pandas, Scikit-learn: Data wrangling & model building.

Tableau: Interactive dashboard creation & visualization.

🎯 Outcomes

Identified top drivers of churn (e.g., contract type, tenure, monthly charges).

Enabled businesses to track high-risk customers with dynamic thresholds.

Provided a data-driven decision support system for customer retention.

📌 Usage

Open customers_clean.csv, churn_prediction.csv, and feature_importance_top20.csv in Tableau.

Load calculated fields and create visualizations.

Explore dashboards to analyze churn trends & retention strategies.

✨ This project bridges Machine Learning + Business Intelligence, helping organizations move from predictions to actionable insights.

