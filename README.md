#End-to-End ETL Pipeline for Bicycle Store
Objective
Design and implement an end-to-end Extract, Transform, Load (ETL) process for a bicycle store using Python. The ETL pipeline will handle data from databases, data lakes, and APIs, involving extraction, data quality checks, transformations, and loading into a structured data model for analytics.

#Milestones
Database and Data Lake Setup

#Initialized a PostgreSQL database with schemas and tables.
Set up folders in a cloud storage solution for additional data storage.
Data Extraction

#Extracted data from PostgreSQL using custom SQL queries.
Read files from the data lake folder structure.
Fetched real-time exchange rates from APIs.
Data Quality Checks

#Handled null values in essential fields.
Removed duplicate rows.
Validated data types and values.
Data Transformation

#Merged latest currency exchange rates for local price calculation.
Added columns to track delivery performance.
Determined customer locality based on store proximity.
Created and utilized lookup tables for resolving ambiguous columns.
Data Modeling and Visualization

#Integrated orders, items, and product details into a unified dataset.
Developed visualizations to illustrate key metrics and trends.
Documented modeling techniques and visualization choices.
Current Progress
Completed database and data lake setup.
Successfully extracted and loaded data from PostgreSQL and data lake.
Implemented data quality checks for null values, duplicates, and data validation.
Completed initial data transformations, including currency conversion and delivery metrics.
Integrated and modeled data for visualization, developing initial visualizations.
Next Steps
#Continue data transformation to enhance data quality and add additional features.
Further refine visualizations and develop comprehensive analytical reports.
Document and finalize the ETL process for future reference and maintenance. 


This project demonstrates proficiency in Python and ETL processes, showcasing the ability to handle complex data workflows and deliver actionable insights for the bicycle store.