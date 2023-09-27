# Hotel Booking Data Analysis

This project explores and analyzes a dataset of hotel bookings for the years 2015, 2016, and 2017. The dataset contains information about bookings at a City Hotel and a Resort Hotel. The analysis aims to answer various questions related to hotel preferences, visitor demographics, booking trends, and more.

![Hotel Data Analytics](https://github.com/sanji77th/hotel-bookings-data-analytics/assets/42697893/830f8219-819d-48e1-bfb7-f5fa34d47008)


## Table of Contents

- [About the Dataset](#about-the-dataset)
- [Project Overview](#project-overview)
- [Data Engineering Pipeline](#data-engineering-pipeline)
- [Questions Answered](#questions-answered)
- [Acknowledgments](#acknowledgments)
- [License](#license)
- [Contact](#contact)

## About the Dataset

The dataset contains 119,390 observations for a City Hotel and a Resort Hotel. Each observation represents a hotel booking made between July 1, 2015, and August 31, 2017. The dataset includes information about guests, bookings, and economic indicators for the United States. It has been coupled with economic data from the FRED database.

## Project Overview

The project involved the following components:
- Data extraction using Azure Data Factory
- Data transformation and cleaning with Azure Databricks using PySpark
- Handling missing values, changing data types, and preparing the data
- Data loading back to Azure Data Lake Gen2
- Loading data into Azure Synapse Analytics and creating an SQL database
- Development of a Microsoft Power BI dashboard



## Data Engineering Pipeline

The data engineering pipeline included the extraction of data using Azure Data Factory, transformation using Azure Databricks with PySpark, and loading of data back into Azure Data Lake Gen2. Additionally, the data was loaded into Azure Synapse Analytics, and an SQL database was created for further analysis.

![Data Factory](https://github.com/sanji77th/hotel-bookings-data-analytics/assets/42697893/49b0fdd2-be90-4f01-afd1-dd5e1fba56b1)

## Questions Answered

The project's Power BI dashboard answered several questions, including but not limited to:

- Which hotel is preferred by guests with adults, children, and babies?
- Which countries (Portugal, Great Britain, France) choose which hotel?
- Which country has the most visitors, adult visitors, child visitors, and baby visitors?
- What is the most popular meal?
- What is the most popular meal among guests from Portugal, Great Britain, and France?
- When do most bookings occur?
- When do most bookings occur for guests from Portugal, Great Britain, and France?
- What is the most commonly used deposit method?
- What types of rooms are used most frequently?
- What types of rooms are used most frequently by guests from Portugal, Great Britain, and France?
- What types of rooms are used most frequently in hotels?

![hotel_bookings_bi-1](https://github.com/sanji77th/hotel-bookings-data-analytics/assets/42697893/7d447e11-b798-4377-b326-b071117e4c6d)![hotel_bookings_bi-7](https://github.com/sanji77th/hotel-bookings-data-analytics/assets/42697893/adf0d537-6f83-4e3e-9eac-c6084ee6adcf)
![hotel_bookings_bi-6](https://github.com/sanji77th/hotel-bookings-data-analytics/assets/42697893/dcdd1450-51cd-4122-a835-5325ec75ff34)
![hotel_bookings_bi-5](https://github.com/sanji77th/hotel-bookings-data-analytics/assets/42697893/efa2a238-5c36-46bb-a9d5-b9becd9661a5)
![hotel_bookings_bi-4](https://github.com/sanji77th/hotel-bookings-data-analytics/assets/42697893/c23a725b-3af4-449c-a311-cfd226275e7e)
![hotel_bookings_bi-3](https://github.com/sanji77th/hotel-bookings-data-analytics/assets/42697893/995af62a-811b-49b8-856c-4642b3d5d6c5)
![hotel_bookings_bi-2](https://github.com/sanji77th/hotel-bookings-data-analytics/assets/42697893/f22c9aca-bf38-4be4-ab5c-2b08994e839d)



## Acknowledgments

The dataset is originally from the article "Hotel Booking Demand Datasets" by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, February 2019. The cleaned version was uploaded to Kaggle by Thomas Mock and Antoine Bichat.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For inquiries or questions, feel free to contact the project maintainers:

- Sanjitha Amarathunga: [sanjithaamarathunga.ai@gmail.com](mailto:sanjithaamarathunga.ai@gmail.com)

