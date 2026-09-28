# Data Quality and ETL Pipeline

A small Python project demonstrating a CSV-based Extract, Transform, Load workflow and basic validation.

## Features
- Extract rows from a CSV file
- Validate required fields, duplicate IDs, numeric amounts, and status values
- Normalize email addresses and text
- Load valid records into a cleaned CSV
- Export a separate validation-issues report

## Run
Requires Python 3.9+; no external packages.
```bash
python src/etl_pipeline.py
```
Outputs `data/cleaned.csv` and `data/validation_issues.csv`.

## Data
All sample records are fictional. The `.example` email domain is reserved for documentation.

## Skills demonstrated
Python, CSV handling, ETL fundamentals, data validation, error reporting.
