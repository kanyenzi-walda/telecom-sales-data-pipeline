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
   ## Key Insights
- Business customers generate higher revenue compared to home users.
- Data cleaning significantly improves analysis accuracy.
- The pipeline reflects real-world telecom sales processes.

## How to Run
1. Clone the repository
2. Install required libraries: pandas, matplotlib
3. Run scripts in order from 1_load_data.py to 4_analysis.py

## Author
Internship-ready project by a data engineering enthusiast.
3. *Transform*: Clean missing values, remove cancelled customers, and standardize data.
4. *Load*: Store the cleaned data into a SQLite database.
5. *Analyze*: Run SQL queries to calculate revenue and customer distribution.

## Project Structure
