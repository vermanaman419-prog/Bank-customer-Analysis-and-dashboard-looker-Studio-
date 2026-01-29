# 📊 Bank Transactions Analytics Dashboard (Looker Studio)

An end-to-end **data analytics project** showcasing data cleaning, transformation, and interactive dashboarding using **Python (Pandas)** and **Google Looker Studio**. This project analyzes banking transaction data to uncover customer behavior, transaction trends, and operational insights.

---

## 🚀 Project Overview

The goal of this project is to:

* Clean and standardize raw banking transaction data
* Engineer meaningful features for time-based and customer analysis
* Build a professional, interactive **Looker Studio dashboard** with KPIs and visual insights
* Present results in a business-ready format

---

## 🧰 Tech Stack

* **Python**: Pandas, NumPy
* **Data Cleaning & Feature Engineering**: Jupyter / Google Colab
* **Visualization & Dashboarding**: Google Looker Studio
* **Data Source**: CSV (cleaned and standardized)

---

## 🧹 Data Cleaning & Preparation

Key data issues addressed:

* ✅ Standardized `transaction_time` from numeric formats (e.g. `143207`) to `HH:MM:SS`
* ✅ Handled invalid and missing time values safely
* ✅ Extracted `transaction_hour` for hourly trend analysis
* ✅ Filled missing `customer_age` values using rounded mean imputation
* ✅ Normalized messy `location` values (e.g. addresses → city names)
* ✅ Parsed text-based dates into proper `Date` fields for time-series analysis

The final cleaned dataset is analysis-ready and dashboard-compatible.

---

## 📈 Dashboard Features

### 🔑 KPIs (Top Section)

* Total Transactions
* Total Transaction Value
* Average Transaction Value
* Active Customers
* Average Customer Age
* Peak Transaction Hour
* High Value Transaction Percentage

### 📊 Visualizations

* Transaction Value Trend Over Time (Time Series)
* Transactions by Hour of Day (Column Chart)
* Top Cities by Transaction Value
* Average Transaction Value by City
* Transaction Amount Distribution (Histogram)
* High vs Low Value Transactions (Pie Chart)
* Transactions by Gender (Donut Chart)
* Customer Age Distribution

### 🎛️ Interactive Filters

* Date Range Filter
* City Filter
* Gender Filter

---

## 🧠 Key Insights

* Identified peak transaction hours and high-activity periods
* Discovered top-performing cities by transaction value
* Analyzed customer demographics and spending patterns
* Highlighted proportion of high-value transactions

---

## 📂 Repository Structure

```
├── data/
│   └── bank_transactions_final_clean.csv
├── notebooks/
│   └── data_cleaning_and_feature_engineering.ipynb
├── dashboard/
│   └── Looker_Studio_Dashboard_Link.txt
├── README.md
```

---

## 🔗 Dashboard Link

👉 *(https://lookerstudio.google.com/reporting/4cb312cb-857a-4f84-8807-316b8a4808d7)*

---


## 🏁 Conclusion

This project demonstrates strong fundamentals in:

* Data cleaning and transformation
* Exploratory data analysis
* Business-focused dashboard design
* Communicating insights through visuals


