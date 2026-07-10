# 🚀 End-to-End CI/CD Pipeline for the vProfile Application using Jenkins, Docker & AWS ECS



A production-style CI/CD pipeline that automates the complete software delivery lifecycle of the **vProfile** application—from source code to deployment on **Amazon ECS**. This project demonstrates modern DevOps practices by integrating continuous integration, code quality analysis, containerization, image management, and cloud-native deployment.

---

# 📖 Overview

This project implements a fully automated CI/CD pipeline that continuously builds, tests, analyzes, containerizes, and deploys the **vProfile** application to **Amazon ECS**.

The objective was to automate the software delivery process while improving deployment reliability, code quality, and release consistency.

---

# 🏗️ Pipeline Architecture

<p align="center">
<img src="screenshots/Screenshot 2026-04-09 093207.png" width="1000">
</p>

---

# ☁️ AWS Services Used

- Amazon ECS
- Amazon ECR
- Amazon IAM
- Amazon EC2 (Jenkins Host)
- Amazon VPC

---

# ⚙️ Technology Stack

| Category | Technologies |
|-----------|--------------|
| CI/CD | Jenkins |
| Build Tool | Apache Maven |
| Code Quality | Checkstyle, SonarQube |
| Containerization | Docker |
| Container Registry | Amazon ECR |
| Container Orchestration | Amazon ECS |
| Version Control | GitHub |
| Language | Java |
| Cloud | AWS |

---

# 🔄 Pipeline Workflow

```
Developer
     │
     ▼
 GitHub Repository
     │
     ▼
 Jenkins Pipeline
     │
     ▼
 Maven Build
     │
     ▼
 Unit Testing
     │
     ▼
 Checkstyle Analysis
     │
     ▼
 SonarQube Analysis
     │
     ▼
 Docker Image Build
     │
     ▼
 Push Image to Amazon ECR
     │
     ▼
 Deploy to Amazon ECS
     │
     ▼
 Running vProfile Application
```

---

# ⚙️ Pipeline Stages

## 📥 Source Code

- Source code hosted on GitHub
- Jenkins automatically triggers builds from repository changes

---

## 🔨 Build

- Maven compiles the application
- Generates deployable WAR artifacts
- Resolves project dependencies

---

## 🧪 Testing

- Executes automated unit tests
- Ensures application stability before deployment

---

## ✅ Code Quality

Static code analysis using

- Checkstyle
- SonarQube

Helps identify

- Code smells
- Bugs
- Maintainability issues
- Technical debt

---

## 🐳 Containerization

- Multi-stage Docker build
- Optimized production-ready Docker image
- Reduced image size
- Improved deployment consistency

---

## 📦 Container Registry

Docker images are securely pushed to

- Amazon Elastic Container Registry (ECR)

Providing centralized image management for deployments.

---

## ☁️ Deployment

Application is automatically deployed to

- Amazon Elastic Container Service (ECS)

Benefits include

- Container orchestration
- Simplified deployments
- Scalable application hosting
- Rolling updates

---

# 🚀 Key Features

- Fully automated CI/CD pipeline
- Continuous Integration with Jenkins
- Automated Maven builds
- Unit Testing
- Checkstyle validation
- SonarQube code quality analysis
- Docker multi-stage builds
- Amazon ECR image management
- Amazon ECS deployment
- Production-style DevOps workflow

---

# 📈 Key Learning Outcomes

Through this project, I gained hands-on experience with

- Jenkins Pipeline Automation
- Continuous Integration
- Continuous Deployment
- Docker Image Optimization
- Amazon ECS
- Amazon ECR
- Code Quality Analysis
- SonarQube Integration
- AWS IAM Configuration
- Cloud-native Application Deployment
- Production DevOps Workflows

---

# 🛠️ Challenges Faced

- Jenkins pipeline debugging
- SonarQube configuration
- Docker build optimization
- ECS task definition updates
- IAM permission management
- Container deployment failures
- Service health checks
- Environment variable configuration

---



# 🔮 Future Improvements

- GitHub Webhook Integration
- Blue/Green Deployments
- Canary Deployments
- Infrastructure as Code with Terraform
- GitOps using Argo CD
- Kubernetes Deployment on Amazon EKS
- Automated Security Scanning with Trivy
- Slack Notifications

---

# 👨‍💻 Author

**Eranga Kavishanka**

- AWS Certified Cloud Practitioner (AWS CCP)
- Kubernetes and Cloud Native Associate (KCNA)
- Software Engineering Undergraduate
- DevOps | Cloud | Site Reliability Engineering (SRE)

---

## ⭐ If you found this project useful, consider giving it a Star!
