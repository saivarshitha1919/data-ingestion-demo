# Data Ingestion Demo

## Overview

This project demonstrates a simple data ingestion pipeline for an e-commerce platform.

The objective is to read customer data from a local CSV file, upload it to Azure Data Lake Storage Gen2 (ADLS), and load it into an Azure Databricks Bronze Delta table using PySpark.

This project is used to demonstrate the SDLC Agentic AI Framework.

## Technology Stack

- Python
- PySpark
- Azure Data Lake Storage Gen2 (ADLS)
- Azure Databricks
- Delta Lake
- GitHub

## Project Structure

```
data-ingestion-demo/
│
├── README.md
├── customers.csv
├── ticket.md
├── requirements.txt
├── intake-sources.md
└── src/
```

## Input

- customers.csv

## Expected Output

A Bronze Delta table containing validated customer records.