# 📊 Customer Churn Prediction & Dashboard

## 📌 Project Overview

This project predicts customer churn for a telecommunications company using machine learning (Python in Google Colab) and visualizes insights through Tableau dashboards. The goal is to help businesses identify at-risk customers and improve retention strategies by combining predictive modeling with interactive business intelligence.

---

## 🔗 Live Dashboard

[*Open the Live Tableau Dashboard →*](https://public.tableau.com/views/TelcoCustomerChurnAnalysisSQLColabMLTableau/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

[![Live Tableau Dashboard – Click to Open](https://public.tableau.com/views/TelcoCustomerChurnAnalysisSQLColabMLTableau/Dashboard2.png)](https://public.tableau.com/views/TelcoCustomerChurnAnalysisSQLColabMLTableau/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

> If the image preview doesn’t load (Tableau Public sometimes blocks hotlinking), use the *Open* link above.

---

## 🚀 Key Steps

### 1. Data Preparation (Google Colab)

* Cleaned telco dataset (tenure, monthly charges, total charges, contract type, etc.).
* Engineered new features (Tenure Buckets, Churn Flag, Churn Rate %).
* Built ML models to predict churn probability.
* Exported outputs:

  * churn_prediction.csv → customer churn probability results.
  * feature_importance_top20.csv → top 20 drivers of churn.

### 2. Tableau Dashboard

* Imported cleaned dataset + ML outputs.
* Created KPIs: Churn Rate %, Total Customers, Avg. Monthly Charges.
* Built calculated fields: Churn Flag, Tenure Buckets, Predicted Class.
* Added interactive filters: Contract, Internet Service, Payment Method, Senior Citizen.
* Implemented parameterized Probability Threshold for flexible classification.
* Designed intuitive dashboards for executives to track churn trends.

---

## 📊 Deliverables

* Machine Learning Output: CSV files with predictions & feature importance.
* Tableau Dashboard: Visual insights by tenure, contract type, charges, and customer segments.
* KPIs & Filters: Business-friendly indicators for decision-making.

---

## 🛠 Tech Stack

* Python (Google Colab): Data preprocessing, model training, predictions.
* Pandas, Scikit-learn: Data wrangling & ML.
* Tableau: Interactive dashboards & visualization.

---

## 🎯 Outcomes

* Identified top churn drivers (e.g., contract type, tenure, monthly charges).
* Highlighted high-risk customers using model predictions.
* Delivered a data-driven decision support system for customer retention.

---

## 📌 Usage Instructions

1. Open Tableau → Connect Data → Load telco_clean.csv, churn_prediction.csv, and feature_importance_top20.csv.
2. Create calculated fields & filters (Contract, Internet Service, Payment Method, Senior Citizen).
3. Build dashboards with KPIs and apply filters.
4. Use parameterized Probability Threshold to adjust churn classification.
5. Explore churn insights to support retention strategies.

---

✨ This project bridges Machine Learning + Business Intelligence, helping organizations move from predictions to actionable insights.
