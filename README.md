**Spotify Azure End-to-End Data Engineering Project**
📌 **Project Overview**

This project demonstrates an end-to-end Azure Data Engineering solution for ingesting, processing, transforming, and analyzing Spotify data using Azure cloud services.

The solution implements production-oriented data engineering concepts including incremental data loading, metadata-driven pipelines, backfill processing, Medallion Architecture, Slowly Changing Dimensions (SCD), and Gold-layer business transformations.

🏗️ **Architecture**

Data Sources → Azure Data Factory → ADLS Gen2 → Azure Databricks → Delta Lake → Bronze → Silver → Gold

🛠️ **Technologies Used**
Azure Data Factory (ADF),
Azure Data Lake Storage Gen2,
Azure Databricks,
Apache Spark / PySpark,
Delta Lake,
Lakeflow Declarative Pipelines,
SQL,
GitHub

🚀 **Key Features**
Incremental data ingestion using CDC/watermark concepts,
Dynamic and parameterized ADF pipelines,
Metadata-driven ingestion framework,
Backfill data processing,
Bronze, Silver and Gold Medallion Architecture,
Delta Lake implementation,
Slowly Changing Dimensions (SCD),
PySpark data transformations,
Lakeflow Declarative Pipelines,
Gold-layer business transformations,
Pipeline monitoring and error-handling concepts

📂 **Data Flow**

Source Systems
↓
Azure Data Factory
↓
ADLS Gen2 – Bronze Layer
↓
Azure Databricks / Delta Lake
↓
Silver Layer
↓
Gold Layer
↓
Business Analytics

🎯 **Project Objective**

The objective of this project is to build a scalable and maintainable Azure data platform that demonstrates real-world data engineering patterns for handling incremental ingestion, historical processing, transformation, and analytics workloads.
