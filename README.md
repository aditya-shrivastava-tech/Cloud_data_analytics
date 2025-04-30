# Cloud_data_analytics
This project showcases an end-to-end data engineering pipeline designed to ingest, process, and analyze live stock market data streams using a robust set of modern technologies.

# Key Components:

* Stock Market App Simulation (Python SDK): A Python-based application that simulates the generation of real-time stock market data.
* Producer: This component, implemented in Python, ingests the simulated stock data and publishes it to the Kafka cluster.
* Apache Kafka (on Amazon EC2): A distributed streaming platform that acts as a central nervous system for our real-time data. Running on Amazon EC2 provides flexibility and control.
* Consumer: This component subscribes to the Kafka topics and processes the incoming stock market data.
* Amazon S3 (Simple Storage Service): A scalable object storage service used to persist the processed data.
* AWS Glue: A fully managed ETL (Extract, Transform, Load) service.
1) Glue Crawler: Automatically discovers the schema of the data stored in Amazon S3.
2) Glue Data Catalog: A central metadata repository containing schema information for the data.
* Amazon Athena: An interactive query service that enables querying data directly in Amazon S3 using standard SQL.


