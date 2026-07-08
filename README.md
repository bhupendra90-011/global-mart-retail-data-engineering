# Global Mart Retail Data Engineering Project

## Project Overview

This project demonstrates an end-to-end retail data engineering pipeline built using Snowflake and AWS S3. The pipeline automatically ingests transaction data from Amazon S3 into Snowflake, processes incremental changes using Streams and Tasks, and prepares clean data for reporting and analytics.

## Architecture

AWS S3
↓
Storage Integration
↓
External Stage
↓
Snowpipe
↓
RAW Layer
↓
Streams
↓
Tasks
↓
STAGING Layer
↓
Reporting Layer

## Technologies Used

- Snowflake
- SQL
- AWS S3
- Snowpipe
- Streams
- Tasks
- Data Warehouse

## Project Features

- Automatic Data Ingestion
- Incremental Data Loading
- Change Data Capture (CDC)
- Data Transformation
- Reporting Queries
- End-to-End ETL Pipeline

## Repository Structure

Dataset/

SQL Scripts/

Architecture/

Documentation/

Screenshots/

README.md

## Author

Bhupendra Singh (Data Engineer)
