# Fraud-tracking-tool
A demo version of a fraud tracking tool that simulates how flagged data is matched and summarized using SQL automation. All data and column names have been anonymized to protect sensitive information, demonstrating secure development practices and fraud investigation logic.
# Fraud Tracking Automation Tool (Demo)

This is a **simulated version** of a fraud tracking tool built for internal investigations. The real version is used to match serial numbers and transaction details from multiple data sources, including large transaction logs and compliance systems.

## Overview

The tool:
- Processes input files containing potentially fraudulent records.
- Matches them against historical and live databases using SQL.
- Automates fraud type categorization (e.g., Type 2 vs Type 3).
- Outputs structured summaries to aid investigators.

## Technologies Used
- SQL (Snowflake, CMOR-style queries)
- Excel (for automation and data structure)
- Python/Excel macros (in the full version)

## Security Notice

To protect sensitive company and customer data, **all columns, filenames, and values have been anonymized or replaced with sample data**. No real names, serials, or transaction IDs are included. This repo reflects the structure and logic of the tool only.

## Contents
- `queries/fraud_summary_query.sql`: Example logic for aggregating flagged records by type and duration.
- `queries/serial_match_sample.sql`: Sample logic for matching user-provided data against an internal dataset.
