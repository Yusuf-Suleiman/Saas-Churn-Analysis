# Saas-Churn-Analysis

**Author:** Yusuf Suleiman
**Domain:** Saas Analytics
**Tools:** Excel (Data Cleaning, Pivot Table, Dashboards)
**Project Goal:** Analyze customer churn, retention and revenue to derive actionable insights for a SaaS business

---
## Project Overview
This project explores a **SaaS subscription dataset** to understand:
- Customer churn patterns
- Revenue lost due to churn
- User engagement across subscription plans, age groups, and region

The goal is to Provide **insights for improving retention** and **maximizing revenue**

## Dataset
**Columns included:**
|  Column  |  Description |
|----------|--------------|
|  Customer_ID  |  Unique customer identifier  |
|  Age  |  Customer age  |
|  Gender  |  Customer gender  |
|  Subscription_Type  |   Type of subscription plan  |
|  Watch_Hours  |  Hours spent watching content  |
|  Last_Login_Days  |  Days since last login  |
|  Region  |  Customer region  |
|  Device  |  Device Used  |
|  Monthly_Fee  |  Subscription monthly cost  |
|  Number_of_Profile  |  Number of profiles per account  |
|  Avg_Watch_Time_Per_Day  |  Average hours watched per day  |
|  Churned  |  Whether a customer has churned (1 = Yes / 0 = No)  |
|  Favorite_Thriller  |  Most watched genre  |

**Folder:**
-`Data/`
    -`Raw/` --- Original dataset
    -`Cleaned/` --- contains the cleaned dataet

## Data Cleaning
- Removed duplicates nd invalid rows
- Replaced `#VALUE ` and missing data
- Fixed negative last login days
- Flagged `churned` into Active, and Churn
- Grouped `Age` into categories: Young Adult, Middle Adulthood, Old

**Folder**
-`Cleaning/Documentation.xlsx` --- contains the detailed cleaning documentation.

## Analysis
- Total Users
- Churn count
- Churn Rate
- Retention Rate
- ARPU
- Lost Revenue
- Retained Revenue

**Insight Explored:**
- Churn by subscription type
- churn by age group, device and region
- Revenue lost by subscription type

**Folder:**
-`Analysis/Analysis.xlsx` --- contains the interactive Excel dashboard with pivot tables and KPIs.

## Visualization
- Doughnut charts for churn, retention, and lost revenue by subscription type
- charts comparing watch time and churn across user categories

**Folder:**
-`Visuals/Customer Churn Dashboard.png` --- containd screenshot of the dashboard.

----

## Key Insight
- loading.....
