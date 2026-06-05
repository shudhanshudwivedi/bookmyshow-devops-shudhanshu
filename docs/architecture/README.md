# BookMyShow DevSecOps Architecture

## Architecture Flow

Developer
↓
GitHub
↓
Jenkins Pipeline
↓
SonarQube Analysis
↓
Trivy Security Scan
↓
Docker Build
↓
DockerHub Push
↓
Kubernetes Deployment
↓
Application Access

## Components

### GitHub
Source code repository.

### Jenkins
CI/CD automation server.

### SonarQube
Code quality analysis.

### Trivy
Container vulnerability scanning.

### Docker
Application containerization.

### Kubernetes
Container orchestration platform.

### DockerHub
Container image registry.

## Deployment Outcome

Automated secure deployment pipeline for BookMyShow application.
