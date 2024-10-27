# Vatan Bilgisayar ETL Pipeline

## Project Overview

This project features an **ETL (Extract, Transform, Load) pipeline** designed to extract data from the **Vatan Bilgisayar** webpage. The extracted data is processed and loaded into a MongoDB database and also saved in CSV format. Additionally, MongoDB queries are retrieved to provide data-driven insights, and **Looker Studio** is utilized for BI (Business Intelligence) analytics.

## Features

- **Data Extraction:** Automatically extracts product data from the Vatan Bilgisayar website.
- **Data Processing:** Cleans and formats the extracted data.
- **Data Loading:** Loads the data into MongoDB and saves it in CSV format.
- **ETL Airflow:** Creates a DAG for automating the ETL process.
- **Data Analytics:** Retrieved MongoDB queries to obtain data-driven insights.
- **Visualization:** Creates analytical reports using Google Looker Studio.

## Installation

### Requirements

- Python 3.x
- MongoDB
- Required Python libraries: `pandas`, `pymongo`, `requests`, `beautifulsoup4`, `datetime', 'regEx', 'airflow'
