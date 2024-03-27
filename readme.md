# Stock Market Real-Time Data Pipeline with Apache Kafka & Cassandra

This project focuses on retrieving real-time stock market data using Python and storing it in a Cassandra database via Apache Kafka. The data is processed with Apache Kafka on AWS EC2 and then stored in a local Cassandra server.

## Key Features

- Data Engineering: Implement a data pipeline for processing real-time data streams.
- Tech Stack: Utilize Python, AWS EC2, Apache Kafka, and CassandraDB.
- Error Handling: Handle common errors and provide troubleshooting tips for a smooth workflow.
- Future Enhancements: Incorporate data visualization, machine learning predictions, real-time alerts, and scalability.

## Architecture

![Pipeline Architecture](https://imgur.com/1DBe05W.png)

## Environment Setup


### Prerequisites

Make sure you have the following prerequisites installed:

- Python with `kafka-python` & `cassandra-driver` packages
- AWS CLI
- Java
- Apache Kafka
- Cassandra

## Project Implementation

Follow these steps to implement the project:

1. Launch an EC2 instance and install Apache Kafka.
2. Create a Python script to retrieve real-time stock market data.
3. Use Apache Kafka to produce the data to a topic.
4. Create a Python script to consume the topic data and store it in CassandraDB.

## Execution

Follow these steps to execute the project:

1. Launch an EC2 instance and set up Apache Kafka.
2. Start the Apache Kafka producer to produce data to a topic.
3. Run the Python script to send real-time stock market data.
4. Start the Python consumer script to consume and store data in CassandraDB.
5. Use SQL queries to retrieve the data stored in CassandraDB.


## Future Enhancements

Consider these future enhancements for the project:

- Adding a data visualization layer using tools such as Matplotlib or Seaborn to visualize the stock market data stored in CassandraDB.
- Incorporating a machine learning model to predict stock prices based on the stored data.
- Implementing a real-time alert system to notify users of significant changes in the stock market.
- Scaling the pipeline to handle larger amounts of data by adding more EC2 instances and increasing the size of CassandraDB clusters.

## Conclusion

This project demonstrates the use of Python, AWS, Apache Kafka, Cassandra, and SQL to retrieve and store real-time stock market data. The pipeline created in this project can be adapted to process and store any real-time data stream efficiently.
