# Hotel Booking Analytics Platform

## Project Overview
An end-to-end Data Engineering project built using Databricks SQL and Lakeflow Spark Declarative Pipelines to transform raw hotel booking data into analytics-ready datasets.

## Technologies Used
- Databricks
- SQL
- Lakeflow Spark Declarative Pipelines
- Medallion Architecture

## Project Architecture

**Bronze Layer**
- Raw hotel booking data ingestion.

**Silver Layer**
- Data cleaning and transformation.
- Duplicate removal.
- Invalid records separation.

**Gold Layer**
- Monthly Booking Summary
- Hotel Performance Summary
- Room Type Summary
- Booking Channel Summary
- Data Quality & Reconciliation

## Data Quality Results

| Metric | Count |
|---|---:|
| Bronze Records | 1316 |
| Clean Records | 1269 |
| Rejected Records | 21 |
| Duplicate Records | 26 |

**Reconciliation:** 1316 = 1269 + 21 + 26

**Status:** Passed

## Dashboard
Created a 3-page Databricks AI/BI Dashboard:
1. Overview
2. Hotels, Rooms & Channels
3. Data Quality

## Key Learnings
- Building an end-to-end ETL pipeline.
- Implementing Medallion Architecture.
- Writing SQL transformations.
- Applying data quality checks.
- Creating business-ready analytics dashboards.

## Author
Hotel Booking Analytics Platform – Data Engineering Internship Project.
