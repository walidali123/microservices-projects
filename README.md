# Microservices Project

This project demonstrates a microservices architecture using Docker Compose. It includes multiple services, each running in its own container, including a client application, an API service, a web API, and databases (MongoDB and MySQL). The services are orchestrated using Docker Compose.

# Project Structure

```plaintext
.
├── client/          # Frontend Angular application
├── nodeapi/         # Node.js API service
├── javaapi/         # Java-based web API service
├── nginx/           # Nginx configuration
│   └── default.conf # Nginx reverse proxy configuration
└── docker-compose.yml

## Prerequisites
Before you begin, ensure you have the following installed on your machine:

Docker
Docker Compose

# Services Overview
