# Freshmart-Retail-Casestudy
# FreshMart Business Performance Analysis

## Project Overview

This project analyses FreshMart's business performance using transaction, stockout and store data for 2025.

FreshMart has experienced a 6% increase in footfall while revenue has remained relatively flat. The purpose of this analysis is to investigate possible reasons behind declining basket sizes, understand customer purchasing behaviour, identify stock availability challenges and evaluate differences in store performance.

The project uses Python, Pandas, Matplotlib, Databricks and Power BI to transform raw data into meaningful business insights and actionable recommendations.

# Business Objectives

The main objectives are to:

- Analyse transaction trends and customer purchasing behaviour.
- Investigate changes in average items per basket and basket value.
- Compare loyalty and non-loyalty customer behaviour.
- Identify stockout patterns and their potential relationship with basket performance.
- Evaluate store performance across provinces and store formats.
- Investigate the possible influence of nearby competitors.
- Develop recommendations and measurable performance indicators.

## Project Structure

The project is organised into three main analytical notebooks.

### 1. Transactions Analysis

This notebook focuses on customer purchasing behaviour and sales performance.

Key areas:
- Transaction volume and revenue analysis.
- Average items per basket.
- Average basket value.
- Loyalty vs non-loyalty customer comparisons.
- Monthly purchasing trends.
- Weekday vs weekend shopping behaviour.
- Basket-size distribution.
- Payment method analysis.

# 2. Stockouts Analysis

This notebook investigates product availability challenges across FreshMart stores.

Key areas:
- Stockout event frequency.
- Stockout duration analysis.
- Stockout events by store.
- Monthly stockout trends.
- Weekday vs weekend patterns.
- Comparison of basket performance on recorded stockout days and days without recorded stockouts.

#3. Stores (Dictionary) Analysis

This notebook examines FreshMart's store network and store characteristics.

Key areas:
- Store distribution by province.
- Store format analysis.
- Floor area comparisons.
- Store opening years.
- Nearby competitor presence.
- Store-level transaction and revenue comparisons.

# Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preparation |
| Pandas | Data cleaning and manipulation |
| Matplotlib | Data visualisation |
| Databricks | Notebook development and data processing |
| Power BI | Interactive dashboards |
| GitHub | Project documentation and version control |

## Key Business Findings

The analysis identified several important patterns:

# Customer Purchasing Behaviour
- Loyalty customers averaged approximately 14.43 items per basket compared with 12.66 for non-loyalty customers.
- Average items per basket declined across both customer segments during 2025.
- Non-loyalty customers experienced a larger decline in average basket items and average basket value.

# Stock Availability
- A total of 119 stockout events were recorded.
- All recorded events occurred on weekends.
- Stockout records related to the Household Cleaning category.
- Transactions on recorded stockout days had an average of approximately 11.30 items compared with 13.47 on days without recorded stockouts.

 Store and Competition Analysis
- Stores with nearby competitors averaged approximately 13.02 items per basket.
- Stores without nearby competitors averaged approximately 13.65 items per basket.
- Stores with nearby competitors also recorded a lower average basket value.

These are descriptive findings and do not independently establish that stockouts or competition caused lower basket performance.

## Visualisations

The project includes visualisations covering:

- Monthly basket performance.
- Loyalty vs non-loyalty purchasing patterns.
- Weekday vs weekend transactions.
- Basket-size distribution.
- Payment method distribution.
- Stockout events by month and store.
- Stockout duration distribution.
- Store distribution by province.
- Store format comparisons.
- Competitor presence analysis.

## Power BI Dashboard

The planned Power BI report consists of five interactive pages:

1. **Executive Overview** – Key business performance indicators and trends.
2. **Transactions and Customer Behaviour** – Customer segments, basket size and spending patterns.
3. **Stockouts and Inventory Performance** – Stockout frequency, duration and associated basket performance.
4. **Store Performance and Dictionary Analysis** – Store characteristics and performance comparisons.
5. **Competition and Business Recommendations** – Competitor comparisons, interventions and monitoring metrics.

## Recommendations

The analysis supports the following proposed business interventions:

1. Improve weekend replenishment processes to reduce stock availability problems.
2. Introduce targeted loyalty offers and complementary product promotions to encourage larger baskets.
3. Investigate stores operating near competitors and evaluate local customer and pricing strategies.
4. Test affordable product bundles and value packs.
5. Monitor average basket size, basket value and stockout performance regularly.

### Proposed Monitoring Targets

| KPI | Proposed Target |
|---|---:|
| Average items per basket | Increase by 5% |
| Average basket value | Increase by 5% |
| Stockout hours | Reduce by 20% |
| Stockout events | Reduce by 15% |
| Profit margin | Maintain or improve |

These are proposed targets for future monitoring, not achieved results.

 Data Limitations

- The analysis covers 2025 only, so year-on-year comparisons cannot be established without previous-year data.
- Stockout records cover September to December 2025 and only the Household Cleaning category.
- The stockout data does not include individual product or SKU information.
- The competitor analysis is descriptive and does not prove causation.
- Non-loyalty customers cannot be consistently tracked across separate transactions.
- Transaction counts should not be interpreted as footfall counts.




# Project Deliverables

- Three analytical notebooks.
- Data cleaning and preparation.
- Exploratory data analysis.
- Business-focused visualisations.
- Business recommendations.
- Monitoring metrics and targets.
- Power BI interactive dashboard.
- Project documentation.

# Conclusion

This project demonstrates how data analytics can support retail business decision-making.

By analysing transactions, stock availability and store characteristics, FreshMart can better understand customer purchasing patterns, identify operational challenges and develop targeted strategies to improve basket performance and revenue.

The overall goal is to transform data into practical business insights that support better operational and strategic decisions.

---

**Project:** FreshMart Business Performance Analysis  
**Domain:** Retail Analytics / Data Analytics  
**Year:** 2025  
**Tools:** Python, Pandas, Matplotlib, Databricks, Power BI and GitHub
