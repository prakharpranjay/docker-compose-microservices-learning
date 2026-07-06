# Microservices Demo Deployment using Docker Compose (Sock Shop)

## Project Overview
This project demonstrates deployment of a cloud-native e-commerce microservices application (Sock Shop) on a local Ubuntu machine using Docker Compose. The objective was to understand containerization, service networking, orchestration, troubleshooting, and deployment of multiple independent services.

## Tech Stack
- Docker
- Docker Compose
- Ubuntu Linux
- Git & GitHub
- Traefik Edge Router
- RabbitMQ
- MySQL
- Microservices Architecture

## Architecture
The application consists of multiple independently running services:
- Frontend
- Catalogue Service
- User Service
- Cart Service
- Orders Service
- Shipping Service
- Payment Service
- Queue Master
- RabbitMQ
- MySQL Databases
- Edge Router (Traefik)

## Features
- Multi-container deployment
- Service isolation
- Internal Docker networking
- Reverse proxy using Traefik
- Database-backed services
- Browser-accessible frontend

## Challenges Solved
- Resolved Docker Compose configuration issues.
- Fixed port conflicts (8080 already in use).
- Modified Edge Router port mapping.
- Verified container networking.
- Successfully launched all required containers.

## Verification
Commands used:

```bash
docker compose up -d
docker ps
docker logs <container>
```

Application accessed successfully from browser.

## Skills Demonstrated
- Docker Containerization
- Docker Compose
- Linux CLI
- Networking & Port Mapping
- Microservices Deployment
- Debugging Containers
- Git Version Control

## Resume Description

**Dockerized Microservices Deployment | DevOps Project**

- Deployed a production-style microservices e-commerce application locally using Docker Compose.
- Managed 10+ interconnected services including frontend, backend APIs, databases, messaging, and reverse proxy.
- Configured Docker networking and resolved runtime issues including port conflicts.
- Validated inter-service communication and application availability through browser testing.
- Gained practical experience with container orchestration, Linux, and DevOps workflows.

## Future Improvements
- Kubernetes deployment
- Jenkins CI/CD pipeline
- Monitoring using Prometheus & Grafana
- Image scanning using Trivy
- Deployment through Helm
