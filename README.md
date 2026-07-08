# RetailMax Analysis

## Project Overview

This analysis evaluates RetailMax’s sales performance, customer behaviour, and pricing strategy. Using transactional, customer, product, store, and discount data, three dashboards were developed to provide clear visibility into revenue trends, customer value, channel performance, and the financial impact of discounting.

The insights support RetailMax’s commercial strategy by improving pricing decisions, strengthening customer retention, and enhancing category‑level profitability.

## Dataset Source

The dataset used in this project was provided directly by RetailMax for internal analytical purposes. It contains real operational records across sales, customers, products, stores, and discount activity, ensuring that all insights reflect actual business performance.

## Data Quality Validation

- Missing values were reviewed and handled appropriately
- Invalid or unmatched IDs were checked and corrected
- Numerical fields (revenue, quantity, discounts) were validated for realistic ranges
- Date fields were confirmed to support accurate trend analysis
- Cross table consistency checks were performed across sales, product, customer, and store data

## Data Model

A structured analytical model was created to support consistent reporting across all dashboards. 

The model includes:
- A central Sales Transaction fact table
- Supporting Product, Customer, Store, and Date dimensions

This structure enables unified filtering, KPI consistency, and reliable cross‑dashboard analysis.

## Dashboards

### Revenue and Product Performance Dashboard

Provides visibility into revenue trends, profit stability, category performance, brand contribution, and product level profitability.

<img width="584" height="329" alt="Screenshot 2026-06-27 214941" src="https://github.com/user-attachments/assets/4a6473b7-9bb3-418a-b12c-1fd1ddf025a1" />

### Customer and Channel Intelligence Dashboard

Highlights customer lifetime value, repeat purchase behaviour, retention rates, segment profitability, and channel performance across Online, Store, and Marketplace.

<img width="581" height="327" alt="Screenshot 2026-06-27 220009" src="https://github.com/user-attachments/assets/04d62b60-c40b-489f-bd86-8b6230bc9b16" />

### Pricing, Discount and Margin Optimisation Dashboard

Analyses discount behaviour, price sensitivity, margin erosion, revenue leakage, and the financial impact of promotional strategies across products and categories.

<img width="582" height="328" alt="Screenshot 2026-06-28 000748" src="https://github.com/user-attachments/assets/f22a85bb-3f09-49b7-9d62-1cda0461c06e" />

## Exploratory Analysis
Revenue and Product Performance
- Revenue remains stable throughout the year, ranging from 8.4M to 9.5M.
- Profit stays between 2.1M and 2.3M, with margins at 24 to 25%.
- Lifestyle and Home Appliances each generate 29M in revenue.
- Brand Nova leads with 30.38M.
- Products 101, 102, and 1 show minimal revenue contribution.

Customer and Channel Intelligence
- Customers 991 and 994 generate 37K plus lifetime revenue.
- Bronze and VIP segments deliver the highest profit.
- Repeat purchases remain strong, consistently above 3,900 per month.
- Retention stays stable at 1.7 to 1.9%.
- Online is the strongest channel with 55M revenue.
- Manchester leads all cities with 47M.

Pricing and Margin Analysis
- Revenue increases sharply only when discounts exceed 20%.
- Profit declines steadily as discount percentage rises.
- Products 997, 992, and 999 show significant margin erosion.
- Lifestyle and Office Tech experience the highest revenue leakage.

## Key Insights
- Lifestyle and Home Appliances are the top revenue drivers.
- Online is the highest performing channel.
- Deep discounts increase revenue but significantly reduce margins.
- Margin erosion is concentrated in heavily discounted products.
- Customer retention and repeat purchases remain consistent.
- High value customers contribute disproportionately to revenue.

## Recommendations
Pricing Strategy
- Reduce reliance on deep discounts.
- Tighten discount controls for Lifestyle and Home Appliances.
- Review discount policies for products with high margin erosion.

Product Strategy
- Reprice or delist consistently underperforming products.

Customer Strategy
- Strengthen loyalty programmes.
- Target high value customers with personalised offers.

Channel Strategy
- Prioritise Online promotions for higher ROI.

## Business Impact
Implementing these recommendations will help RetailMax:
- Improve profitability
- Reduce margin erosion
- Strengthen customer retention
- Increase channel efficiency
- Enhance pricing strategy
- Support long term commercial growth
