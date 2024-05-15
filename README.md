# Twitter Data Pipeline with Airflow and Python
![image](https://user-images.githubusercontent.com/69507898/221837668-06295313-2608-413b-8428-63638efffa82.png)

# Project Overview
This project demonstrates the creation of an end-to-end data engineering pipeline using Airflow, Python, and various AWS services. The goal is to extract data from Twitter using the Twitter API, transform the data using Python, deploy the code on Airflow running on an EC2 instance, and finally save the processed data to Amazon S3. This comprehensive project covers all the essential steps in building a robust data pipeline.

# Project Steps
# Data Extraction:

1) Use the Twitter API to extract tweets and relevant data.
2) Handle authentication and API rate limits.
3) Extract data in real-time or in batches based on the requirements.

# Data Transformation:

1) Utilize Python to clean and transform the extracted data.
2) Handle data parsing, normalization, and any necessary transformations.
3) Ensure data quality and consistency for downstream processing.

# Pipeline Orchestration:

1) Deploy the transformation code on Apache Airflow.
2) Set up Airflow on an Amazon EC2 instance for pipeline orchestration.
3) Create DAGs (Directed Acyclic Graphs) in Airflow to schedule and manage the data pipeline tasks.

# Data Storage:

1) Save the transformed data to Amazon S3.
2) Organize the data in S3 for easy access and further processing.
3) Ensure data security and proper access controls in S3.

# Technologies Used
1) Twitter API: For data extraction from Twitter.
2) Python: For data transformation and processing.
3) Apache Airflow: For orchestrating and scheduling the data pipeline.
4) Amazon EC2: To host the Airflow instance.
5) Amazon S3: For storing the transformed data.

# Initial requirements:
-Amazon aws account

-Twitter API account:
[  access_key = ""
  access_secret = ""
  consumer_key = ""   
  consumer_secret = ""
]

-Ec2 instance 

-S3 bucket

# Commands once your connected to EC2 
sudo apt-get update

sudo apt install python3-pip

sudo pip install apache-airflow

sudo pip install pandas

sudo pip install s3fs

sudo pip install tweepy


