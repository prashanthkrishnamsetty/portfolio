---
title: "YouTube Data Analysis"
description: "Uncover daily YouTube trends using AWS services, analyzing video data for actionable content insights in diverse regions"
# dateString: May 2018 - July 2018
draft: false
tags: [Data Ingestion, ETL, Data Lake Management, Scalability, Cloud Computing (AWS), Reporting, AWS S3, AWS Glue, QuickSight, AWS Athena, Data Analysis, Insights Generation]
showToc: false
weight: 209
cover:
    image: "projects/yt_dataanalysis/yt_analysis.png"
--- 
## Description

### Project Overview:
The objective of this project is to ensure the secure management, optimization, and analysis of structured and semi-structured data from YouTube videos, with a focus on video categories and trending metrics.

### Dataset Used:
The dataset employed for this project is sourced from Kaggle and consists of CSV files containing statistical data. It offers a comprehensive record of daily trending YouTube videos over several months, with up to 200 videos trending each day across various locations. The dataset includes information such as video titles, channel titles, publication timestamps, tags, view counts, likes, dislikes, video descriptions, comment counts, and a 'category_id' field that varies by region, linked to a region-specific JSON file.

This dataset encompasses two primary data files:

- Region: Containing video information from different regions, providing insights into regional trends and statistics.
- Category: Offering information about various video categories, enabling the categorization and analysis of video content based on distinct themes and topics.

### Project Goals:
- **Data Ingestion**: Establish a mechanism for acquiring data from diverse sources.
- **ETL System**: Convert raw data into a structured format for analysis.
- **Data Lake**: Create a centralized repository for storing data collected from various sources.
- **Scalability**: Ensure the system can expand seamlessly to accommodate growing data volumes.
- **Cloud**: Leverage cloud computing, specifically AWS, to handle substantial data processing, surpassing local computer capabilities.
- **Reporting**: Develop a dashboard to derive insights and answers to predefined queries.


### Services Used:

- **Amazon S3**: A scalable object storage service that offers manufacturing scalability, data availability, security, and performance.

- **AWS IAM**: Identity and Access Management, which allows secure management of access to AWS services and resources.

- **QuickSight**: Amazon QuickSight, a cloud-based, serverless, machine learning-powered business intelligence (BI) service that offers scalability and embedding capabilities.

- **AWS Glue**: A serverless data integration service designed for data discovery, preparation, and integration, supporting analytics, machine learning, and application development.

- **AWS Lambda**: A computing service enabling code execution without the need for server management.

- **AWS Athena**: An interactive query service for Amazon S3 that doesn't require data loading; the data remains in S3 for querying.

### Architecture Diagram
![](/projects/yt_dataanalysis/architecture.jpeg)