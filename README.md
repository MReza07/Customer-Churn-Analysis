## 📊 Customer Churn Analytics Dashboard (Power BI)

![License](https://img.shields.io/badge/License-MIT-blue)
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-orange)



“This Customer Churn Analysis project identifies churn drivers using Power BI, providing insights into customer retention patterns and risk indicators. The dashboard highlights churn trends by demographics, subscription type, and customer activity.

## 📷 Dashboard Preview

<a href="https://github.com/MReza07/Customer-Churn-Analysis/tree/main/dashboard%20Overview">View Dashboard<a/>

## Project Summary

| Section             | Summary                          |
| ------------------- | -------------------------------- |
| **Dashboard**       | Customer Churn Analysis          |
| **Tools**           | Power BI, Power Query, DAX       |
| **Key KPIs**        | Churn %, Monthly Charges, Tenure |
| **Business Output** | Identify customer churn drivers  |


## 🚀 Project Overview

Customer churn is one of the most important KPIs for subscription-based businesses. This Power BI dashboard analyzes churn patterns by demographic attributes, subscription tenure, service usage, payment method, and account information. It enables decision-makers to detect high-risk segments and optimize retention strategies.

## 📌 Key Insights (At a Glance)

Churn Rate: 26.54% with 1,869 customers churned out of 7,043 total customers.

Higher churn among:

Customers with paperless billing

Month-to-month contracts

Internet users with fiber optic service

Subscription time under 1 year has the highest churn (31.04%).

Partner & dependent status shows differing churn behavior across segments.

## 📁 Dataset Overview

The dataset includes customer-level information such as:

Customer Demographics

Payment Method & Billing Information

Contract Type

Subscription Duration

Internet & Phone Service Usage

Support Tickets

Monthly & Yearly Charges

Churn Indicator (Yes/No)

## Dataset

<a href="https://github.com/MReza07/Customer-Churn-Analysis/tree/main/dataset">Download Dataset<a/>

## Data dictionary

![Uploading image.png…]()



## 🛠️ Tools & Technologies

Power BI – Data modeling, DAX calculations, and dashboard creation

Power Query – Data cleaning & transformation

Excel / CSV – Raw dataset

DAX Measures – For KPI calculations

## 📁 Project Structure
│── Dataset/

│     └── Customer Churn-Dataset.xlsx

│── PBIX/
│     └── Churn analytics.pbix

│── Dashboard Overview/

      └── Customer Churn Analysis.JPG

│     └── Churned Customer by Gender.PNG

      └── Churned Customer by Paymentmethod.PNG
       
      └── Churned Customer by contract.PNG
     └──  Churned by Tunure.PNG

│── README.md

## Project Workflow

Data Collection

Data Cleaning (handling blanks, data types, transformations)

Exploratory Analysis

Power BI Modeling (DAX, relationships)

Visualization & Insights



## 📈 Main KPIs Measured

Total Customers

Churned Customers

Churn Rate (%)

Monthly & Yearly Charges

Service Usage Metrics

Subscription Tenure Distribution

## 📊 Dashboard Features

✔ Slicers for Gender, Contact, Payment Method, Churn Status, Tenure Year

✔ Fully interactive segmentation

✔ Donut charts, bar charts, card KPIs, and tables

✔ Churn analysis segmented by:

Gender

Senior Citizens

Partners & Dependents

Payment Method

Contracts

Internet Service

Subscription Year

## 📐 Sample DAX Measures

Admin Tickets = 
CALCULATE(
    COUNTROWS('Churn-Dataset'),
    'Churn-Dataset'[numTechTickets] = "Admin"
)

Total Customer = COUNTROWS('Churn-Dataset')

Churn Citizen% = DIVIDE([Churned Senior Citizens],[Churned Customers],0)

Churn% = ([Churned Customers]/[Total Customer])

Total Charge = CALCULATE(SUM('Churn-Dataset'[TotalCharges]),'Churn-Dataset'[Churn]="Yes")

Churn Rate = DIVIDE([Churned Customers], [Total Customers])




## 🎯 Business Value

Identify at-risk customers

Understand churn drivers

Improve customer retention strategies

Optimize service offerings

Support data-driven decisions for telecom teams


## How to Open

1. Clone repo
2.    git clone https://github.com/MReza07/Customer-Churn-Analysis/tree/main/Report

3.2. Open `PBIX/Sales Data Analysis.pbix` in Power BI Desktop (latest).

3.  Go to Home → Transform Data → Refresh to load latest dataset.
4.  
5.  4. If prompted, update data source to `Dataset/Dataset.xlsx` then Refresh.


## 📜 License

This project is released under the MIT License.

## 📬 Contact

Md. Rezaul Repon

Data Analyst (Power BI | SQL | Python)

🔗 GitHub: https://github.com/MReza07

📧 Email:reazulrepon@gmail.com



