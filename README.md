Insurance Data Analysis – Power BI Project
📌 Project Overview

This project focuses on analyzing insurance customer data using Power BI to identify trends in customer demographics, policy performance, claim behavior, and risk indicators.
The dashboard provides actionable insights for decision-making and operational improvement.

📊 Key Insights Covered

Customer demographics (age, gender, region, income)

Policy status & performance analysis

Claims summary & claim amount trends

High-risk vs low-risk segmentation

Premium and revenue performance

Loss ratio & profitability metrics

🛠️ Tools & Technologies

Power BI Desktop

Power BI Service

Power Query

DAX

Excel / CSV

Row Level Security (RLS)

Scheduled Refresh

🔧 Data Preparation & Modeling
Data Cleaning (Power Query)

Removed duplicate & null values

Standardized column names

Applied correct data types

Merged and appended tables

Created calculated columns

Data Modeling

Designed a star schema model

Created relationships between fact & dimension tables

Defined hierarchies (Region → State → City)

Built DAX measures:

Total Premium

Total Claims

Claim Count

Loss Ratio

Active Policies

📈 Dashboard Features

Slicers for region, policy type, age group, and gender

KPI cards showing total premium, claims, active policies

Region-wise policy and claim map visualizations

Trend charts for premium growth and claim patterns

Customer segmentation visuals

Policy performance distribution charts

⚡ Power BI Service Deployment
✔ Published the Report

Uploaded the .pbix file to a Power BI workspace.

Validated visuals, measures, and data connections in the cloud.

✔ Scheduled Refresh

Configured Scheduled Refresh to automatically update data.

Connected to OneDrive/SharePoint source for seamless refresh.

Set daily refresh frequency based on business needs.

✔ Managed Roles

Used Manage Roles in Power BI Desktop to define user-level filters.

Verified filtering using View As → Roles.

✔ Row Level Security (RLS)

Applied Row Level Security to restrict data by region/department.

Assigned RLS roles to users in Power BI Service.

Ensured every user sees only their authorized data.

📁 Project Files

insurance-data-analysis.pbix

InsuranceData.csv

🚀 How to Use This Project

Download the .pbix file

Open in Power BI Desktop

Load the dataset (CSV)

Refresh the model

Publish to Power BI Service (optional)
