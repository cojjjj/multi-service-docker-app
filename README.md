# Multi-Service Docker Application

This project demonstrates an advanced Docker deployment using multiple interconnected services.

## Services

* React Frontend
* Node.js Express API
* MongoDB Database
* Redis Cache
* Nginx Reverse Proxy

## Features

* Docker Compose
* Multi-stage Builds
* Custom Dockerfiles
* Docker Networks
* Docker Volumes
* Docker Secrets
* Health Checks
* Logging Support
* Image Optimization

## Running the Project

```bash
docker compose up -d
```

## Architecture

Client
|
v
Nginx
|
+--> React Frontend
|
+--> Node API
|
+--> MongoDB
|
+--> Redis

## Project URL

https://roadmap.sh/projects/multiservice-docker

## Concepts Demonstrated

* Container Orchestration
* Docker Networking
* Persistent Storage
* Secrets Management
* Reverse Proxying
* Microservices Architecture
* DevOps Fundamentals
