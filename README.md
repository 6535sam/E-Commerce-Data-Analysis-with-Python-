# E-Commerce Data Analysis with Python
## Project Objective
The objective of this project is to analyze raw E-Commerce transactional data to understand customer purchasing behavior, sales trends, and product performance. This data-driven analysis helps the business unlock critical insights to optimize inventory, improve marketing strategies, and drive sales growth in upcoming quarters.

## Dataset used
- [Raw Transactional Dataset](https://github.com/6535sam/E-Commerce-Data-Analysis-with-Python-/blob/main/Sample%20-%20Superstore.csv)
## Questions (KPIs)
- What is the monthly revenue trend and which month recorded the highest sales?
- What is the optimal time (peak hours) to display advertisements to maximize customer engagement?
- Which countries/regions are contributing the maximum revenue to the business?
- What are the top 10 highest-selling products based on quantity and total revenue?
- How to handle data anomalies like missing values, cancellations, and negative quantities?

## Process
- **Data Cleansing:** Verified the dataset for missing values (specifically in `CustomerID` and `Description`) and dropped or imputed anomalies.
- **Data Standardization:** Handled negative values in `Quantity` (cancellations) and cleared zero or erroneous entries in `UnitPrice` to ensure consistency.
- **Feature Engineering:** Extracted critical time-based metrics such as `Month`, `Day`, `Hour`, `DayOfWeek`, and calculated the total order value field (`TotalAmount = Quantity × UnitPrice`).
- **Exploratory Data Analysis (EDA):** Grouped data using Python libraries to generate statistical charts and answer core business KPIs.

## Dashboards & Visualizations

### 📈 1. Monthly Revenue & Sales Trend
![Monthly Sales Trend](images/monthly_sales_trend.png)

### ⏰ 2. Peak Ordering Hours (Ad Optimization)
![Peak Hours Analysis](images/peak_hours.png)

### 🌍 3. Top Countries by Total Revenue
![Geographical Distribution](images/top_countries.png)

### 📦 4. Top 10 Selling Products
![Top Products](images/top_products.png)

## Project Insights
- **Seasonal Sales Surge:** There is a significant spike in revenue and order volume during the festive season months (October to December).
- **Peak Engagement Hours:** Maximum customer orders are placed between 11:00 AM and 3:00 PM, identifying this as the prime slot for running online advertisements.
- **Geographical Concentration:** A major portion of the core business revenue is generated from the primary country region, helping streamline localized logistics.
- **Product Turnover:** Retail items with high transaction volume dominate the top 10 list, acting as the main drivers for business turnover.

## Final Conclusion:
To improve the sales and profitability of the E-Commerce store, the strategic marketing plan should focus on running high-conversion ads during the peak hours of 11 AM - 3 PM, boosting stock inventory before the Q4 festive season, and launching targeted loyalty programs for high-volume customers in top revenue-generating regions.
