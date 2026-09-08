# AWS-ETL-Project
This is an ETL project using SQL, AWS S3, AWS Lambda, AWS Glue, AWS IAM, AWS Athena, AWS Redshift, Python, Jupyter Notebook


Dual-source serverless pipeline that ingests support logs and tickets from the Source (MySQL-backed, others) system to local manually and then into Amazon S3 (Raw) using some automation Python code and transforms them via AWS Lambda and AWS Glue into Parquet-based S3 (Processed) datasets, and loads them into Amazon Redshift for reporting — with Amazon Athena enabling ad-hoc SQL analysis and Power BI powering the final dashboards.
