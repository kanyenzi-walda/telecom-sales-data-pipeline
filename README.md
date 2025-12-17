# Telecom Sales Data Pipeline

## Project Overview
This project demonstrates an end-to-end sales data pipeline for a telecommunications company that provides home and business internet services. The pipeline simulates how sales data is collected, cleaned, stored, and analyzed to generate business insights.

## Tools & Technologies
- Python
- Pandas
- SQLite
- SQL
- Matplotlib

## Data Description
The dataset represents internet sales transactions including:
- Customer type (Home or Business)
- Internet plan
- Monthly subscription fee
- City
- Account status (Active or Cancelled)

## ETL Pipeline Steps
1. *Extract*: Load raw sales data from a CSV file.
2. *Transform*: Clean missing values, remove cancelled customers, and standardize data.
3. *Load*: Store the cleaned data into a SQLite database.
4. *Analyze*: Run SQL queries to calculate revenue and customer distribution.

## Project Structure
