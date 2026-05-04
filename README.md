# -Data-Analysis-customer-shopping-analysis
This data analysis project investigates consumer patterns using a dataset of 3,900 purchases to inform strategic business decisions. The workflow integrates Python for data engineering, SQL for structured querying, and Power BI for interactive visualization.

# Customer Shopping Behavior Analysis

## Overview
This project provides a comprehensive analysis of consumer purchasing patterns using a dataset of **3,900 records**. By integrating **Python**, **SQL**, and **Power BI**, the analysis uncovers key drivers behind customer spending, subscription rates, and demographic trends to provide actionable business recommendations.

## Dataset
The dataset, **customer_shopping_behavior.csv**, includes 18 columns detailing customer demographics and transaction history.
*   **Key Features:** Age, Gender, Purchase Amount (USD), Category, Location, Size, Color, Season, Review Rating, and Subscription Status.
*   **Target Metrics:** Revenue, Customer Retention (Loyalty), and Shipping Efficiency.

## Tools
*   **Python:** Data cleaning and Exploratory Data Analysis (EDA).
*   **SQL (PostgreSQL):** Advanced querying and data aggregation.
*   **Power BI:** Interactive dashboarding and data visualization.
*   **Gamma:** AI-powered presentation generation for executive reporting.

## Steps
1.  **Data Loading & Cleaning (Python):** Handled missing values in review ratings using median imputation and removed duplicates to ensure data integrity.
2.  **Exploratory Data Analysis (EDA):** Visualized distributions of spending across age groups and seasons using Matplotlib/Seaborn.
3.  **Database Management (SQL):** Imported the cleaned dataset into a relational database to execute queries for top-performing products and revenue shares by category.
4.  **Dashboard Development:** Connected the processed data to Power BI to create dynamic filters and KPIs.
5.  **Reporting:** Synthesized findings into a structured report and used Gamma to generate a professional PPT for stakeholders.

## Dashboard
The Power BI dashboard features three primary views:
*   **Executive Summary:** High-level KPIs including total revenue and average purchase amount ($59.76).
*   **Demographic Insights:** Breakdown of spending by gender (52% Male, 48% Female) and age groups.
*   **Operational Metrics:** Analysis of shipping methods and the impact of discounts on customer loyalty.

## Results
*   **Revenue Generation:** Identified that male customers and seasonal trends significantly influence total sales.
*   **Subscription Value:** Found that 27% of customers are subscribers, showing higher lifetime value compared to non-subscribers.
*   **Efficiency:** Determined that Express Shipping correlates with higher review ratings and repeat purchases.

## How to Run
1.  **Python:** Run the `Customer Data (EDA & Cleaning)` notebook to process the raw CSV.
2.  **SQL:** Execute the scripts in `queries.sql` within your SQL environment to generate aggregated tables.
3.  **Power BI:** Open the `Shopping_Behavior_Dashboard.pbix` file to explore the interactive visualizations.
4.  **Presentation:** View the project summary via the Gamma file..
