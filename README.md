# BookMyShow DevSecOps Deployment Project

## Project Overview

This project demonstrates the end-to-end DevSecOps deployment of the BookMyShow application using modern CI/CD and security practices.

The objective of this project is to automate application build, testing, security scanning, containerization, and Kubernetes deployment using industry-standard DevSecOps tools.

---

## Architecture Flow

Developer
→ GitHub
→ Jenkins Pipeline
→ SonarQube Code Analysis
→ Trivy Security Scan
→ Docker Image Build
→ DockerHub Push
→ Kubernetes Deployment
→ Application Access

---

## Technology Stack

- Git & GitHub
- Jenkins
- SonarQube
- Trivy
- Docker
- DockerHub
- Kubernetes
- Linux

---

## CI/CD Pipeline Stages

### Stage 1: Source Code Management
Application source code is stored in GitHub.

### Stage 2: Continuous Integration
Jenkins automatically triggers the pipeline after code changes.

### Stage 3: Code Quality Analysis
SonarQube performs static code analysis and quality checks.

### Stage 4: Security Scanning
Trivy scans dependencies and container images for vulnerabilities.

### Stage 5: Containerization
Docker creates application images for deployment.

### Stage 6: Image Registry
Docker images are pushed to DockerHub.

### Stage 7: Kubernetes Deployment
Application is deployed and managed using Kubernetes.

---

## Project Structure

```text
bookmyshow-devops-shudhanshu
│
├── README.md
├── docs
│   ├── project-overview.md
│   ├── architecture
│   │   └── README.md
│   └── screenshot
│       └── README.md
```

---

## Features

- Automated CI/CD Pipeline
- Static Code Analysis
- Vulnerability Scanning
- Docker Containerization
- Kubernetes Deployment
- DevSecOps Best Practices

---

## Documentation

### Project Overview
See:

`docs/project-overview.md`

### Architecture Documentation
See:

`docs/architecture/README.md`

### Deployment Screenshots
See:

`docs/screenshot/README.md`

---

## Future Enhancements

- Monitoring using Prometheus
- Grafana Dashboard Integration
- ArgoCD GitOps Deployment
- Automated Testing Integration

---

## Author

**Shudhanshu Dwivedi**

DevOps Engineer

AWS | Docker | Kubernetes | Jenkins | Terraform | Linux

---
