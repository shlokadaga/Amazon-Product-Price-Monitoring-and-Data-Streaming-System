# Amazon-Product-Price-Monitoring-and-Data-Streaming-System
This project is an automated price tracking system that scrapes product details from e-commerce websites (like Amazon) and streams the data in real time using Kafka. The extracted data is stored in Cassandra for efficient retrieval and analysis.

# Flow
1. Automated Web Scraping: Uses Selenium to extract product details (name, price, etc.) from e-commerce websites.
2. Real-Time Data Streaming: Implements Apache Kafka for continuous data streaming.
3. Distributed Storage: Uses Apache Cassandra for scalable and reliable data storage.
4. Scalability & Portability: Dockerized components ensure easy deployment across different environments.
5. Data Monitoring & Analysis: Enables real-time data tracking for business insights.
