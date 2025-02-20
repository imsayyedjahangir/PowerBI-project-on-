📊 E-commerce Sales Dashboard
📌 Project Overview
This E-commerce Sales Dashboard is built using Power BI to analyze sales, profits, and customer purchasing trends. The dashboard provides key insights into revenue, profit distribution, and customer behavior across different states, product categories, and payment methods.

📈 Key Features
✔ KPIs Overview: Displays total sales, quantity sold, profit, and average order value.
✔ Sales by State: A bar chart showcasing total revenue contributions from different states.
✔ Customer Insights: Identifies top customers based on purchase amount.
✔ Profit Analysis: Monthly profit trends and sub-category profit distribution.
✔ Category & Payment Mode Breakdown: Visualizes product category-wise sales and preferred payment methods.
✔ Quarter & City Filters: Interactive filters to analyze data based on city and quarter.

🛠️ Tools & Technologies
🔹 Power BI for data visualization
🔹 DAX (Data Analysis Expressions) for calculations and KPIs
🔹 Excel / SQL for data processing (if applicable)

🔢 DAX Measures Used
DAX
Copy
Edit
-- Total Sales
Total Sales = SUM(Details[Amount])

-- Total Quantity Sold
Total Quantity Sold = SUM(Details[Quantity])

-- Total Profit
Total Profit = SUM(Details[Profit])

-- Average Order Value
Average Order Value = DIVIDE((SUM(Details[Amount]) * SUM(Details[Quantity])), SUM(Details[Quantity]))
This measure calculates the Average Order Value (AOV) by dividing the total sales amount by the total quantity sold.

🔍 Insights Derived
📌 Maharashtra has the highest revenue among all states.
📌 Printers and phones contribute significantly to profit.
📌 Harivansh is the top customer in terms of purchase amount.
📌 January had the highest profit among the three months displayed.

🚀 How to Use
1️⃣ Open the Power BI file.
2️⃣ Use the filters (Quarter, City) to customize insights.
3️⃣ Analyze sales trends and customer behavior using interactive visuals.

📂 Project Files
📁 Ecommerce_Sales.pbix - Power BI file with dashboard
📁 Dataset.xlsx - Source data used for analysis

This is a well-structured README with proper headings, bullet points, emojis, and hashtags to make it readable and GitHub-friendly. Let me know if you need any changes! 🚀







