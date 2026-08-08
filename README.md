#  Retail Café Sales: Data Cleaning & Exploratory Analysis (Excel)

##  Project Overview
This project focuses on **data hygiene, exploratory analysis, and revenue driver identification** using transactional sales data from a retail café. 

Designed as an end-to-end data quality and exploratory case study, this project prioritizes rigorous data hygiene and statistical validation in Excel to ensure accurate, trustworthy baseline reporting.

---

##  Key Data Analytics Skills Demonstrated

* **Data Hygiene & Cleansing:** Imputed missing numerical data (`Quantity`, `Price Per Unit`) using statistical means; handled missing categorical values (`Location`, `Payment Method`) by creating an `"Unspecified"` class to preserve 100% of financial transaction value.
* **Data Formatting & Standardization:** Converted raw categorical codes into clear business text labels and rounded key correlation metrics to 2 decimal places for clean reporting.
* **Pivot Tables & Aggregations:** Structured 4 separate dynamic pivot tables to analyze product performance, basket size distributions, price point tiers, and payment method channels.
* **Data Visualization:** Built multi-axis combo charts and stacked column charts (excluding Grand Total distortions) to communicate spend behavior clearly.

---

##  Key Business Insights

1. **Basket Size Drives Spend (Correlation: +0.70):** 
   Order quantity is the primary driver of revenue growth. Average spend increases linearly from **$3** (1 item) to **$15** (5 items).
2. **Price Elasticity (Correlation: +0.66):** 
   Higher item prices directly increase top-line sales without causing customers to reduce the number of items purchased per transaction.
3. **Volume vs. Revenue Mismatch:**
   * **Top Revenue Drivers:** **Salads** ($19k) and **Sandwiches** ($16k) generate the highest revenue.
   * **Traffic Volume Drivers:** **Coffee** (3,898 units) and **Cake** (4,169 units) drive foot traffic and customer visits.
4. **Channel Neutrality:**
   Customer spend remains consistent across dining options (**In-Store** vs. **Takeaway**) and payment types (**Cash**, **Credit Card**, **Digital Wallet**).

---

##  Actionable Recommendations

* **Product Bundling:** Create promotional meal deals (e.g., *"Coffee + Sandwich"*) to convert 1-item orders into multi-item baskets.
* **Menu Engineering:** Place high-revenue items (**Salads/Sandwiches**) prominently near daily volume items (**Coffee**) on physical and digital menus.
* **POS Data Rules:** Configure Point-of-Sale (POS) systems to require `Location` and `Payment Method` entry at checkout to close the 7% tracking gap.

---

##  Repository Files

* [Dirty Cafe Sales.xlsx](Dirty%20Cafe%20Sales.xlsx) — Full Excel workbook *(Please download file to view interactive pivot tables & charts in Excel/Google Sheets)*
* [Dirty Cafe Sales - Executive Summary.pdf](Dirty%20Cafe%20Sales%20-%20Executive%20Summary.pdf) — Polished project summary document formatted for executive review.
