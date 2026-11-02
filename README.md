# Supply Chain Performance Analysis

## 1. Project Overview

The **Supply Chain Performance Analysis** project is an end-to-end Business Intelligence project developed using Microsoft Power BI. It provides an interactive view of sales performance, profitability, shipping costs, product performance, and product returns.

The dashboard helps stakeholders monitor key performance indicators (KPIs), identify operational issues, evaluate product performance, and make data-driven business decisions.

By combining sales, profitability, shipping, and returns analysis into a single reporting interface, the project demonstrates how data analytics can transform operational data into actionable business insights.

## 2. Business Problem

Organizations need to monitor sales performance, profitability, shipping expenses, and product returns to understand how effectively their operations are performing.

However, when these metrics are analyzed separately, decision-makers may struggle to identify underperforming products, understand return patterns, monitor profitability, and evaluate operational costs.

This project addresses the need for a centralized and interactive reporting solution that allows stakeholders to explore business performance across different categories, months, years, states, and shipping modes.

## 3. Project Objectives

The objectives of this project are to:

* Monitor total orders, revenue, gross profit, and shipping costs.
* Evaluate profitability and profit margin.
* Compare sales and profit performance across product categories.
* Analyze monthly revenue and gross profit trends.
* Identify common reasons for product returns.
* Compare revenue and profit contributions across individual products.
* Enable interactive analysis using State, Month, Year, and ShipMode filters.
* Provide stakeholders with a consolidated view of key business performance indicators.

## 4. Business Questions

The dashboard was designed to answer the following questions:

1. How many orders were recorded during the selected period?
2. What are the total revenue, gross profit, and shipping costs?
3. What is the overall profit margin?
4. Which product categories generate the highest sales and profit?
5. How do revenue and gross profit change from month to month?
6. What are the most common reasons for product returns?
7. Which products contribute the most to revenue and gross profit?
8. How does business performance vary by state, year, month, and shipping mode?

## 5. Dashboard Features

### KPI Cards

The dashboard displays four primary performance indicators:

* **Total Orders:** Measures the volume of orders processed.
* **Gross Profit:** Measures the profit generated after the costs included in the profit calculation.
* **Total Revenue:** Measures revenue generated from sales.
* **Shipping Cost:** Measures the shipping expenses associated with fulfilling orders.

Supporting metrics include:

* Return Orders
* Profit Margin
* Previous-Month Sales
* Return Rate

These indicators provide a high-level overview before users explore the detailed visuals.

### Sales and Profit by Category

A comparative chart displays sales and profit across product categories.
Office supplies generate the most sales (692.18K) and Furnitures generate the highest profit(256.26K)

This visualization helps stakeholders evaluate category-level performance and identify differences between sales volume and profitability.

### Return Orders by Return Reason

A horizontal bar chart summarizes returned orders by return reason.

It helps stakeholders identify frequently reported return categories and investigate potential product, fulfillment, or customer-experience issues.
- Wrong items (25) is the most frequently return order i.e wrong items are mistakenly ships 25 times
- while late delivery (14) have the least return

### Monthly Revenue and Gross Profit Trends

A monthly trend chart compares revenue and gross profit over time.

This visualization supports the monitoring of business performance, identification of changing trends, and comparison of revenue and profitability patterns.

### Product-Level Performance Table

A detailed table presents product-level revenue and gross profit.

Unlike the initial version, the corrected table displays values that vary by product, allowing stakeholders to compare individual product contributions rather than seeing repeated grand totals.

### Interactive Filters

The dashboard includes slicers for:

* State
* Month
* Year
* Shipping Mode

These filters enable users to investigate performance for selected locations, periods, and shipping methods.

## 6. Key Performance Indicators

| KPI                  | Business Purpose                                                       |
| -------------------- | ---------------------------------------------------------------------- |
| Total Orders         | Measures order volume.                                                 |
| Total Revenue        | Measures sales revenue.                                                |
| Gross Profit         | Measures profit based on the defined business calculation.             |
| Profit Margin        | Evaluates profitability relative to revenue.                           |
| Shipping Cost        | Tracks logistics expenditure.                                          |
| Return Orders        | Measures the number of returned orders.                                |
| Return Rate          | Evaluates the frequency of returns relative to the chosen denominator. |
| Previous-Month Sales | Supports comparison with the preceding month's sales.                  |

*The precise DAX definitions and denominators should be documented alongside the measures to ensure consistent interpretation.*

## 7. Tools and Technologies

* **Microsoft Power BI Desktop:** Dashboard development and data visualization.
* **Power Query:** Data preparation and transformation, where applied.
* **DAX:** KPI calculations and analytical measures.
* **Data Modeling:** Relationships between relevant tables, where applicable.

## 8. Technical Implementation

The project brings together business performance metrics in an interactive report.

The implementation focuses on:

1. Preparing the available data for analysis.
2. Developing measures for key business metrics.
3. Creating visuals that answer the identified business questions.
4. Configuring slicers for interactive analysis.
5. Validating product-level calculations to ensure that results respond appropriately to product context.
6. Reviewing KPI calculations for consistency and accuracy.

## 9. Business Value

The dashboard provides a foundation for several business activities:

* **Performance monitoring:** Track orders, revenue, profit, and shipping expenses.
* **Product evaluation:** Compare product-level financial contributions.
* **Returns investigation:** Identify common return reasons for further analysis.
* **Trend monitoring:** Observe changes in revenue and gross profit over time.
* **Operational analysis:** Explore performance across states and shipping modes.
* **Decision support:** Give stakeholders a consolidated view of business performance.

## 10. Limitations and Scope

The current dashboard focuses on sales, profitability, shipping costs, and returns.

Inventory replenishment and stock-risk monitoring are outside the scope of this dashboard version. The report should therefore not be interpreted as a complete inventory optimization solution.

The dashboard highlights patterns and potential areas for investigation; further analysis is needed to establish root causes and validate specific business recommendations.

## 11. Conclusion

The Supply Chain Performance Analysis project demonstrates the application of Power BI to business performance monitoring and exploratory analysis.

By integrating key financial, product, shipping, and returns metrics into one interactive dashboard, the report enables stakeholders to explore performance patterns and identify areas that may require further investigation.

The project also demonstrates the importance of validating DAX measures and ensuring that product-level calculations respond correctly to the relevant filter context.

## 12. Future Enhancements

Potential future enhancements include:

* Adding inventory availability and stockout monitoring.
* Introducing supplier performance analysis.
* Developing more detailed shipping efficiency comparisons.
* Adding targets and variance analysis.
* Incorporating drill-through pages for detailed product and regional investigations.
* Developing a dedicated inventory replenishment dashboard.
