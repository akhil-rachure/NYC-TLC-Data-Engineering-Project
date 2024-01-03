# NYC-TLC-Data-Engineering-Project

## Project Overview:

The primary goal of this project is to establish a comprehensive data analytics pipeline for NYC TLC data using a combination of Python, Google Cloud Platform (GCP), and Mage-AI Data Pipeline tool. The ultimate objective is to develop an analytics dashboard using Looker Studio.

## Project Execution

* **Data Extraction/Acquisition**:
Dataset is acquired from the official nyc.gov website, it focusses on TLC's yellow and green taxi trip records. This dataset includes crucial information such as pick-up and drop-off times, locations, trip distances, rate types, payment types. 

  * Data Source - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
  * Data Directory - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

* **Data Modeling**:
The Dataset/flat file is converted into STAR Schema. A comprehensive data model is designed by creating Fact and Dimension tables based on the existing data frame. The Schema is implemented in python.

* **ETL and Data Transformation**:
I leveraged Mage-AI for ETL, which is an excellent data pipeline tool for transforming and integrating data. The data is **Extracted** from the Google Cloud Storage, **Transformed** into desired format using Python and **Loaded** into BigQuery for further analysis. All this process is being done on a Virtual Machine on Cloud.

* **Cloud Computing and Data Analysis**:
Google Cloud Platform is used as the Cloud Infrastructure for handling robust and scalable data . GCP Services used - Compute Engine, Cloud Storage, BigQuery, Firewall, Looker Studio

* **Data Visualization**:
Looker Studio is used for visualization of data and building dashboards. The data is extracted from BigQuery tables.

## Project Infrastructure

<img width="765" alt="architecture" src="https://github.com/akhil-rachure/NYC-TLC-Data-Engineering-Project/assets/25721124/81b78089-1c77-45f5-bc70-3de28c99fea4">

## Data Model
<img width="986" alt="Screenshot 2024-01-01 at 5 07 44 PM" src="https://github.com/akhil-rachure/NYC-TLC-Data-Engineering-Project/assets/25721124/a14840a8-98bf-4dea-b503-61f4077ed949">

## Dashboard
<img width="800" alt="Dashboard" src="https://github.com/akhil-rachure/NYC-TLC-Data-Engineering-Project/assets/25721124/21eec091-ea3e-4de2-9f19-945c0b13cf72">

