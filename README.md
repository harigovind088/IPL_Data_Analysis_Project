# IPL_Data_Analysis_Project

## Introduction

This project focuses on analyzing IPL (Indian Premier League) cricket data using a data pipeline.Here data is fetched from dataset ,then stored in s3 bucket and transform the data according to user needs using Apache Spark. Here the Project is built on Databricks

## Architecture
![Architecture](https://github.com/harigovind088/IPL_Data_Analysis_Project/assets/80459421/e84cb106-5043-4ff7-bcbf-ecfae8c34826)


## Dataset/API
Dataset is used here which contains information about all the Indian Premier League (IPL) matches till 2017 season.

## Data Source: 
Amazon S3

## Technologies Used:
+ Apache Spark: For efficient and scalable data processing
+ SQL Spark: For intuitive and powerful data querying
+ Matplotlib & Seaborn: For creating stunning visualizations
+ Databricks: For streamlined data lifecycle management, including cluster setup, library handling, and collaborative notebooks


## Project Execution Flow

1. Fetch the IPL dataset and store it in an Amazon S3 bucket.

2. Set up a Databricks cluster and load the raw data from S3 into Databricks.

3. Use Apache Spark for data cleaning, transformation, and enrichment.

4. Perform data analysis using SQL Spark to derive insights and statistics from the cleaned dataset.

5. Use Matplotlib and Seaborn to create visualizations that represent the analyzed data.
