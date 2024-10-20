# Sales and Finance Analytics in Excel

This project uses Excel to develop a comprehensive set of reports aimed at delivering insights into both sales performance and financial health for Atliq Hardware Technologies. By harnessing Power Query, Power Pivot, and Data Modeling, the project provides valuable metrics for decision-making.

---

## Table of Contents

1. [Objective](#objective)
2. [Key Features](#key-features)
3. [Data and Tools Used](#data-and-tools-used)
4. [Purpose of Sales Analytics](#purpose-of-sales-analytics)
5. [Purpose of Finance Analytics](#purpose-of-finance-analytics)
6. [Workflow Breakdown](#workflow-breakdown)
7. [Role of Reports](#role-of-reports)
8. [Documentation](#documentation)
9. [References](#references)

---

## Objective

The main objective of this project was to create a system of reports that would allow stakeholders at Atliq Hardware Technologies to analyze both sales and financial data at a granular level. This includes tracking market performance, customer behavior, and financial outcomes such as profit and loss, segmented by key dimensions like markets, months, and fiscal years.

---

## Key Features
- Sales Analytics:
  - Market Performance Report
  - Customer Performance Report
- Finance Analytics:
  - P&L Statements by 
    - Market,
    -  Month, 
    -  and Fiscal Year

---

## Data and Tools Used
- CSV Files from Atliq Hardware Technologies:
  - dim_customer.csv: Customer details.
  - dim_product.csv: Product information.
  - dim_market.csv: Market segments.
  - fact_sales_monthly.csv: Monthly sales figures.
  - target.csv: Market performance targets.

- Excel Features:
  - Power Query for data cleaning and transformation.
  - Data Model for relationship building between tables.
  - Power Pivot for calculated measures.
  - User-friendly and visually enhanced reports.

---

## Purpose of Sales Analytics

The Sales Analytics section was designed to offer detailed insights into the performance of markets and customers for Atliq Hardware Technologies, with a focus on:
- Identifying top-performing markets and tracking their sales against targets.
- Understanding customer behavior, including purchasing trends, repeat orders, and overall contribution to sales.

These reports empower the business to optimize its sales strategies by identifying which markets and customers are contributing the most and where improvements are needed.

---

## Purpose of Finance Analytics

The Finance Analytics section focuses on providing a clear and detailed picture of Atliq Hardware Technologies' financial health through:
- Profit and Loss statements, helping to track revenue and costs across different markets.
- Time-based financial trends, providing insights into financial performance across months and fiscal years.

These reports are essential for decision-makers to monitor financial performance and make informed budgeting and resource allocation decisions.

---

## Workflow Breakdown

1. Data Loading
   - Imported five CSV files from Atliq Hardware Technologies into Power Query: dim_customer, dim_market, dim_product, fact_sales_monthly, and target.

2. Data Cleaning
   - Performed data cleaning in Power Query: removed duplicates, unnecessary columns, and standardized formats.

3. Data Modeling
   - Created relationships between tables in the Data Model, added a Dim Date table, and connected tables for accurate reporting.

4. Data Analysis
   - Used Power Pivot and DAX to calculate key metrics such as total revenue, market performance, and target vs. actual sales.

5. Report Creation
   - Developed interactive reports:

     - Customer Performance Report: Analyzed customer behavior and sales contributions.
     - Market Performance Report: Compared sales performance to targets.
     - P&L Reports: Provided financial insights segmented by market, month, and fiscal year.

---

## Role of Reports

The reports in this project play a crucial role in guiding decision-making for Atliq Hardware Technologies:
- Customer Performance Report: 
  - This report helps stakeholders focus on customer-specific strategies by identifying high-value customers and tracking their purchasing behavior over time.
- Market Performance Report: 
  - Enables the business to monitor market success and identify which regions or market segments are meeting or exceeding their sales targets.
- P&L Statements:
  - These reports are essential for financial planning and control, helping the business track profitability and make adjustments in real time based on market or temporal factors.

---

## Documentation

Check out all the created reports that I have attached to this repository.
- [Customer Performance Report](https://github.com/sumanju333/Excel-Sales-Finance-Analytics/blob/main/Customer%20Performance%20Report.pdf)
- [Market Performance Report](https://github.com/sumanju333/Excel-Sales-Finance-Analytics/blob/main/Market%20Performance%20Report.pdf)
- [P&L Statement By Market Report](https://github.com/sumanju333/Excel-Sales-Finance-Analytics/blob/main/P%20%26%20L%20statement%20BY%20customers.pdf)
- [P&L Statement By Year Report](https://github.com/sumanju333/Excel-Sales-Finance-Analytics/blob/main/P%20%26%20L%20statement%20By%20Fiscal%20Year.pdf)
- [P&L Statement By Month Report](https://github.com/sumanju333/Excel-Sales-Finance-Analytics/blob/main/P%26L%20statement%20by%20month.pdf)

---

## References

This project is part of a guided learning experience from the Codebasics website, under the course titled "Excel: Mother of Intelligence." The project utilizes real-world business data from Atliq Hardware Technologies, focusing on sales and finance analytics.
For more details on the course, visit the Codebasics website: [Check Out](https://codebasics.io/courses/excel-mother-of-business-intelligence)




