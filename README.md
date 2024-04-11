# medallion-Azure-DBT-spark
 
In this Project, I jsut want to familiarize myself with Microsoft Azure Technoogy. Thus i build a simple data engineering project that involve using Apache Spark, Azure Databricks, Data Build Tool (DBT) using Azure as my cloud provider. This project illustrate the process of data ingestion to the lakehouse, data integration with ADF and data transformation with Databricks, and DBT. I mainly learn about this technology from youtube, and online documentation. The data I use is sample data from Azure, AdventureWorks. 

## System Architecture

For this project i want to implement modern data engineering technique, the medallion architecture. This architecture allow us to ahve 3 layers of transformation:

Bronze Layer - The data that coming to the system is uncut ie raw data.
Silver Layer - The data then have been transformed, changed and might been removed form the system.
Gold Layer - The data that already ready to be used by different unit such as Business Intelligence and Analytics.

## Technologies

Technologies that I want to learn and familiar myself with from this project:

- Microsoft Azure Cloud Platform
- Azure Data Factory
- Azure SQL Databases
- Azure Data Lake Gen 2
- Azure Databricks
- Apache Spark
- DBT (Data Build Tool)
- SQL query

### Learned so far
DBT is command-line tool that enables data analysts and engineers to transform data in their warehouses more effectively. It provides a consistent and standardized approach to data transformation and analysis, making it easier for data analysts and engineers to work with data.

Azure Data Factory is a cloud-based data integration service developed by Microsoft as part of their Azure platform.  It allows organizations to create, schedule, and manage data pipelines that can move and transform data from various sources to different destinations. ADF offers several key features, including data movement and transformation activities, data flow transformations, integration with other Azure services, data monitoring and management, and support for hybrid data integration.

Azure Databricks is a cloud-based analytics platform built on top of Apache Spark that simplifies the process of data engineering, data exploration, and model training. It offers an interactive workspace that allows users to easily create, manage, and deploy big data processing and machine learning workloads.

Azure Data Lake Storage Gen 2  is a cloud-based repository for both structured and unstructured data, designed for highly scalable big data analytics solutions.  It combines the management and scalability features of Azure Blob Storage and Azure Data Lake Storage Gen1, including a hierarchical file system with granular security and lower-cost tiered storage. It offers highly scalable storage, processing capabilities, high availability, and disaster recovery.

### Appendix

![image](https://github.com/AsyrafMustaffa-01/medallion-Azure-DBT-spark/assets/155541067/06a4b380-1e0a-4149-b671-fbd1bf85a3cb)
Snippet of Data Pipelines.

![image](https://github.com/AsyrafMustaffa-01/medallion-Azure-DBT-spark/assets/155541067/309d3bce-4b5d-4ccd-b9f9-5a02639f4ab8)
Snippet of using Azure Databricks to load data to bronze layer.

![image](https://github.com/AsyrafMustaffa-01/medallion-Azure-DBT-spark/assets/155541067/fb9f774b-fcac-45bf-9da3-e92d726d176f)
Snippet of Documentations generated to documentation the transformation that has been done to data.

