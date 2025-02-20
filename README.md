ETL Pipelines for Data Processing

This repository contains multiple ETL (Extract, Transform, Load) pipelines for handling different data sources, including API, CSV, and Excel files.

Project Structure

ETL_pipeline_api/ - Extracts data from an API, transforms it, and loads it into a database.

ETL_pipeline_csv_1/ - Processes CSV data, cleans it, and stores it for analysis.

ETL_pipeline_csv_2/ - A similar CSV-based ETL pipeline with different transformation logic.

ETL_pipeline_excel/ - Reads Excel files, performs data wrangling, and loads structured data.

Technologies Used

Python (pandas, requests, sqlalchemy, psycopg2)

PostgreSQL (for structured data storage)

Jupyter Notebook (for development and testing)

Overview

Each pipeline follows the standard ETL process:

Extract - Data is fetched from APIs, CSV, or Excel sources.

Transform - Cleaning, filtering, and structuring the data.

Load - Processed data is stored in a PostgreSQL database for further analysis.

Expected Outcome

Well-structured, cleaned, and formatted data.

Ready-to-use datasets stored in a relational database for querying and analytics
