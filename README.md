# RFM Analysis Dashboard for Customer Segmentation

## Overview
This project explores the use of RFM (Recency, Frequency, and Monetary value) analysis to segment customers based on their purchasing behavior. The goal is to provide actionable insights into customer behavior to drive targeted marketing and improve customer retention strategies.

### Data Source
This project uses data gotten from this [RFM Analysis Case Study](https://statso.io/rfm-analysis-case-study/).

## Key Features

### 1. Data Cleaning and Preparation:
I ensured data types were correct and ready for analysis.
Calculated Recency, Frequency, and Monetary values using DAX functions in Power BI.

### 2. RFM Scoring and Segmentation:
Customers were scored on a scale of 1–5 for each metric:
- Recency: Customers with more recent purchases were assigned a higher score.
- Frequency: Customers who had a higher purchase frequency scored higher.
- Monetary: Higher spenders scored higher.

### 3. Customer Segmentation and Categorization.
The individual scores were combined into an overall RFM score, which was used for segmentation into value segments and customer categories
- Low-Value Customers: Minimal engagement and low spending.
- Mid-Value Customers: Moderate engagement and spending.
- High-Value Customers: Frequent, recent purchases with high spending.

Customers were further categorized into:
- Champions: Most loyal and high-spending customers.
- Potential Loyalists: Recent buyers with potential for growth.
- At-Risk Customers: Previously active but declining engagement.
- Can't Lose: Recently lost customers needing attention.
- Lost: Completely disengaged customers.

### 4. Analysis and Visualization:
I developed an interactive 2 page dashboard in Power BI showcasing various insights. Here is what the dashboard looks like:
![Customer Segmentation](path/to/your/image.png)

![Monetary Analysis](path/to/your/image.png)


### 5. Insights
- Champions and potential loyalist drive a cummulative 88.6% of revenue, indicating a strong loyal base. These categories are the backbone of the business and deserve focus for retention and rewards programs.
- Lost Customers represent 4.3% of customer distribution and 2.9% of the revenue distribution. A small, yet crucial group to re-engage through targeted campaigns
- Many customers are one-time buyers, suggesting the need for engagement strategies to encourage repeat purchases.

## Technology Stack
Power BI: Data cleaning, analysis, and visualization.
DAX: Advanced calculations for RFM metrics and scoring.

## Getting Started
- Clone this repository: git clone <repo-url>
- Open the Power BI dashboard file (.pbix) to explore the interactive visualizations.

## Conclusion
This project was an eye-opener into the power of RFM analysis. It’s not just a tool for data scientists—it’s something marketers, business owners, and anyone looking to understand their customers can benefit from. It’s incredible how much you can learn about customer trends and behaviors from just one dataset! Whether you're looking to drive better marketing strategies or simply curious about customer analytics, this project shows how data can unlock actionable insights.
