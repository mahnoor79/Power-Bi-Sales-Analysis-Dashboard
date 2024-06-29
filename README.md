# Power-Bi-Sales-Analysis-Dashboard (Task 1)
Developed a comprehensive Sales Analysis dashboard using Power BI to visualize key metrics such as revenue, sales trends, and product performance. Utilized advanced data modeling and DAX functions to provide actionable insights for strategic decision-making.
# 1. Data Set Overview
The dataset comprises detailed sales information for various products. It includes 185,950 records and 12 columns, with each record representing a distinct order. The data spans multiple cities and captures various time-related attributes, allowing for comprehensive temporal analysis.

# 2. Data Set Description
The dataset columns are described as follows:

a) Unnamed: 0: Index column (likely an artifact of the export process).
b) Order ID: A unique identifier for each order, which helps track and reference individual orders.
c) Product: The name of the product ordered, which is useful for product-specific sales analysis.
d) Quantity Ordered: The number of units of the product ordered in a particular transaction.
e) Price Each: The unit price of the product.
f) Order Date: The date and time the order was placed.
g) Purchase Address: The delivery address for the order, is useful for geographic analysis.
h) Month: The numeric representation of the month when the order was placed.
i) Sales: The total sales amount for the order, calculated as Quantity Ordered * Price Each.
j) City: The city where the order was delivered.
k) Hour: The hour of the day when the order was placed, facilitating time-of-day sales analysis.
l) MonthName: The month's name when the order was placed, making temporal trends easier to understand.
# 3.Important Additional Information of data:
**Revenue Trends**: Analysis of the revenue trends over different months can provide insights into peak sales periods and seasonal variations.
**Product Performance:** Identifying top-selling and least-selling products helps in inventory management and marketing strategies.
**Geographic Sales Distribution:** Understanding which cities generate the most sales can inform regional marketing efforts and logistics planning.
**Time-Based Sales Patterns:** Analysis of sales by day of the week and hour of the day can help optimize staffing and operational hours.

# 4. Dashboard Description
The dashboard provides a comprehensive visualization of the sales data, featuring the following components:
**Top Summary Metrics:** Displays key figures like total revenue, total sales quantity, and total profit margin prominently at the top for a quick snapshot of overall performance.
**Sum of Sales by Month:** A line graph illustrating monthly sales trends, helping to identify seasonal patterns and sales peaks.
**Sum of Sales by City:** A bar graph showing the distribution of sales across different cities, highlighting geographical performance.
**Sum of Sales by Day:** A line graph showing the variation in sales on different days of the week.
**Sum of Sales by Product:** A pie chart that breaks down sales by product, providing insights into which products contribute the most to revenue.
**Sum of Quantity Ordered by Product:** A bar graph depicting the total quantity ordered for each product, indicating popular items.
**Filters:** Interactive filters for day, month, product, and city, allowing users to drill down into specific subsets of data for detailed analysis.
# 5. Key Performance Indicators (KPIs) with Results
# a) **Total Revenue:** $34,492.04K
# **b) Explanation:** Represents the total income generated from all sales.
# c) **Result:** The company has generated substantial revenue, indicating strong sales performance.
# d) **Total Sales Quantity:** 209K units
# 1)**Total Profit Margin**: $34,491.9K

**Explanation:** Indicates the total profit margin from all sales. Note that the dataset does not explicitly provide cost data, so this value might need to be derived from additional data.
**Result:** Significant profit margin, reflecting efficient cost management and pricing strategies.

# 2) **Monthly Sales Trend:**
**Explanation:** The line graph shows monthly sales, identifying peaks and troughs.
**Result:** Highest sales in December (104K) and lowest in January (41K), indicating a strong seasonal trend.

# 3) **City-wise Sales Distribution:**
**Explanation:** A bar graph displaying sales by city.
**Result:** Highest sales in San Francisco (0.26M), indicating a strong market presence there.

# 4)Product-wise Sales Contribution:
**Explanation:** A pie chart showing the contribution of each product to total sales.
**Result:** AAA Batteries are the top-selling product (55.4% of total sales).

# 5) Daily Sales Pattern:
**Explanation:** A line graph showing sales on different days of the week.
**Result:** Highest sales on Tuesday (114.2K), indicating potential peak shopping days.

**Conclusion**
The sales data provides a detailed view of the company's performance across various dimensions, including time, geography, and product. The dashboard effectively visualizes key metrics, making it easier to identify trends and areas for improvement. The KPIs show a robust sales performance with substantial revenue and profit margins. The monthly and daily sales trends, along with the geographic distribution, provide actionable insights for optimizing marketing, inventory, and operations. Overall, the data indicates a successful sales strategy with opportunities for targeted improvements based on the detailed analysis provided.
