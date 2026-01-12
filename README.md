# **Customer Churn Analysis & Retention Strategy**
**Power BI + Python**

## Project Overview

Customer churn represents a critical challenge for subscription-based businesses.
This project analyzes customer churn patterns to identify key drivers, segment customers by risk level, and propose actionable, data-driven retention strategies.

The workflow combines Python for exploratory data analysis (EDA) and Power BI for interactive analytics and business storytelling, ensuring both analytical rigor and decision-oriented insights.

## Business Objectives

-Understand overall customer churn behavior
-Identify the main drivers of churn across contracts, tenure, and pricing
-Segment customers by churn risk
-Quantify revenue at risk
-Prioritize retention actions with the highest business impact

## Analytical Workflow

The analysis follows a structured, end-to-end approach:

### 1 - Exploratory Data Analysis (Python)

Python was used to:

-Explore data distributions and missing values
-Validate churn rates and customer counts
-Analyze relationships between churn, tenure, pricing, and contract types
-Support hypothesis generation before dashboard design

### 2️- Interactive Analysis & Storytelling (Power BI)

Power BI was used to:

-Model churn-related metrics using DAX
-Build interactive dashboards
-Translate analytical findings into business insights
-Enable segmentation, prioritization, and decision-making

## Dashboard Structure

### Page 1 — Executive Overview
High-level churn indicators:

-Total customers
-Overall churn rate
-Average tenure
-Average monthly charges
-Churn distribution
-Churn by contract type and tenure group

Key insight:
Month-to-month contracts show significantly higher churn compared to long-term contracts.

### Page 2 — Contract & Pricing Analysis
Deep dive into churn drivers:

-Churn rate by contract type
-Monthly charges comparison between churned and retained customers
-Churn behavior across pricing tiers

Key insight:
High-paying, month-to-month customers churn at substantially higher rates, highlighting price sensitivity combined with low contractual commitment.

### Page 3 — Retention Opportunities
Action-oriented segmentation and prioritization:

-High-risk customer count

-Churn rate for the high-risk segment

-Revenue at risk

-Risk-based customer segmentation

-Suggested retention actions by segment

Key insight:
Targeting high-paying, short-tenure, month-to-month customers offers the greatest retention impact.

## Customer Risk Segmentation
Customers were segmented based on:

-Contract type
-Customer tenure
-Monthly charges

## Risk Segment	Description
-High Risk:	Month-to-month customers with high monthly charges and short tenure

-Medium Risk:	Month-to-month customers with moderate charges or mid-range tenure

-Low Risk:	Long-term or high-tenure customers

This segmentation enables focused retention strategies with higher expected ROI.

## Business Recommendations

-High Risk Customers
Offer targeted discounts, contract upgrades, or personalized retention incentives.

-Medium Risk Customers
Promote service bundles or loyalty programs to increase perceived value.

-Low Risk Customers
No immediate action required; continue monitoring and maintaining service quality.

## Tools & Technologies

-Python
-Pandas
-NumPy
-Matplotlib / Seaborn (Exploratory Data Analysis & validation)
-Power BI
-Data modeling
-DAX measures
-Interactive dashboards & storytelling
-Excel

## Key Takeaways

-Churn is primarily driven by contract flexibility and pricing sensitivity
-A relatively small customer segment concentrates a disproportionate share of churn and revenue risk
-Combining Python EDA with Power BI storytelling leads to more robust and defensible insights
-Data-driven segmentation enables focused, high-impact retention strategies

