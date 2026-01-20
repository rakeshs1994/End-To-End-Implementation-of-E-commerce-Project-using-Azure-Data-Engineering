# Introduction
This e-commerce project showcases an end-to-end data pipeline implementation using Azure technologies. The solution leverages Azure Data Lake Storage Gen2 for scalable and secure data storage, Azure Data Factory for orchestrating data movement and transformation, and Azure Databricks for advanced analytics and data processing.

# Architecture
<img width="832" height="464" alt="image" src="https://github.com/user-attachments/assets/627f0c83-89c4-4fa3-9aaf-4fe8437f6640" />

# Technology Used
* Programming Language - Pyspark
* Scripting Language - SQL
* Azure Cloud
  * Azure Databricks
  * Azure DataFactory
  * Azure DataLake Storage Gen2
 

# Dataset Used
This dataset aims to serve as a benchmark for an e-commerce fashion store. Using this dataset, you may want to try and understand what you can expect of your users and determine in advance how your grows may be.

Here is the link to the dataset : https://data.world/jfreex/e-commerce-users-of-a-french-c2c-fashion-store

# Project Execution Flow:
Extract data from E-com data.world -> ADLS (CSV Format) -> Azure Data Factory -> ADLS (Parquet Format) 
-> Azure Databricks -> Bronze Layer (Reading the files) -> Silver Layer (Transformation) -> Gold Layer (Combine all data and store it in one table)
