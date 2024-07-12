# Analyzing Olympic Data using Azure

## Overview

This project showcases a comprehensive end-to-end data engineering workflow using Azure services. The primary objective is to extract data from an API, transform it using Apache Spark in Azure Databricks, and analyze it with Synapse Analytics. The dataset used is from the Tokyo 2021 Olympics, providing rich insights and visualizations.

## Objectives

- **Data Extraction**: Extract Olympic data from a API
- **Data Integration**: Build a data pipeline using Azure Data Factory to load data into Azure Data Lake Storage.
- **Data Transformation**: Use Apache Spark in Azure Databricks to transform the data.
- **Data Analysis**: Utilize Synapse Analytics to analyze the transformed data.
- **Visualization**: Generate insights and visualizations from the data.

## Azure Services Utilized

### Azure Data Factory

- Orchestrates data movement and transformation.
- Builds and manages data pipelines efficiently.

### Azure Data Lake Storage

- Stores both raw and transformed data.
- Supports structured and unstructured data formats.

### Azure Databricks

- Provides a collaborative environment for data engineering and data science.
- Uses Apache Spark for data processing and transformation.

### Azure Synapse Analytics

- Enables data analysis using powerful SQL queries.
- Facilitates insights and visualizations.

## Workflow Summary

### Data Ingestion

1. **Source Data**: Extract data from GitHub.
2. **Load Data**: Use Azure Data Factory to load raw data into Azure Data Lake Storage.

### Data Transformation

1. **Read Data**: Access raw data from Azure Data Lake Storage using Azure Databricks.
2. **Transform Data**: Process data with Apache Spark.
3. **Store Data**: Save transformed data back into Azure Data Lake Storage.

### Data Analysis

1. **Query Data**: Use Synapse Analytics to query the transformed data.
2. **Visualize Data**: Generate insights and create visualizations using tools like Power BI and Tableau.

## Data Pipeline

![Data Analytics Pipeline](./Data%20Analytics.png)

The data pipeline for this project involves several stages:

1. **Data Source**: Collecting raw data from various sources.
2. **Data Integration**: Automating data movement and transformation with Azure Data Factory.
3. **Raw Data Storage**: Storing data in Azure Data Lake Gen 2.
4. **Data Transformation**: Using Azure Databricks to process and transform data.
5. **Transformed Data Storage**: Storing transformed data back in Azure Data Lake Gen 2.
6. **Data Analytics**: Utilizing Azure Synapse Analytics for data analysis.
7. **Visualization**: Creating interactive dashboards with Power BI and Tableau.

## Getting Started

1. **Azure Setup**: Configure your Azure account and necessary services.
2. **Data Collection**: Gather and prepare your raw data sources.
3. **Pipeline Creation**: Use Azure Data Factory to create data pipelines.
4. **Data Storage**: Store data in Azure Data Lake Storage.
5. **Data Transformation**: Process and transform data with Azure Databricks.
6. **Data Analysis**: Analyze data using Azure Synapse Analytics.
7. **Visualization**: Build interactive dashboards with Power BI or Tableau.



## Conclusion

This project provides a robust approach to building a data analytics pipeline using Azure services. By following the outlined steps, you can efficiently process and analyze large datasets, derive valuable insights, and visualize them through interactive dashboards.

