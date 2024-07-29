ShopBoot is a simple e-commerce application where customers can order products. The application is developed with Microservices Architechture using SpringBoot and Spring Cloud and deploy them using Docker and Kubernetes. 
The application contains the following services:
* Product Service - create and view products. 
* Order Service -  user can order products
* Inventory Service -  order service checks with the invetory service if the product is in stock or not before submitting the order
* Notification Service - send notifications to user once the order is placed. 

Softwares used:
For Asynchronous Communication: Message Queues: RabbitMQ and Kafka
Spring Cloud: API Gateway - acts an entry point for all the client requests and send requests to different services ,Eureka, ConfigServer
The application is secured using Authorization server called as KeyCloak.
Distributed Tracing: Zipkin
Elastic Search, Kibana and Logstash: Logstash ingests, transforms, and sends the data to the right destination. Elasticsearch indexes, analyzes, and searches the ingested data. Kibana visualizes the results of the analysis.

