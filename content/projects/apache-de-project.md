---
title: "Real-time Data Streaming Pipeline with Apache Stack"
description: "Built an efficient end-to-end data engineering pipeline with Apache technologies for seamless data management"
# dateString: Jan 2021 - May 2021
draft: false
tags: [Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, Cassandra, PostgreSQL, Docker]
showToc: false
weight: 203
cover:
    image: "projects/apache-de-project/Designer.png"
--- 
<!-- ### 🔗 [Colab Notebook](https://colab.research.google.com/drive/1Q553uslYW3Ho6P1G46SOEDxOS_VmHXfJ) -->

## Description

### Introduction
This project acts as a thorough roadmap for constructing a holistic data engineering pipeline. It encompasses every phase, from data intake to processing, culminating in storage, leveraging a robust technology stack comprising Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra. The entire infrastructure is containerized through Docker, ensuring straightforward deployment and scalability. 

### Key Components:

- Data Ingestion
- Data Processing
- Data Storage
### Tech Stack:
- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- Docker

### System Architecture
- Explain how data flows from data ingestion through processing to storage.
- Describe how each technology in the stack plays a role in this architecture.
![Attention Mechanism](/projects/apache-de-project/Dataarchitecture.png)

The project is designed with the following components:

- **Data Source**: We use randomuser.me API to generate random user data for our pipeline.
- **Apache Airflow**: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.
- **Apache Kafka and Zookeeper**: Used for streaming data from PostgreSQL to the processing engine.
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.
- **Apache Spark**: For data processing with its master and worker nodes.
- **Cassandra**: Where the processed data will be stored.

### Learning Outcomes:

- Setting up data pipelines with Apache Airflow
- Real-time data streaming with Apache Kafka
- Distributed synchronization with Apache Zookeeper
- Data processing techniques with Apache Spark
- Data storage solutions with Cassandra and PostgreSQL
- Containerizing the data engineering setup with Docker


