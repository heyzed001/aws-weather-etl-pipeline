# Weather Data Ingestion System

A cloud-based weather data ingestion system built with Python and AWS that automatically retrieves weather data from the OpenWeather API and stores it in Amazon RDS for historical analysis.

## Overview

This project automates the collection, processing, and storage of weather data for Lagos (including Ikeja). Using a serverless architecture, the system retrieves weather information from the OpenWeather API on a scheduled basis, processes the response, and stores the data in an Amazon RDS database for future querying and analysis.

The project was built to demonstrate cloud-based data automation using AWS services and Python.

## Features

- Automated weather data collection
- OpenWeather API integration
- Scheduled execution with Amazon EventBridge
- Serverless processing using AWS Lambda
- Data storage in Amazon S3
- Historical weather records stored in Amazon RDS
- SQL-ready database for querying and analysis

## Technologies

- Python
- AWS Lambda
- Amazon EventBridge
- Amazon S3
- Amazon RDS
- OpenWeather API
- SQL
- Git & GitHub

## Workflow

1. Amazon EventBridge triggers the AWS Lambda function on a schedule.
2. Lambda requests weather data from the OpenWeather API.
3. The data is processed and validated.
4. A copy of the response is stored in Amazon S3.
5. Processed weather records are inserted into Amazon RDS.
6. Historical data can be queried using SQL.

## Skills Demonstrated

- Python Programming
- REST API Integration
- ETL Pipeline Development
- Cloud Computing (AWS)
- Serverless Architecture
- Database Design
- SQL
- Workflow Automation

## Future Improvements

- Support multiple cities
- Dockerize the application
- Add CI/CD with GitHub Actions
- Build a dashboard for weather visualization
- Add automated testing

## Author

**Abdulaziz Shina Abdulaziz**
