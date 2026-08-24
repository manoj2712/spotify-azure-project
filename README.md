# Spotify End-to-End Azure Data Engineering Project
# Overview

An end-to-end Azure Data Engineering project implementing a scalable ETL/ELT pipeline for Spotify data using Azure Data Factory, ADLS Gen2, Azure Databricks, PySpark, Delta Lake, and Unity Catalog.

The project follows the Medallion Architecture (Bronze → Silver → Gold) and demonstrates incremental data ingestion, metadata-driven processing, streaming, data transformation, dimensional modeling, and SCD Type 2 implementation.

# Architecture
Source Data
    │
    ▼
Azure Data Factory
    │
    ▼
Azure Data Lake Storage Gen2
    │
    ▼
Bronze Layer
    │
    ▼
Azure Databricks / PySpark
    │
    ▼
Silver Layer
    │
    ▼
Gold Layer

# Technologies
Azure Data Factory
Azure Data Lake Storage Gen2
Azure Databricks
Apache Spark
PySpark
Delta Lake
Unity Catalog
Structured Streaming
Databricks Auto Loader
Delta Live Tables / Lakeflow Pipelines
Azure SQL Database
Jinja2
GitHub

# Key Implementations
Built parameterized and metadata-driven Azure Data Factory pipelines.
Implemented incremental data ingestion and historical backfill processing.
Ingested raw data into ADLS Gen2 using the Bronze layer.
Performed data cleansing and transformation using PySpark and Databricks.
Implemented Structured Streaming and Auto Loader for incremental processing.
Created reusable PySpark transformation utilities.
Implemented Bronze, Silver, and Gold data layers using the Medallion Architecture.
Designed fact and dimension tables following dimensional modeling principles.
Implemented SCD Type 2 using Databricks Auto CDC to maintain historical changes.
Used Unity Catalog for data governance and management.

# Project Structure
spotify-azure-project/
│
├── Databricks_Code/
├── dataset/
├── factory/
├── linkedService/
├── pipeline/
├── source_script/
├── screenshot/
└── README.md

# Project Screenshots
Screenshots of the Azure Data Factory pipelines, Databricks implementation, and project architecture are available in the screenshot directory.

# Reference
This project was developed as a hands-on implementation based on an end-to-end Azure Data Engineering tutorial, with the implementation and project code maintained in this repository.
