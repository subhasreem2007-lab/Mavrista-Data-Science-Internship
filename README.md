# Mavrista Data Science Internship

This repository contains projects completed during my Data Science Internship at Mavrista Technologies.

## Task 1: Retail Sales Data Cleaning and Exploration

- Cleaned and explored retail sales data.
- Checked missing values and duplicate records.
- Performed summary statistics and sales analysis.
- Created visualizations to understand sales trends.
- Detected outliers using the IQR method.
- Exported the cleaned dataset.

## Tools Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Files
- `sales_data.csv` – Original dataset
- `Retail_Sales_Cleaned.csv` – Cleaned dataset
- `Task_1_Retail_Sales_Data_Cleaning.ipynb` – Python notebook

More internship tasks will be added to this repository.

## Task 2: Marketing Campaign Performance Analysis

### Objective
To analyze marketing campaign performance and identify the most effective campaigns, channels, and target audiences using data analysis.

### Activities Performed
- Collected and loaded the marketing campaign dataset.
- Cleaned the dataset and handled missing values and duplicates.
- Calculated Click-Through Rate (CTR).
- Estimated conversions and cost per conversion.
- Analyzed campaign ROI and estimated revenue.
- Compared performance across campaign types, marketing channels, and target audiences.
- Performed statistical analysis to compare channel performance.
- Created visualizations to understand campaign performance.
- Provided recommendations for improving marketing strategies.

### Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Google Colab

### Deliverables
- Jupyter Notebook containing the analysis.
- Cleaned marketing campaign dataset.
- Campaign, channel, audience, and monthly performance reports.

### Note
The dataset contains estimated performance metrics. Estimated conversions and revenue are calculated from the available dataset columns and should not be treated as actual business results.

### Task 3: A/B Test Analysis for Product Feature Rollout

**Objective:** To analyze the performance of a new product feature by comparing control and treatment groups.

**Activities Performed:**
- Loaded and cleaned A/B testing dataset.
- Compared conversion rates between control and treatment groups.
- Performed a two-proportion Z-test.
- Calculated p-value, 95% confidence interval and effect size.
- Analyzed session duration using Welch's t-test.
- Created visualizations for comparison.
- Provided a product rollout recommendation.

**Key Results:**
- Control Conversion Rate: 9.86%
- Treatment Conversion Rate: 11.18%
- Absolute Lift: 1.32 percentage points
- P-value: 0.031463
- Final Recommendation: SHIP IT

**Deliverables:** Jupyter Notebook, Cleaned Dataset and Summary Report.

*Note: Analysis performed using a synthetic practice dataset.*

## Task 4: Customer Lifetime Value (CLV) & Cohort Analysis

### Objective
To analyze customer purchasing behavior, measure customer retention, and calculate Customer Lifetime Value (CLV) using SQL and Python.

### Activities Performed
- Loaded and cleaned the online retail dataset.
- Created a SQLite database.
- Extracted transaction data using SQL queries.
- Identified customer cohorts based on their first purchase month.
- Created a cohort retention table.
- Visualized customer retention using a heatmap.
- Calculated customer-level and average cohort CLV.
- Identified best and worst performing cohorts.
- Created retention curves and CLV visualizations.

### Tools and Technologies
- Python
- Pandas
- SQLite
- SQL
- Matplotlib
- Seaborn
- Google Colab

### Deliverables
- Jupyter Notebook
- Cohort Retention Report
- Customer CLV Reports
- Cohort Heatmap
- Retention Curves
- CLV Chart
- SQLite Database

### Note
The first purchase month is used as a proxy for the customer cohort month. CLV represents historical customer revenue during the available dataset period, not a future revenue prediction.

### Task 5: Predictive Demand Modeling with Feature Engineering

**Objective:**
To develop a machine learning model that predicts product demand using historical sales data and helps improve inventory and procurement planning.

**Dataset:**
Online Retail Dataset – Kaggle

**Activities Performed:**
- Cleaned and preprocessed the retail sales dataset.
- Selected a high-volume product for demand prediction.
- Aggregated sales quantity into daily demand.
- Created features such as day, month, day of the week, and weekend indicators.
- Generated lag features and rolling-average features.
- Trained and compared Linear Regression and Random Forest models.
- Used chronological train-test splitting for time-aware validation.
- Evaluated model performance using MAE and RMSE.
- Analyzed feature importance.
- Generated a 7-day demand forecast.
- Prepared procurement recommendations based on predicted demand.

**Tools and Technologies:**
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

**Deliverables:**
- `Task_5_Predictive_Demand_Modeling.ipynb`
- `Task_5_Analysis_Reports.zip`

**Outcome:**
Developed a predictive demand modeling workflow to estimate future product demand, compare machine learning models, understand important demand patterns, and support inventory planning decisions.

**Note:** The selected dataset does not contain actual holiday or promotion information. The model focuses on one high-volume product and uses historical sales-based features.

### Task 6: End-to-End Business Insights & Anomaly Detection System

**Objective:**

To develop an end-to-end business analytics system that combines data cleaning, business metric tracking, historical trend analysis, and statistical anomaly detection to identify unusual business activities.

**Dataset:**

Online Retail Dataset – Kaggle

**Activities Performed:**

- Cleaned and preprocessed the retail sales dataset.
- Removed duplicate records, missing values, cancelled transactions, and invalid sales entries.
- Calculated important business metrics such as total revenue, quantity sold, orders, and unique customers.
- Analyzed daily revenue and weekly sales patterns.
- Applied Z-score-based anomaly detection.
- Used the IQR method to identify unusual revenue values.
- Compared daily revenue with historical weekday patterns.
- Identified unusual business activities using statistical thresholds.
- Analyzed product and country-wise sales performance.
- Generated business insights, charts, and recommendations.

**Anomaly Detection Methods:**

- Z-Score Method (Threshold: ±3)
- Interquartile Range (IQR) Method (1.5 × IQR)
- Historical Weekday Pattern Analysis

**Tools and Technologies:**

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn

**Deliverables:**

- `Task_6_End_to_End_Business_Insights.ipynb`
- `Task_6_Analysis_Reports.zip`

**Outcome:**

Developed an end-to-end business insights system that monitors sales performance, detects unusual revenue activities, analyzes historical patterns, and provides data-driven recommendations for better business decision-making.

**Note:** Statistical anomalies indicate unusual activity and do not automatically represent errors or fraud. The dataset does not contain actual conversion, churn, holiday, or promotion information.
