# aws-glue

![Blank diagram (1)](https://github.com/user-attachments/assets/cb00fef1-76b9-46b7-8382-8268afb0ef7a)

Objective
Build an ETL (Extract, Transform, Load) pipeline using DynamicFrames in AWS Glue.

This script reads two tables from an AWS Glue Data Catalog database, performs a join between the two tables, and calculates the total sales. Finally, the result is written to a Parquet file in S3.

Construct an ETL pipeline in AWS Glue and configure all required components for execution.
Use AWS Glue Crawlers to discover data structures and populate the AWS Glue Data Catalog.
Read information from the AWS Glue Data Catalog and leverage it for necessary data transformations.
Convert CSV files to Parquet format.
Load transformed data into Amazon S3.
- **AWS Services to Use**
- Amazon Athena
- AWS Glue
- AWS Glue Data Catalog
- AWS Glue Crawler
- Amazon S3
- IAM
- **Concepts**
- DynamicFrame: A data structure similar to an Apache Spark DataFrame, but with additional features that make it more suitable for data transformation processes in AWS Glue.
- DataFrame: A data structure that is similar to Apache Spark DataFrame, often used for data processing tasks but in the context of AWS Glue, it has extended capabilities.
