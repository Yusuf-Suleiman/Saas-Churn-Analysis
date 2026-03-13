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
- churn by age group, gender, device and region
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
|    Subscription Type    |    Revenue Lost    |    Retention Rate    |   Churn Rate    |
|-------------------------|--------------------|----------------------|-----------------|
|    Basic    |    $647    |    75.3%    |    24.7%    |
|    Standard    |   $7,960     |    83.0%    |    17.0%    |
|    Premium    |    $3,706    |    83.2%    |    16.8%    |

- The table above illustrates the discrepancy between revenue loss and churn volume, highlighting that while the Basic plan has the highest churn, the Standard plan represents the greatest revenue risk.
  

|    Subscription Type    |    Young Adult    |    Middle Age    |   Old    |
|------------------------|-------------------------|------------------|----------|
|    Basic    |    28.7%    |    21.7%    |    23.6%    |
|    Standard    |    16.9%    |    17.8%    |    15.6%    |
|    Premium    |    16.9%    |    16.2%    |    17.6%    |

- The Baisc suubscription plan acts as a primary churn driver, exhibiting the highest churn rates across all demographics. Specifically, Young Adults on the Basic Plan churn at a rate of 28.7%, which is significantly higher than the company-wide average of 17%.


|    Subscription Type    |    Female    |   Male     |
|-------------------------|------------|--------------|
|    Basic    |    21.5%    |    28.7%    |
|    Standard    |    17.6%    |    16.3%    |
|    Premium    |    17.2%    |    16.3%    |

- The Male on the Basic plan have the highest churn rate of 28.7%


|    Genre    |    Churn Count    |
|-------------|-------------------|
|    Action    |    175    |
|    Comedy    |    164    |
|    Documentary    |    196    |
|    Drama    |    164    |
|    Thriller    |    148    |

- Users who identify Documentary as their favorite exhibit higher attrition


|    Region    |    Churn Count    |
|--------------|-------------------|
|    Africa    |    9    |
|    Asia    |    230    |
|    Europe    |    322    |
|    North America    |    238    |
|    South America    |    48    |

- Europe exhibit the highest number of churn users


|    Device    |    Churn Count    |
|--------------|-------------------|
|    Laptop    |    186    |
|    Mobile    |    280    |
|    Tablet    |    18    |
|    TV    |    363    |

- Users making use of TV exhibits the highest number of churn in this category


|    Status    |    Avg. Watch Time    |
|--------------|-----------------------|
|    Active    |    2.15    |
|    Churn    |    2.06    |

- Churn users have an average hour of watch time per day as 2.06

## Recommendation
**1 Value Proposition Optimization (Basic Plan)**
- **Target:** New subscribers, Male gender, and Young Adult demographic.
- 


