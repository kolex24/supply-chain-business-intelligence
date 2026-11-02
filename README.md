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

This visualization helps stakeholders evaluate category-level performance and identify differences between sales volume and profitability.

### Return Orders by Return Reason

A horizontal bar chart summarizes returned orders by return reason.

It helps stakeholders identify frequently reported return categories and investigate potential product, fulfillment, or customer-experience issues.

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

## 10. Key Insights and Business Recommendations

The dashboard provides insights into sales performance, profitability, product returns, and shipping expenditure. These findings highlight opportunities to improve order fulfillment, prepare for seasonal demand, and strengthen profitability monitoring.

### 10.1 Key Business Insights

**Insight 1: Office Supplies generate the highest sales.**

Office Supplies recorded approximately **692.18K in sales**, making it the highest-selling category among the categories displayed in the dashboard.

Furniture generated the highest profit, at approximately **256.26K**.

**Business implication:** The category generating the highest revenue is not necessarily the category generating the highest profit. Management should evaluate sales and profitability together when making product and category-level decisions.

**Insight 2: Wrong-item returns are a major operational concern.**

The return-reason analysis shows that **Wrong Item accounts for 25 returned orders**, making it the most frequently displayed return reason. Late Delivery accounts for 14 returned orders, the lowest among the displayed categories.

**Business implication:** Incorrect shipments may be contributing to avoidable returns and additional fulfillment costs. The business should investigate order-picking, packing, and dispatch verification processes to identify the underlying causes.

**Insight 3: Sales fluctuate throughout the year, with a potential increase toward December.**

The monthly revenue trend suggests that sales increase toward December.

**Business implication:** If this pattern is consistent across multiple years, the business may experience higher demand during the December period. Early planning would help the organization prepare its purchasing, stock availability, staffing, and shipping capacity.

This seasonal pattern should be validated against historical data before being treated as a recurring trend.

**Insight 4: Product-level profitability varies.**

The product-level performance table shows differences in revenue and gross profit across individual products.

**Business implication:** Management should evaluate products based on both revenue and profitability. Products generating substantial sales but relatively low profit may require further investigation into their costs, pricing, discounts, and shipping expenses.

**Insight 5: Shipping expenditure requires continuous monitoring.**

The dashboard reports approximately **71.80K in shipping costs**.

**Business implication:** Although this figure shows the scale of shipping expenditure, it does not independently establish whether shipping is efficient. Further analysis by shipping mode, location, and order volume would help identify potential cost-saving opportunities.

### 10.2 Business Recommendations

**Recommendation 1: Introduce order verification before dispatch**

The shipping department should verify each order before dispatch to ensure that the correct products, quantities, and customer delivery details match the order records.

Recommended actions:

* Introduce a pre-dispatch verification checklist.
* Use barcode scanning or other product identification controls where feasible.
* Record dispatch errors and their causes.
* Monitor order accuracy and wrong-item return rates monthly.

**Expected outcome:** Fewer incorrect shipments, reduced avoidable returns, and improved customer satisfaction.

**Recommendation 2: Prepare for increased December demand**

Management should use historical monthly sales data to estimate December demand and begin preparations before the expected peak period.

Recommended actions:

* Identify products that experience higher December sales.
* Coordinate purchasing and replenishment with suppliers in advance.
* Review warehouse staffing and shipping capacity before the peak.
* Monitor stock availability and order fulfillment throughout December.

**Expected outcome:** Reduced stockout risk, improved fulfillment readiness, and a greater ability to meet seasonal customer demand.

**Recommendation 3: Improve product and category profitability monitoring**

Management should compare revenue and gross profit across product categories and individual products.

Recommended actions:

* Identify products with the highest revenue and gross profit.
* Investigate products with relatively low profit contributions.
* Review the impact of discounts, product costs, and shipping expenses.

**Expected outcome:** More informed product portfolio decisions and improved profitability management.

**Recommendation 4: Monitor and optimize shipping expenditure**

Management should evaluate shipping costs in relation to order volumes, revenue, and delivery performance.

Recommended actions:

* Compare shipping costs across shipping modes.
* Calculate shipping cost per order.
* Investigate unusually expensive routes or delivery methods, where route data is available.
* Monitor delivery delays alongside shipping expenditure.

**Expected outcome:** Improved logistics cost visibility and opportunities to reduce unnecessary shipping expenses without compromising service quality.

**Recommendation 5: Establish regular KPI monitoring**

Management should review the dashboard regularly to monitor business performance and assess whether operational improvements are working.

Recommended actions:

* Review revenue, gross profit, and profit margin monthly.
* Monitor return rates and order accuracy.
* Track shipping cost per order.
* Compare monthly performance with previous periods.
* Establish performance targets for key operational indicators.

**Expected outcome:** Better performance monitoring, earlier identification of operational problems, and more informed management decisions.

## 11. Limitations and Scope

The current dashboard focuses on sales performance, profitability, shipping expenditure, product-level performance, and returns.

Inventory availability, stockout monitoring, and replenishment planning are not directly measured in the current dashboard. Recommendations concerning inventory preparation are therefore based on the observed sales pattern and should be supported by inventory data before implementation.

The dashboard also identifies return patterns but does not independently establish their root causes. Further operational investigation is needed to determine why incorrect shipments, delivery delays, or defective products occur.

In addition, the potential December sales increase should be validated using historical data across multiple years where available.

## 12. Conclusion

The Supply Chain Performance Analysis project demonstrates how Microsoft Power BI can transform business data into an interactive business intelligence solution.

The dashboard consolidates key metrics covering sales, profitability, shipping expenditure, product performance, and customer returns. The analysis highlights the strong sales contribution of Office Supplies, the high profit contribution of Furniture, and the need to investigate wrong-item returns.

The findings also support recommendations to strengthen pre-dispatch verification, prepare for potential seasonal demand, monitor product profitability, and improve shipping cost visibility.

Overall, the project demonstrates the value of combining data visualization with business analysis to identify operational improvement opportunities and support evidence-based decision-making.

![supply chain BI dashboard](<img width="597" height="330" alt="supply_chain_bi" src="https://github.com/user-attachments/assets/61c2d745-23cd-488a-8862-dba6f1711975" />)


