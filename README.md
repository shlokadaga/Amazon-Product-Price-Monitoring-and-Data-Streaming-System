# Amazon-Product-Price-Monitoring-and-Data-Streaming-System
This project is an automated price tracking system that scrapes product details from e-commerce websites (like Amazon) and streams the data in real time using Kafka. The extracted data is stored in Cassandra for efficient retrieval and analysis.

# Flow
1. Uses Selenium to extract product details (name, price, etc.) from e-commerce websites.
2. Implements Apache Kafka for continuous data streaming.
3. Utilizes PySpark to process and analyze large volumes of collected data.
4. Uses Apache Cassandra for scalable and reliable data storage.
5. Dockerized components ensure easy deployment across different environments.
6. Enables real-time data tracking for business insights.
