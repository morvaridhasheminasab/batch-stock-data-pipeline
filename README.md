# Batch Stock Data Pipeline

## Overview
This project implements a batch-processing data pipeline for time-series stock data. It uses Apache NiFi for ingestion and transformation, Docker Compose for orchestration, and FastAPI as a lightweight delivery service for processed data.

## Project Goal
The goal of this project is to build a reproducible and containerized data engineering workflow that can ingest, process, and serve structured stock market data efficiently.

## Technologies Used
- Python
- Apache NiFi
- FastAPI
- Docker
- Docker Compose

## Features
- Batch ingestion of time-series stock data
- Containerized architecture for reproducible deployment
- NiFi-based processing pipeline
- FastAPI delivery service for processed outputs
- Designed to handle large datasets, including 1M+ records

## Repository Structure
- `docker-compose.yml` — orchestration of services
- `Dockerfile` — container setup
- `main.py` — delivery service logic
- `data/` — input CSV files
- `documentation/` — architecture diagram, NiFi template, and supporting project documentation

## How It Works
1. Raw stock data is placed in the `data/` folder
2. Docker Compose starts the project services
3. Apache NiFi ingests and processes the data
4. Processed outputs are generated and stored
5. FastAPI serves processed data for downstream access

## Skills Demonstrated
- Data pipeline design
- Containerized service setup
- Batch processing workflows
- Data delivery API implementation
- Technical documentation and reproducibility

## Notes
This project was completed as part of academic coursework and is presented here as a portfolio project demonstrating practical data engineering, pipeline orchestration, and service-based architecture.
