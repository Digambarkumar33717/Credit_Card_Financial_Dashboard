Credit Card Analysis Project – README
📌 Project Overview

This project focuses on Credit Card Transaction Analysis and Credit Card Customer Analysis using Power BI. The goal is to understand customer behaviour, spending patterns, revenue drivers, and operational trends through an interactive dashboard.

🎯 Objectives

To analyse and visualise credit card transactions and customer insights.

To identify key revenue drivers, high‑value customers, and spending behaviour.

To evaluate transaction patterns across time, geography, and merchant categories.

To provide a dashboard that supports data‑driven decision‑making for business stakeholders.

To help financial institutions improve targeting, risk assessment, and customer engagement.

🛠️ Steps Followed
1. Data Collection & Understanding

Imported credit card transaction dataset and customer dataset.

Reviewed schema, data types, and initial structure.

2. Data Cleaning & Pre‑Processing

Handled missing values and removed duplicates.

Standardised date formats (e.g., transaction_date, week_start_date).

Converted columns to proper data types (numeric/text/date).

Created calculated columns such as:

Revenue / Transaction Amount

Age Groups

Transaction Categories

3. Data Modelling

Built a star schema model with fact and dimension tables.

Created relationships between transactions and customer tables.

Ensured proper cross‑filter direction.

4. DAX Measures Development

Developed important metrics such as:

Total Revenue

Average Transaction Value

Total Customers

Repeat Rate

YOY / WOW growth

Customer Lifetime Value (CLTV)

5. Dashboard Building

Created two dashboards:

Credit Card Transaction Report

Credit Card Customer Report

Used charts like:

Line charts (trend analysis)

Bar/Column charts (category breakdown)

Donut/Pie charts (customer segments)

Maps (regional spending)

Cards (KPIs)

6. Insights & Interpretation

Derived business insights based on dashboard visuals (see below).

🔍 Key Insights
1. Transaction Insights

Peak transactions occur during weekends/month‑end.

High spending categories: Travel, Dining, and E‑commerce.

Revenue is majorly contributed by top-tier customers and specific regions.

Notable growth/decline trends in transaction frequency over time.

2. Customer Insights

Majority of customers fall in the 25–40 age group, driving the highest revenue.

High‑income professionals use credit cards more frequently.

Loyal customers exhibit higher monthly spend and higher transaction count.

Potential churn group identified through decreased monthly activity.

3. Risk & Behaviour Patterns

Certain segments show unusual spending spikes, requiring monitoring.

Some regions have higher chargeback ratios compared to others.

📦 Final Deliverables

Cleaned Dataset

Data Model

DAX Measures

Power BI Dashboards:

Credit Card Transaction Dashboard

Credit Card Customer Dashboard

Insight Summary

README File
