# Kafka_Stock_Market_AWS

## Project Diagram
![Project Diagram](https://github.com/Oussamahajoui/Kafka_Stock_Market_AWS/blob/main/Project_diagram.png)

## Goal & Context:
* **TL,DR:** Build a real-time stock market data streaming application using Kafka on AWS.
* **Full story:** This project focuses on setting up a Kafka cluster on Amazon Web Services (AWS) to handle real-time stock market data. The application will utilize producers to fetch and publish stock market data, and consumers to process and analyze the data. Additionally, there will be data storage and analysis components integrated to provide meaningful insights.

## Components and Steps:
1. **Setting up Kafka Cluster on AWS:**
   - Provisioning Kafka brokers, Zookeeper, and related components on AWS.
   - Configuring security settings and network configurations.

2. **Implementing Producers and Consumers:**
   - Developing producers to fetch stock market data from reliable sources.
   - Implementing consumers for processing and analysis.

3. **Simulating Stock Market Data using Python and a Free Dataset:**
   - Creating a simulated stream of stock market data using Python.
   - Utilizing a free dataset to generate realistic stock market scenarios.

4. **Utilize Amazon S3 for Storage:**
   - Implementing a storage solution using Amazon S3 to store both raw and processed data.
   - Setting up appropriate access permissions and lifecycle policies.

5. **Leverage AWS Glue (Crawlers and Glue Data Catalog) for Data Cataloging:**
   - Utilizing AWS Glue Crawlers to automatically discover and catalog metadata about your data sources.
   - Leveraging the Glue Data Catalog to maintain a centralized metadata repository.

6. **Utilize Athena for Data Analysis:**
   - Writing SQL queries in Athena to perform data analysis on the cataloged data.
   - Extracting valuable insights and patterns from the stock market data.

## End Result:
The final product will be a robust, real-time stock market data streaming application hosted on AWS. It will provide a reliable platform for processing and analyzing stock market data, making it a valuable tool for traders, analysts, and financial professionals.

## Future Improvements:
* Implementing advanced analytics and machine learning models for stock market predictions.
* Implementing additional security measures and compliance with industry standards.

---


###### Made by Oussama Hajoui
