# Home_Sales

This project analyzes home sales data using PySpark and Spark SQL. The goal was to answer key questions about home prices based on features like bedrooms, bathrooms, views, and square footage — while also practicing performance tuning with caching and Parquet formatting.
 Key Steps
Loaded and queried CSV data with PySpark

Registered a temporary table (home_sales)

Calculated average home prices by year, features, and view rating

Used CACHE TABLE to improve query runtime

Saved data partitioned by date_built in Parquet format

Re-ran queries and compared performance to uncached/cached versions

Technologies Used
PySpark

Spark SQL

AWS S3 (CSV file source)

Parquet file format

Results
Query performance improved after caching and further optimized using Parquet with partitioning. Spark SQL allowed flexible and efficient analysis of large-scale housing data.
