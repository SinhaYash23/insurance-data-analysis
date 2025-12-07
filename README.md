Insurance Data Analysis – Power BI Dashboard
📌 Project Overview

This project focuses on analyzing insurance customer data using Power BI.
The goal is to identify patterns in customer demographics, policy performance, claim behavior, and risk factors to support data-driven decision-making for insurance teams.

The project includes:

Data cleaning & transformation

Data modeling

DAX calculations

Interactive dashboards

Row Level Security (RLS)

Scheduled refresh setup in Power BI Service

📊 Dashboard Features
1. Customer Demographics Analysis

Age groups, gender distribution, income segmentation

Region-wise customer distribution

2. Policy Performance

Active vs. inactive policy trends

Policy type breakdown

Renewal patterns

3. Claims Analysis

Number of claims, claim amount trends

High-risk vs. low-risk customer segments

Loss ratio metrics

4. Premium & Revenue Insights

Total premium collected

Revenue trends over time

Top contributing segments

🔧 Tools & Technologies Used

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

Power BI Service

Excel / CSV Data Sources

RLS (Row Level Security)

🛠️ Data Cleaning & Transformation

Performed using Power Query:

Removed duplicates and null values

Standardized column names

Created calculated columns

Merged & appended tables

Applied data types

Built star schema model

📐 Data Modeling

Designed a star schema with fact & dimension tables

Defined relationships (one-to-many, many-to-one)

Created DAX measures for KPIs:

Total Premium

Total Claims

Claim Amount

Loss Ratio

Active Policies

Implemented hierarchies (Region → State → City)

🔐 Row Level Security (RLS)

Created RLS roles for region-wise access

Assigned filters using DAX

Tested and validated RLS in Power BI Desktop

Published to Power BI Service and assigned users to roles

☁️ Power BI Service Setup

Published the PBIX report to Power BI Service

Configured Scheduled Refresh (Daily/Hourly)

Connected to OneDrive/SharePoint for auto-updates

Built a workspace for sharing & collaboration

Provided access to managers and specific roles

📈 Final Output

The final dashboard provides:

Clear visibility into customer, policy, and claim performance

Data-driven recommendations for minimizing risk

Insights for improving policy renewals and customer retention

Operational reporting for management teams
