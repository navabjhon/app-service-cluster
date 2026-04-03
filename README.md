# Overview
App Service Cluster is a Kubernetes-based infrastructure setup for orchestrating a multi-service application.
It leverages containerization and cloud-native principles to ensure scalability, reliability, and efficient resource utilization.

This repository contains all the Kubernetes manifests required to deploy, manage, and scale the application services seamlessly.

## Architecture
The system follows a distributed, microservices-friendly architecture:

- Client Requests → Routed via NGINX
- Application Layer → Powered by Apache Tomcat (JDK 21)
- Database Layer → Managed by MySQL
- Caching Layer → Optimized with Memcached
- Messaging Layer → Handled by RabbitMQ

## Technologies Used
- Apache Tomcat (10 with JDK 21) – Hosts the Java-based application services
- MySQL (8.0.33) – Relational database for persistent storage
- NGINX – Acts as a reverse proxy and load balancer
- Memcached – In-memory caching layer to improve performance
- RabbitMQ – Message broker for asynchronous communication between services

## Getting Started
### Prerequisites
- Kubernetes cluster (Minikube / EKS / GKE / AKS)
- kubectl CLI installed
- Docker (for building images)

## Features
- ✅ Scalable microservices architecture
- ✅ Containerized deployments
- ✅ Load balancing with NGINX
- ✅ Caching for performance optimization
- ✅ Asynchronous messaging with RabbitMQ
- ✅ Kubernetes-native configuration

## Contributing

### Contributions are welcome!

- Fork the repo
- Create a feature branch
- Commit your changes
- Open a Pull Request

## Author

Maintained by Navab

Feel free to connect and contribute!
