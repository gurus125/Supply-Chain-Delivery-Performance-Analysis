# Supply Chain Delivery Performance Analysis

## Overview

This project analyzes the delivery performance of a global e-commerce supply chain to identify operational bottlenecks, understand the financial impact of delays, and build a predictive model for late deliveries.

The analysis covers over **172,000 customer orders** across multiple regions and product categories. Using data analytics and machine learning techniques, the project uncovers key drivers of delivery delays and provides actionable recommendations to improve operational efficiency.

---

## Business Problem

Late deliveries negatively impact customer satisfaction, operational performance, and profitability.

Key questions addressed:

* What percentage of orders are delivered late?
* Which regions, shipping modes, and departments contribute most to delays?
* What is the financial impact of delayed deliveries?
* Can we predict high-risk orders before they become late?

---

## Dataset

**Source:** DataCo Global Supply Chain Dataset

**Records Analyzed:** 172,765 Orders

### Features Included

* Order Information
* Customer Information
* Product Categories
* Shipping Details
* Delivery Status
* Profit Metrics
* Geographic Data

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning & Preparation

* Handled missing values
* Removed inconsistencies
* Created delay-related metrics
* Engineered business KPIs

### 2. Exploratory Data Analysis (EDA)

* Delivery performance analysis
* Profitability assessment
* Delay distribution analysis
* Regional performance comparison
* Department-wise analysis
* Shipping mode evaluation

### 3. Root Cause Analysis

Identified major factors driving delivery delays:

* Shipping Mode
* Payment Processing Status
* Product Department
* Geographic Region
* Customer Segment

### 4. Machine Learning

Built a classification model to predict whether an order will be delivered late.

#### Model Used

* Random Forest Classifier

#### Handling Class Imbalance

* SMOTE Oversampling

#### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score

---

## Key Findings

### Delivery Performance

* Total Orders: **172,765**
* Late Deliveries: **94,523**
* Late Delivery Rate: **54.71%**
* On-Time Delivery Rate: **45.29%**

### Financial Impact

* Total Profit: **$7.5 Million**
* Profit at Risk from Delayed Orders: **$2.1 Million**

### Operational Insights

* First Class Shipping showed the highest delay rate.
* Payment review processes contributed significantly to delays.
* Delay patterns were consistent across most customer segments.
* Certain departments experienced noticeably higher delay percentages.

---

## Machine Learning Results

| Metric                  | Value |
| ----------------------- | ----- |
| Accuracy                | 74%   |
| Precision (Late Orders) | 78%   |
| Recall (Late Orders)    | 75%   |
| F1 Score                | 74%   |

The model successfully identifies high-risk orders and can be used as an early-warning system for supply chain operations.

---

## Business Recommendations

1. Audit First Class and Second Class shipping operations.
2. Deploy predictive alert systems for high-risk orders.
3. Improve payment review workflows.
4. Create seasonal logistics capacity plans.
5. Optimize shipping mode assignment logic.
6. Monitor high-delay departments and regions.

---

## Project Structure

```text
├── data/
│   ├── DataCoSupplyChainDataset.csv
│
├── notebooks/
│   ├── Supply Chain Analysis.ipynb
│
├── reports/
│   ├── Supply_Chain_Performance_Report.pdf
│
├── README.md
```

---

## Future Improvements

* Hyperparameter tuning
* XGBoost and LightGBM comparison
* Real-time delay prediction dashboard
* Power BI integration
* Feature importance and SHAP analysis

---

## Author

Gurpreet Singh

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning
