# Insurance Analytics & Customer Feedback Dashboard

## Overview
Interactive Power BI dashboard for analyzing insurance policies, premiums, coverage, claims, customer information, and customer feedback.

## Data
+ 10,004 insurance records
+ 13 insurance data fields
+ 97 customer feedback records
+ Insurance data loaded from SQL Server
+ Customer feedback data analyzed using sentiment scores

## Data Preparation
Data was prepared using Power Query by:

+ Removing duplicate records
+ Changing data types
+ Handling missing values
+ Creating Active/Inactive policy status
+ Creating Age Group
+ Creating feedback categories based on sentiment scores

## Dashboard Analysis
The dashboard analyzes:

+ Premium Amount
+ Coverage Amount
+ Claim Amount
+ Policy Type
+ Claim Status
+ Age Group
+ Gender
+ Active and Inactive Policies
Interactive slicers are provided for:

+ Policy Number
+ Customer ID
+ Claim Number
## Drill-Through
A drill-through page provides detailed policy-level information, including:

+ Policy Number
+ Customer ID
+ Claim Number
+ Age
+ Gender
+ Coverage Amount
+ Premium Amount
+ Policy Dates
+ Policy Type
+ Claim Status
+ Claim Date
+ Claim Amount
+ Age Group
## Customer Feedback Analysis
Analyzed 97 customer feedback records using sentiment scores.

Feedback was categorized in Power Query into:

+ Good
+ Excellent
+ Needs Improvements
Visuals include:

+ Word Cloud
+ Summary Chart
+ Detailed Feedback Table
## Power BI Service
The report was published and managed in Power BI Service.
The project includes:

+ Workspace
+ Scheduled Refresh
+ Refresh Testing
+ Updated Report Publishing
+ Row-Level Security (RLS)
+ RLS Testing in Power BI Service

## Tools
+ SQL Server
+ Power BI Desktop
+ Power Query
+ Power BI Service

## Screenshots

### Insurance Overview
![image-alt](https://github.com/Aman12424t/insurance_analytics_customer_feedback_dashboard/blob/7810df7245738c40c3dbd5fe86cf002d64ed9c6c/screenshots/png_1.png)

### Policy Details
![image-alt](https://github.com/Aman12424t/insurance_analytics_customer_feedback_dashboard/blob/7810df7245738c40c3dbd5fe86cf002d64ed9c6c/screenshots/png_2.png)

### Customer Feedback & Sentiment
![image-alt](https://github.com/Aman12424t/insurance_analytics_customer_feedback_dashboard/blob/7810df7245738c40c3dbd5fe86cf002d64ed9c6c/screenshots/png_3.png)


