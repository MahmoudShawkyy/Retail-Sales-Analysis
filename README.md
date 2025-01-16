# Retail-Sales-Analysis
## Project Overview
This project focuses on analyzing Walmart store sales data using big data tools like Sqoop, HDFS, and Hive to help businesses understand store performance and the factors influencing sales. For example:-

 - Identify stores with the lowest and highest sales.

- Find stores with the most unpredictable sales (highest variation).

- Determine stores with the best growth over a specific period.

## Tech Stack
Languages: SQL, Bash

Services: AWS EC2, Docker, MySQL, Sqoop, Hive, HDFS

## Tools and Services:

AWS EC2: Virtual server for running applications on the cloud.

Docker: Platform for containerized application deployment.

MySQL: Relational database for initial data storage and table setup.

Sqoop: Tool for importing/exporting data between Hadoop and relational databases.

Hive: Distributed data warehouse for querying and managing large datasets.

## Data Pipeline Workflow

Launch containers using Docker.

Set up MySQL for table creation.

Import data from MySQL to Hive using Sqoop.

Perform data transformations and analysis in Hive.

## Dataset Description

The Walmart Store Sales dataset includes 6436 data points with these attributes:

Store

Date

Weekly_Sales

Holiday_Flag

Temperature

Fuel_Price

CPI

Unemployment

