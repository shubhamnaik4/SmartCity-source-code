# • Smart City Real-time Data Streaming Pipeline: D


## Introduction

Designed and implemented a real-time data pipeline for smart city data using IoT devices. Utilized Apache Kafka and Spark for data ingestion and processing, with AWS Glue for data transformation and Redshift for storage. Integrated AWS Athena for querying and deployed services using Docker containers for scalability and consistency.

Key components of the system include:

- **Data Ingestion & Processing**: Utilizes **Apache Kafka** and **Apache Spark** for real-time data streaming and processing. The pipeline efficiently handles data from IoT devices such as traffic sensors, environmental sensors, and cameras.
  
- **Data Transformation**: **AWS Glue** is used to perform data transformation and cleaning operations, ensuring the data is in the right format for analysis and querying.
  
- **Storage**: The processed data is stored in **AWS Redshift**, a fully managed data warehouse, providing efficient and scalable storage for large datasets.

- **Data Querying**: **AWS Athena** is integrated for interactive querying of the data stored in Amazon S3, enabling fast insights into the smart city’s operations.

- **Scalability & Deployment**: The entire pipeline and associated services are containerized using **Docker**, ensuring easy scalability, portability, and consistent execution across environments.

This project demonstrates how modern cloud and data technologies can work together to build scalable, real-time data processing systems, and can be used to monitor and improve various aspects of a smart city.


