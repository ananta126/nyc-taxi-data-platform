# NYC Taxi Data Engineering Platform

## Project Overview

An end-to-end batch data engineering platform built using NYC Yellow Taxi trip data.

The platform will ingest public data, preserve raw records, clean and validate data,
quarantine invalid records, create analytical data models, and support reporting.

## Architecture

- Source: NYC TLC Yellow Taxi Trip Data
- Ingestion: Python
- Storage: Parquet
- Processing: Python, DuckDB
- Transformation: SQL
- Orchestration: Apache Airflow
- Testing: Pytest
- BI: Power BI

## Data Architecture

- Bronze: Raw ingested data
- Silver: Cleaned and standardized data
- Gold: Business-ready analytical datasets
- Quarantine: Invalid or rejected records

## Business Metrics

- Daily trip volume
- Revenue proxy
- Average fare
- Average trip distance
- Pickup location popularity
- Payment type distribution

## Project Goals

- Build an end-to-end data pipeline
- Implement data quality checks
- Implement incremental processing
- Implement pipeline monitoring
- Build analytical data models
- Develop reporting dashboards

## Status

Phase 1 - Environment and repository setup
