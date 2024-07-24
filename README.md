# Wiscow Project

This is a simple Python web application using Flask, Docker, Jenkins, and Kubernetes.

## Setup

1. Clone the repository
2. Build and run the Docker container
3. Deploy to Kubernetes

## Build and Run Docker Container

```sh
docker build -t wiscow .
docker run -p 5000:5000 wiscow
