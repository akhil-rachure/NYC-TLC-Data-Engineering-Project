# NYC-TLC-Data-Engineering-Project


## Project Overview:

The primary goal of this project is to establish a comprehensive data analytics pipeline for NYC TLC data using a combination of Python, Google Cloud Platform (GCP), and Mage-AI Data Pipeline tool. The ultimate objective is to develop an analytics dashboard using Looker Studio.

## Project Execution
Data Acquisition:
Dataset is acquired from the official nyc.gov website, it focusses on TLC's yellow and green taxi trip records. This dataset includes crucial information such as pick-up and drop-off times, locations, trip distances, rate types, payment types. 

Data Source - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
Data Directory - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

Data Modeling:
The Dataset/flat file is converted into STAR Schema. A comprehensive data model is designed by creating Fact and Dimension tables based on the existing data frame. The Schema is implemented in python.

Transformation and ETL:
I will leverage Mage AI to transform the data into the desired format, preparing it for loading into the cloud. My responsibility includes executing the Extract, Transform, Load (ETL) process to ensure data accuracy and consistency.

Cloud Computing:
Recognizing the impracticality of handling extensive data locally, my choice is GCP as the cloud solution. I will migrate and store the transformed data in the cloud for efficient processing and analysis.

Analytical Outputs:
To facilitate meaningful insights and answers to predefined inquiries, I will construct an intuitive visual interface using Looker Studio. The analytics dashboard I create will serve as a powerful tool for interactive data exploration.

<img width="765" alt="architecture" src="https://github.com/akhil-rachure/NYC-TLC-Data-Engineering-Project/assets/25721124/81b78089-1c77-45f5-bc70-3de28c99fea4">



<img width="800" alt="Dashboard" src="https://github.com/akhil-rachure/NYC-TLC-Data-Engineering-Project/assets/25721124/21eec091-ea3e-4de2-9f19-945c0b13cf72">

<img width="986" alt="Screenshot 2024-01-01 at 5 07 44 PM" src="https://github.com/akhil-rachure/NYC-TLC-Data-Engineering-Project/assets/25721124/a14840a8-98bf-4dea-b503-61f4077ed949">
