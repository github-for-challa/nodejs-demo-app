# http://localhost:3000/

# Node.js Demo App - CI/CD Pipeline
## Task Overview
Automated code deployment using GitHub Actions with a CI/CD pipeline.

## Stack Used
- Node.js
- GitHub Actions
- Docker
- DockerHub
- 
## ⚙️ CI/CD Pipeline Setup
- Trigger: On every push to `main`
- Steps:
  - Checkout code
  - Install dependencies
  - Run dummy tests
  - Build Docker image
  - Push image to DockerHub
  - Dummy deploy step

##  Secrets Used
- `DOCKER_USERNAME`: DockerHub username
- `DOCKER_PASSWORD`: DockerHub personal access token

##  Docker Image
- Image name: `challa1/nodejs-demo-app:latest`

## ✅ Status
CI/CD pipeline tested and working successfully 
