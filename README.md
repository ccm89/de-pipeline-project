# de-pipeline-project
# End-to-End Data Pipeline: E-Commerce Events (Cosmetics Shop)

## Overview
This project builds a batch data pipeline that ingests raw e-commerce event data, cleans and validates it, and loads analytics-ready tables for SQL analysis. The goal is to demonstrate practical data engineering skills: ETL design, data quality checks, and warehouse-friendly modeling.

## Architecture
Raw CSV → Ingest → Transform/Clean → Validate → Load (Warehouse) → Analytics Queries

## Tech Stack
- Python (pandas)
- SQL
- Git/GitHub
- Local: Postgres (planned)
- Optional: GCP (Cloud Storage + BigQuery)

## Dataset
- Source: eCommerce Events History in Cosmetics Shop (Kaggle)
- Time range: Oct 2019 – Feb 2020
- Events: view, cart, remove_from_cart, purchase
- Key fields: event_time, event_type, product_id, category_id, category_code, brand, price, user_id, user_session
- Size:
  - Full dataset: ~20M events (5 months)
  - This project starts with a single monthly file locally and is designed to scale

## How to Run (WIP)
```bash
# setup (Coming Soon...)
# run pipeline (Coming Soon...)

