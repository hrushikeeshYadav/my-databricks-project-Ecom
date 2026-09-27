# End-to-End Azure Databricks E-Commerce Data Engineering Project

This repository contains an end-to-end E-Commerce Data Engineering project built using **Azure Databricks, Azure Data Lake Storage Gen2, PySpark, Delta Lake, and Unity Catalog**.

The project demonstrates how to build a structured data engineering solution from the ground up, covering Azure resource configuration, Databricks workspace setup, compute, catalog and schema management, secure storage access, data ingestion, transformation, data quality, and business analytics.

The solution follows the **Medallion Architecture (Bronze, Silver, and Gold)** to organize raw, cleaned, and business-ready data. It uses **Databricks Auto Loader** for file ingestion, **Delta tables** for data storage, and a dimensional model to support analytical queries and Power BI reporting.

## Key Components

* **Azure Infrastructure:** Resource Group, ADLS Gen2 Storage Account, and Azure Databricks Workspace.
* **Databricks Setup:** Workspace configuration, compute resources, Unity Catalog, catalogs, and schemas.
* **Data Governance:** Storage Credentials, External Locations, and centralized access management through Unity Catalog.
* **Data Ingestion:** Databricks Auto Loader to ingest Parquet files from ADLS Gen2.
* **Data Transformation:** PySpark-based cleansing, filtering, deduplication, and data preparation.
* **Medallion Architecture:** Bronze, Silver, and Gold data layers using Delta Lake.
* **Data Modeling:** Fact and dimension tables, including customer, product, region, and order data.
* **Data Quality:** Duplicate checks, validation rules, and referential integrity checks.
* **Analytics:** SQL queries, Databricks SQL Warehouse, and Power BI reporting.

## Project Objective

The objective is to understand and implement the complete data engineering lifecycle using Azure Databricks, from cloud infrastructure and secure data access to incremental ingestion, transformation, data modeling, and business intelligence.

This project also provides practical experience with modern data engineering concepts, including Unity Catalog governance, scalable Spark processing, incremental data ingestion, and production-oriented workflow design.
