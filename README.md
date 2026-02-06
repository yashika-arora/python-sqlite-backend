# python-sqlite-backend
Python backend project demonstrating relational database design, data ingestion, analytics workflows, reporting exports, and external API integration using SQLite.

# Backend Data Pipeline & API Integration
This project implements a modular backend system for relational data processing, reporting, and external API interaction using Python and SQLite.

## Overview
The system ingests structured CSV data into a normalized SQLite database with enforced foreign keys and constraints. It supports backend workflows for querying, reporting, and API interaction, demonstrating end-to-end data handling and validation.

## Key Features
- Relational database schema with primary and foreign key constraints
- CSV data ingestion with validation checks
- Modular backend components for querying and reporting
- Export of results to CSV and text-based reports
- Interactive external API integration with error handling

## Project Structure
- `setup_database.py` — Database creation, schema definition, CSV imports, and validation  
- `analyze_data.py` — Backend query modules answering business questions  
- `generate_report.py` — CSV exports and text-based summary reporting  
- `api_demo.py` — Standalone API interaction demonstration  
- `api_integration.py` — Extended API integration logic  

This repository focuses on backend system design, emphasizing data integrity, modularity, and correctness. The implemented workflows mirror common backend patterns used for transactional systems, analytics pipelines, and service integrations, making the design applicable beyond the example dataset.
