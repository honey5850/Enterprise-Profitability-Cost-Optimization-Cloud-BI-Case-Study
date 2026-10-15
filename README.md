# Enterprise Profitability & Cost Optimization Platform

## 1. Project Overview
An end-to-end analytics engineering and business intelligence
project that analyzes sales performance, profitability, and
cost drivers using the AdventureWorks DW 2020 sample dataset.

## 2. Business Objectives
- Identify profitable and underperforming products.
- Analyze revenue and profit by customer, territory, and time.
- Track order trends and sales performance.
- Build reliable, reusable business metrics.
- Demonstrate cloud-based data ingestion and transformation.

## 3. Technology Stack
- Cloud storage: Azure Data Lake Storage Gen2
- Data integration: Microsoft Fabric Data Factory
- Analytics storage: Microsoft Fabric Lakehouse
- Transformation: Python and SQL
- Visualization: Power BI
- Version control: Git and GitHub

## 4. Architecture
Source CSV files
    -> Azure Data Lake Storage Gen2 (Raw)
    -> Fabric Data Factory
    -> Lakehouse Bronze
    -> Validated and cleaned Silver tables
    -> Business-ready Gold tables
    -> Power BI dashboard

## 5. Repository Structure
- data/: local source and processed data
- docs/: architecture, setup, data dictionary and decisions
- sql/: profiling, validation, transformation and metrics
- notebooks/: Python-based data processing
- pipeline/: ingestion pipeline documentation
- powerbi/: dashboard documentation and screenshots
- scripts/: reusable utilities

## 6. Data Model
The initial scope uses Sales, Sales Order, Customer,
Product, Date and Sales Territory tables where available.

Grain, keys, column names, relationships, and data quality
will be verified against the actual CSV files before modeling.

## 7. Implementation Status
- [x] Project scope defined
- [ ] Source data profiled
- [ ] GitHub repository initialized
- [ ] Azure storage configured
- [ ] Automated ingestion implemented
- [ ] Silver and Gold transformations completed
- [ ] Power BI dashboard developed
- [ ] Data quality tests documented

## 8. Cost Management
Use eligible free tiers or trial credits where available.
Check current pricing before creating resources and delete
billable resources when they are no longer needed.

## 9. Data Sources
AdventureWorks DW 2020 sample model:
https://github.com/microsoft/powerbi-desktop-samples/tree/main/DAX

CSV distribution:
https://github.com/pbi-tools/adventureworksdw2020-pbix

## 10. Disclaimer
This project uses sample data for educational and portfolio
purposes. Business findings are illustrative and should not
be interpreted as actual company financial results.