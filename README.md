# Apache Kafka Microservices Project

This project consists of two Spring Boot applications demonstrating Apache Kafka's usage. The two microservices interact using Kafka to showcase event-driven architecture.

## Applications Overview

### 1. **Event Producer Service**
- Generates and sends real-time event messages to a Kafka topic.
- Simulates a **Delivery Boy application** sending live location updates.
- Uses **Spring Boot** and **Kafka Producer API**.

### 2. **Event Consumer Service**
- Listens to Kafka topics and processes received messages.
- Simulates a **Customer application** receiving live delivery updates.
- Uses **Spring Boot** and **Kafka Consumer API**.

## Project Structure
```
├── producer-service
│   ├── src/main/java/com/example/producer
│   │   ├── ProducerApplication.java
│   │   ├── KafkaProducerConfig.java
│   │   ├── LocationProducer.java
│   ├── resources/application.yml
│
├── consumer-service
│   ├── src/main/java/com/example/consumer
│   │   ├── ConsumerApplication.java
│   │   ├── KafkaConsumerConfig.java
│   │   ├── LocationConsumer.java
│   ├── resources/application.yml
```

## Technologies Used
- **Java 17+**
- **Spring Boot**
- **Apache Kafka**
- **Spring Kafka**
- **Docker (Optional for Kafka Setup)**

