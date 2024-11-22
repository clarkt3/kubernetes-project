# kubernetes-project
Demo Kubernetes Skills

# Kubernetes Demo Project

This project demonstrates deploying a simple containerized Python web application to a Kubernetes cluster.

## Features
- Containerized Python Flask app.
- Kubernetes Deployment for scalable application deployment.
- Kubernetes Service for external access.

## Prerequisites
- Docker
- kubectl
- Minikube (or another Kubernetes cluster)

## Steps to Run Locally
1. Build the Docker image:
   ```bash
   docker build -t hello-kubernetes .
