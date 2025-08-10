# 📊 E-COMMERCE SQL DATA ANALYSIS

Dataset Used: E-commerce_Dataset

Tool Used: SQLite DB Browser

🔧 SQL Features Implemented:

Extracted, filtered, sorted, and grouped data using:

SELECT

WHERE

ORDER BY

GROUP BY

Performed joins to relate records within the same dataset:

INNER JOIN (Self-Join)

LEFT JOIN (Self-Join)

RIGHT JOIN equivalent in SQLite

Created subqueries for comparative analysis.

Applied aggregate functions:

SUM

AVG

COUNT

Created reusable Views for focused analysis.

Optimized queries with Indexes for better performance.

📊 Queries Executed:

Basic Retrieval:

Displayed first 10 rows for dataset overview.

Conditional Retrieval:

Selected specific columns where Sales > 100.

Sorted Results:

Listed top 20 profitable orders.

Aggregated Metrics:

Calculated total sales and profit per product category.

Joins:

Compared products purchased by the same customer using self-joins.

Subquery Analysis:

Found products whose total sales exceed the average sales.

Aggregate by Payment Method:

Summarized sales, average sales, and order count by payment type.

View Creation:

Stored high-value orders (Sales > 200) in a view.

Index Optimization:

Created index on Product_Category and used it in filtered queries.

🧩 Analysis Features:

Self-Join Analysis:

Identified customers purchasing multiple different products.

Subquery Usage:

Compared sales of products against dataset-wide averages.

Performance Optimization:

Used indexes for faster query execution.

🎯 Key Insights:

Fashion category was retrieved as an example of category-based filtering.

High-value orders were separated for focused analysis.

Index creation helped optimize category-based queries.
