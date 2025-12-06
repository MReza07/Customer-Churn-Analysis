## 📊 Customer Churn Analytics Dashboard (Power BI)


## 🚀 Project Overview

Customer churn is a critical KPI for subscription-based businesses. This analysis examines churn behavior through demographic attributes, contract types, service usage, billing details, and tenure.
The dashboard helps decision-makers detect churn-prone segments and design data-driven retention strategies.

## 📌 Key Insights (At a Glance)

Overall Churn Rate: 26.54% (1,869 churned out of 7,043 customers)

Churn is significantly higher among:

Customers with paperless billing

Month-to-month contract holders

Users with fiber optic internet

Customers with less than 1 year of subscription (31.04%)

Partner & dependent status shows distinct churn behavior across segments.

## 📁 Dataset Overview

Demographics

Billing & Payment Method

Contract Type

Tenure & Subscription Duration

Internet & Phone Service Usage

Support Tickets

Charges (Monthly & Total)

Churn Status (Yes/No)

👉 Download Dataset https://github.com/MReza07/Customer-Churn-Analysis/tree/main/dataset

## 📘 Data Dictionary

Column Name	Description

CustomerID	Unique customer identifier

Tenure	Number of months customer stayed

MonthlyCharges	Monthly subscription fees

TotalCharges	Total payment till date

Contract	Type of contract (1, 12, 24 months)

Churn	Whether customer left (Yes/No)

🛠️ Tools & Technologies

Power BI – Data modeling & dashboard development

Power Query – Data cleaning & transformation

DAX – KPI calculations

Excel/CSV – Raw dataset storage

## 📂 Project Structure

│── Dataset/

│   └── Customer Churn-Dataset.xlsx
│
│── PBIX/

│   └── Churn Analytics.pbix
│
│── Dashboard Overview/

│   ├── Customer Churn Analysis.JPG

│   ├── Churned Customer by Gender.PNG

│   ├── Churned Customer by PaymentMethod.PNG

│   ├── Churned Customer by Contract.PNG

│   └── Churned by Tenure.PNG
│
└── README.md

🧭 Project Workflow

Data Collection

Data Cleaning & Transformation (Power Query)

Exploratory Data Analysis

Data Modeling & DAX Calculations

Dashboard Design & Visualization

Insights & Business Recommendations

📈 Main KPIs Measured

Total Customers

Churned Customers

Churn Rate (%)

Tenure Distribution

Monthly / Yearly Charges

Service Usage Metrics

📊 Dashboard Features

✔ Gender, Contract, Payment Method, Tenure slicers

✔ Highly interactive visual exploration

✔ Donut charts, KPIs, bar charts & summary tables

✔ Churn segmentation by:

Gender

Senior Citizenship

Partner & Dependent Status

Contract Type

Payment Method

Internet Service Type

Subscription Tenure

## 📐 Sample DAX Measures

Admin Tickets =
CALCULATE(COUNTROWS('Churn-Dataset'), 'Churn-Dataset'[numTechTickets] = "Admin")

Total Customer =
COUNTROWS('Churn-Dataset')

Churn Citizen% =
DIVIDE([Churned Senior Citizens], [Churned Customers], 0)

Churn% =
DIVIDE([Churned Customers], [Total Customer])

Total Charge =
CALCULATE(SUM('Churn-Dataset'[TotalCharges]), 'Churn-Dataset'[Churn] = "Yes")

Churn Rate =
DIVIDE([Churned Customers], [Total Customers])

## 🎯 Business Value

Identify at-risk customers early

Understand churn motivations

Optimize retention strategies

Improve service offerings

Support data-driven decision-making

## 📂 How to Open the Report

To explore the Power BI dashboard:

1. Download the PBIX File

Open the Churn Analytics.pbix file in the PBIX/ folder

Click Download raw

2. Open in Power BI Desktop

Install Microsoft Power BI Desktop (free)

Open the downloaded .pbix file

3. View Dataset (Optional)

Download the dataset from the Dataset/ folder

## 📜 License

This project is released under the MIT License.

## 📬 Contact

Md. Rezaul Repon

Data Analyst (Power BI | SQL | Python)

🔗 GitHub: https://github.com/MReza07

📧 Email: reazulrepon@gmail.com
