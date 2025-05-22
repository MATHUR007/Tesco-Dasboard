# Tesco Customer Churn Analysis Dashboard (Power BI)

This Power BI dashboard provides a comprehensive analysis of customer churn behavior for Tesco using a publicly available dataset. The goal is to help stakeholders understand churn patterns, identify critical risk segments, and uncover actionable insights to enhance customer retention strategies.

## 📊 Dashboard Features

- **KPIs**:
  - Median of Monthly Charges by Churn
  - Sum of Total Charges by Churn
  - Average Tenure by Contract Type

- **Visualizations**:
  - **Bar Chart**: Count of churn by payment method
  - **Pie Chart**: Count of senior citizens by phone service usage
  - **Waterfall Chart**: Count of churn segmented by Streaming TV access

## 📁 Dataset

- **Source**: Sample dataset from Kaggle
- **Dataset Name**: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn?resource=download)
- **Format**: CSV
- **Fields Used**: `gender`, `SeniorCitizen`, `Partner`, `PaymentMethod`, `PhoneService`, `StreamingTV`, `Contract`, `MonthlyCharges`, `TotalCharges`, `Churn`, and `tenure`

## 🎯 Key Insights

- Electronic check users show the highest churn rate.
- Senior citizens mostly use phone services but have lower representation in churn.
- Customers with streaming TV show a significant trend in retention or churn variations.

## 💻 Tools Used

- Power BI (Desktop)
- Data Cleaning with Power Query
- DAX for KPI calculations

## 📦 How to Use

1. Download the `.pbix` file from the repository.
2. Open it in Power BI Desktop.
3. Load the CSV data if required.
4. Explore visualizations and filters for insights.

---

