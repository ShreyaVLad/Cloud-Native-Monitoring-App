# Cloud Monitoring App

**Cloud Monitoring App** is a cloud-native project to monitor EC2 instances in real time. It tracks system metrics like CPU, memory, disk, and network usage using **Python, Flask, and psutil**.

The app is containerized with **Docker**, pushed to **AWS ECR**, and deployed on **AWS EKS** with Kubernetes for scalability and reliability.

## Features
- Run locally with Flask
- Dockerized for easy deployment
- Push Docker images to AWS ECR
- Deploy and manage on AWS EKS using Kubernetes

## Prerequisites
- AWS account with CLI access
- Python 3 installed
- Docker and kubectl installed
- Code editor (VS Code)

## Quick Start


### 1. Clone the repository
```bash
git clone <repository_url>
cd <repository_folder>

### 2. Install dependencies
```bash
cd pip3 install flask psutil plotly boto3 kubernetes

### 3. Run locally
cd python3 app.py



