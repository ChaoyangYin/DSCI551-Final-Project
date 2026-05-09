# DSCI551-Final-Project: DuckDB Sales Analytics Project

## Sunny Yin
## Overview

This project implements a lightweight sales analytics application using DuckDB. It demonstrates how DuckDB’s internal features—such as columnar storage, vectorized execution, and push-based query processing—improve performance for analytical workloads.

The application is implemented in a Jupyter Notebook and performs aggregation, filtering, and ranking queries on a synthetic sales dataset.

---

## Environment Setup

Ensure you have Python installed (Python 3.8+ recommended).

---

## Install Dependencies

Install required libraries using:

pip install duckdb pandas jupyter

## Project Configuration

No additional configuration is required.

The project uses:

- DuckDB (in-process database)
- A synthetic dataset generated within the notebook (or optional CSV input)

## How to Run the Application
1. Clone the repository:
git clone https://github.com/ChaoyangYin/DSCI551-Final-Project.git

cd DSCI551-Final-Project
2. Launch Jupyter Notebook:

jupyter notebook

3. Open:
DuckDB_project.ipynb

4. Run all cells from top to bottom.

## Reproducing Results

### To reproduce results:

1. Run the notebook from the beginning.
2. The dataset will be:
    - Generated programmatically (synthetic data), OR
    - Loaded from CSV if provided

3. DuckDB will:
    - Load the dataset
    - Execute analytical queries
    - Display results
    - Show execution plans (EXPLAIN, EXPLAIN ANALYZE)

4. Performance comparisons with Pandas will be shown in the output.

## Features
- Aggregation: Total sales by region
- Filtering: Conditional sales analysis
- Ranking: Top-performing products
- Query plan inspection using DuckDB internals
- Performance comparison with Pandas

## Notes
This project does not require any API keys or credentials.
All functionality runs locally using DuckDB’s embedded architecture.

## Repository Structure

DSCI551-Final-Project/

├── DuckDB_project.ipynb

├── data/ (optional)

├── requirements.txt (optional)

└── README.md

## Summary

This project highlights how modern analytical databases like DuckDB efficiently process large datasets using:

- Columnar storage
- Vectorized execution
- Push-based execution pipeline

These features make DuckDB well-suited for OLAP workloads and data analysis tasks.


