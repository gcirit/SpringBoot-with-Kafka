# SpringBoot-with-Kafka

Coding and implementing Kafka Clients using SpringBoot with Producer/Consumer API.

# Project Progression So Far:

# Setting up Kafka Clusters and Components

Kafka Zookeeper and Broker clusters are set up

Topics, Produce and Consume messages are created using CLI

Consumer Offsets are created

Consumer Groups are created

3 Kafka Brokers are created

Fault Tolerance and Robustness features are added

# Building library-event-producer API

Base Project set up for Library Event Kafka Producer using Spring Initialzr

Library Event Domain is built

POST endpoint created

KafkaTemplates are configured using SpringBootProfiles with application.yml file

LibraryEvents are produces with KafkaTemplate

KafkaRecord with Headers are sent using KafkaTemplates

NEW, UPDATE LibraryEvent Types (Enums) are added

Integration Testing using JUnit5 is added

Unit Testing using JUnit5 is added

# Building library-event-consumer API

Base Project set up for Library Event Kafka Consumer using Spring Initialzr

KafkaTemplates are configured using SpringBootProfiles with application.yml file

Kafka Consumer features with @ KafkaListener Annotation are built

Consumer Offset Management added

H2 In-Memory DB integrated

LibraryEvent and Book Entities are created

Service Layer is built

Integration Testing added using Embedded Kafka

# Additional Features 

Error Handling, Retry and Recovery features added for Kafka Consumer

Error Handling, Retry and Recovery features added for Kafka Producer

# To:Do

Add SSL Security for Kafka Cluster

Access SSL Secured Kafka Cluster using Spring Boot











=======
>>>>>>> e66e3c877e7a3a937a6fb37af255b69b41a482d8
