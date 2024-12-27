# Kubernetes CI/CD Pipeline with Docker and Jenkins 🚀

## 📜 Overview
This project demonstrates a complete **CI/CD pipeline** for deploying a containerized Python application to a Kubernetes cluster using **Jenkins**, **Docker**, and **Kubernetes**. The pipeline automates the steps of building a Docker image, pushing it to Docker Hub, and deploying it to a Kubernetes cluster.

---

## 🛠️ Key Features
- **Dockerized Application**: A Python Flask app running in a Docker container.
- **Jenkins Pipeline**: Automates building, pushing, and deploying the application.
- **Kubernetes Deployment**: Manages the application scaling and service exposure.
- **Continuous Deployment**: Automatically deploys the latest application changes.

---

## 📂 Project Structure
```plaintext
k8s-docker-pipeline/
├── app/
│   ├── app.py           # Python Flask application
│   └── Dockerfile       # Dockerfile for containerizing the app
├── k8s/
│   ├── deployment.yaml  # Kubernetes deployment definition
│   └── service.yaml     # Kubernetes service definition
├── Jenkinsfile          # CI/CD pipeline definition
└── README.md            # Project documentation

