# COVID-19 Data Engineering Project

## Project Overview
This project focuses on building a scalable **data engineering pipeline** for processing and analyzing COVID-19 data using **AWS services**. The data is ingested from an AWS-managed data lake, preprocessed, and structured for analytical use.

For a detailed breakdown of the project, visit the [COVID19 Data Engineering Documentation](https://devengine.notion.site/COVID19-Data-Engineering-Project-18632fa5808880d289edda50b8c5f857).

## Architecture Overview
The AWS-based data pipeline consists of the following stages:
1. **Data Ingestion**: Data is obtained from an AWS-managed data lake and stored in **Amazon S3**.
2. **Data Crawling**: AWS Glue Crawlers scan the datasets and create a catalog.
3. **Data Processing & Transformation**:
   - AWS **Athena** is used for querying and transformation.
   - Processed data is stored in an S3 bucket.
   - A new database is created in **Athena** to store transformed data.
4. **Data Storage & Security**:
   - Processed data is loaded into **Amazon Redshift** for further analysis.
   - **IAM roles** and policies ensure secure access to AWS services.
5. **Analytics & Reporting**: The final structured data is used for querying.

![Alt Text](https://github.com/suryadeipreddyk/covid19-data-engineering-project/blob/main/Covid%20Data%20Engineering%20Architecture.jpeg)

## Tools & Technologies
- **AWS Services**: S3, Glue, Athena, Redshift, IAM
- **Programming**: Python (for ETL scripts using boto3)
- **Data Formats**: CSV
- **Database Querying**: SQL (Athena, Redshift)

---
This project demonstrates a comprehensive AWS-based **data engineering pipeline** for COVID-19 data processing, transformation, and analytics.


For a detailed breakdown of the project, visit the [COVID19 Data Engineering Documentation](https://devengine.notion.site/COVID19-Data-Engineering-Project-18632fa5808880d289edda50b8c5f857).
