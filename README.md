# Vatan Bilgisayar ETL Pipeline

## Project Overview

This project features an **ETL (Extract, Transform, Load) pipeline** designed to extract data from the **Vatan Bilgisayar** webpage using **Python**. The extracted data is processed and loaded into a MongoDB database and also saved in CSV format. Additionally, **MongoDB** queries are retrieved to provide data-driven insights, and **Looker Studio** is utilized for BI (Business Intelligence) analytics.

## Features

- **Data Extraction:** Automatically extracts product data from the Vatan Bilgisayar website.
- **Data Processing:** Cleans and formats the extracted data.
- **Data Loading:** Loads the data into MongoDB and saves it in CSV format.
- **ETL Airflow:** Creates a DAG for automating the ETL process.
- **Data Analytics:** Retrieved MongoDB queries to obtain data-driven insights.
- **Visualization:** Creates analytical reports using Google Looker Studio. https://lookerstudio.google.com/reporting/ad2c3769-a0a3-4206-8e59-ffb5e1330015/page/p_h3jinupdmd If you enter that link, You will see an additional page for filtering the data. Then, Choose a brand and you will see the statistics of that brand. 

### Requirements

- Python 3.x
- MongoDB
- Required Python libraries: `pandas`, `pymongo`, `requests`, `beautifulsoup4`, `datetime', 'regEx', 'airflow'
