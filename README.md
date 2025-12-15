# Pyspark_EDA_Pipeline
This project demonstrates an end-to-end PySpark pipeline using Databricks.

# Key Spark Concepts Demonstrated
- CSV ingestion with schema inference
- Parquet conversion for performance
- Null & duplicate checks
- String normalization
- Derived columns
- UDFs for business logic
- Aggregations & groupBy
- Data quality checks

# Tech Stack
- PySpark
- Databricks
- Parquet

# Notes:
- Due to file size constraints, the dataset is not included in this repository. You can download the dataset from the following source: https://www.datablist.com/learn/csv/download-sample-csv-files#products-dataset
- Databricks paths are used intentionally. If you run this notebook locally or in another environment, update the 'CSV_PATH' and 'PARQUET_PATH' variables to point to your local files.
- coalesce(1) is used here only for demonstration purposes to generate a single Parquet file. In production, partitioned output is preferred for performance and scalability.
