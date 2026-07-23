# Sales Insights of Electronics Shop

## Overview
Sales data analysis for a company selling hardware products across various ranges.

## Data Preparation
Extracted and modeled 5 tables from raw SQL data:
Sales Market, Sales Product, Sales Transaction, Sales Date, Sales Customers

## Data Modeling
Built relationships between the tables using a Star Schema in Power BI.
[Star Schema.PNG]

## Dashboard
Built an interactive dashboard to surface sales insights.
[Sales_Dashboard.PNG]

### Key Insights
- Delhi NCR is the dominant market, generating 520.72M in revenue (~53% of total) and 989.9K units sold — more than 3x the next closest market (Mumbai).
- Overall revenue trended downward from a peak in early 2018 through 2020, indicating a decline worth further root-cause investigation.
- Customer revenue is highly concentrated: the top customer (Electricalsara St.) accounts for more revenue than the next two customers combined.
- Identified a data quality issue in the Top Products view — a significant share of transactions had missing product IDs, flagging a gap in data capture at the source that would need addressing for more granular product-level insights.

## Tools Used
Power BI, DAX, SQL, Star Schema Data Modeling
