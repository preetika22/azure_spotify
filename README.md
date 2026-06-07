# azure_spotify

##Overview

Designed and implemented an end-to-end data engineering platform on Azure to ingest, transform, model, and serve Spotify streaming data for analytical reporting and business intelligence.

##Architecture

Source → Azure Data Factory → Azure Data Lake Storage Gen2 → Azure Databricks (PySpark & Delta Lake) → Delta Live Tables → Azure Synapse Analytics

##Key Features
Built automated ingestion pipelines using Azure Data Factory to load Spotify datasets into Azure Data Lake Storage Gen2.
Developed scalable transformation pipelines in Azure Databricks using PySpark and Delta Lake, following the Medallion Architecture (Bronze, Silver, Gold).
Implemented Star Schema data models with optimized fact and dimension tables for analytics workloads.
Utilized Jinja templating to dynamically generate Spark SQL transformations, improving maintainability and reducing code duplication.
Built Delta Live Tables (DLT) pipelines for automated transformations, data quality validation, and orchestration.
Integrated Azure Key Vault and Azure Active Directory for secure secret management and access control.
Published curated datasets to Azure Synapse Analytics for reporting and dashboard consumption.
##Tech Stack
Azure Data Factory
Azure Databricks
PySpark
Delta Lake
Delta Live Tables (DLT)
Azure Data Lake Storage Gen2
Azure Synapse Analytics
SQL
Jinja
GitHub
