# UK Online Retail - Sales Analysis & Interactive Excel Dashboard

## Tools Used
* **Microsoft Excel** (Data Cleaning, Power Query, Pivot Tables, Dashboard Design)
* **GitHub** (Project Documentation & Portfolio Hosting)

## Project Overview
This project demonstrates end-to-end data cleaning, transformation, and business intelligence analysis for a real UK-based online retail wholesaler. The dataset is sourced from the UCI Machine Learning Repository and contains transactional records spanning from December 2010 to December 2011.

The primary goal of this project was to clean a massive raw dataset, construct dynamic summaries, and build an executive-level interactive Excel dashboard to uncover key performance indicators (KPIs) and sales trends.

---

## Phase 1: Data Cleaning & Transformation (Excel)
Raw transactional data often contains anomalies that can distort financial reporting. Before conducting any analysis, the dataset underwent strict validation and cleaning steps in Microsoft Excel:
* **Removal of Cancellations:** Filtered out and excluded all transactions where the `InvoiceNo` started with "C" (representing canceled orders).
* **Quantity Correction:** Isolated and removed negative or zero quantities to ensure valid revenue calculations.
* **Calculated Fields:** Added a custom column for `Sales Amount` using the formula: `[Quantity] * [UnitPrice]`.
* **Date Standardization:** Standardized the `InvoiceDate` field into standard Excel date formats to allow accurate monthly and quarterly grouping.

---

## Phase 2: Pivot Tables & Data Analysis
Using the cleaned dataset, three distinct Pivot Tables were constructed to answer critical business questions:
1. **Monthly Sales Trends:** Analyzed the chronological progression of revenue to identify seasonal demand peaks.
2. **Top 10 Selling Products:** Isolated the highest revenue-generating items to pinpoint product performance.
3. **Sales Distribution by Country:** Evaluated geographic performance to determine the company's primary and secondary markets.

---

## Final Dashboard Preview
Below is a comprehensive preview of the completed interactive Excel dashboard showing the final professional visual presentation:

![Excel Dashboard](dashboard_screenshot.png)

---

## Key Business Findings
1. **Strong Seasonal Pattern:** Revenue showed steady growth from August onward, peaking dramatically in November. This highlights a clear holiday shopping cycle, indicating that inventory and logistical preparation should be ramped up during Q3.
2. **Geographic Concentration Risk:** The United Kingdom heavily dominates the sales catalog, accounting for the vast majority of total revenue. However, steady purchasing from countries like the Netherlands, Ireland (EIRE), Germany, and France suggests strong international expansion potential.
3. **Product Performance:** High-volume service and wholesale items (such as specialized postage and popular decor sets) serve as core revenue drivers, indicating a strong reliance on commercial B2B buyers.

---

## Skills Demonstrated
* Advanced Data Cleaning & Filtering in Microsoft Excel
* Dynamic Data Summarization using Pivot Tables
* Executive Dashboard Layout & Technical Chart Selection 
* Analytical Problem-Solving & Business Insight Generation
* Professional Project Portfolio Documentation

---

## About the Author
* **Walaa Hussein Ibrahim**
* **Role:** Bookkeeping Professional & Computer Science Student (University of the People)
* Specialized in financial record-keeping, data organization, and business intelligence toolsets.
