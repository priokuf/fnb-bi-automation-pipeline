# F&B BI Automation Pipeline

This repository showcases an end-to-end Business Intelligence (BI) Engineering solution designed for an F&B company environment.
The pipeline automates data ingestion from SAP and DMS systems, loads and transforms data into a SQL Server Data Warehouse, and delivers analysis-ready models via SQL Server Analysis Services (SSAS) for Excel-based reporting.

The solution emphasizes reliability, automation, and operational monitoring — including file detection, scheduled execution, bulk loading, data modeling, and email notifications for both success and failure events.


## Key Features
- Automated file detection from SAP/DMS landing folder  
- Scheduled ETL orchestration using Windows Task Scheduler  
- Bulk insert into SQL Server staging and warehouse tables  
- Data mart development for reporting use cases  
- Semantic modeling using SQL Server Analysis Services (SSAS)  
- Email notification for success and failure monitoring

## Architecture Overview
![BI Pipeline Architecture](diagrams/bi_pipeline_architecture.png)
