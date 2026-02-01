# Kubernetes Network Policy Visualizer

- Student Name: Deep Kiran Kaur
- Registration No: 23FE10CSE00307
- Course: CSE3253 DevOps [PE6]  
- Semester: VI (2025-2026)  
- Project Type: Kubernetes & Security  
- Difficulty: Intermediate  

---

## Project Overview

### Problem Statement
Kubernetes Network Policies are difficult to understand by reading YAML files directly.  
This project provides a visualization tool that converts Kubernetes NetworkPolicy YAML files into an interactive network graph showing allowed and blocked traffic between pods.

### Objectives
- Parse Kubernetes NetworkPolicy YAML files
- Identify allowed and denied pod-to-pod communications
- Represent network rules in a visual graph format
- Containerize the application using Docker
- Deploy the application using Kubernetes manifests
- Implement CI/CD pipeline for automated build and testing

### Key Features
- Supports Kubernetes NetworkPolicy YAML input
- Displays pod communication as a graph
- Highlights allowed and blocked connections
- Web-based visualization interface
- Dockerized application
- Kubernetes deployment support
- CI/CD pipeline integration

---

## Technology Stack

### Core Technologies
- Programming Language: Python
- Framework: Flask
- YAML Parsing: PyYAML
- Graph Processing: NetworkX
- Frontend Visualization: D3.js / Graphviz

### DevOps Tools
- Version Control: Git & GitHub
- CI/CD: GitHub Actions
- Containerization: Docker
- Orchestration: Kubernetes
- Monitoring: Prometheus / Nagios (optional)

---

## Getting Started

### Prerequisites
- Python 3.8+
- Docker
- Git
- kubectl (optional for Kubernetes deployment)

## Project Structure
devops-project-kubernetes-network-policy-visualizer/
│
├── README.md                           Main project documentation
├── .gitignore                          Git ignore file
├── LICENSE                             MIT or Apache 2.0
│
├── src/                                Source code
│   ├── main/                           Main implementation
│   │   ├── [language-specific-structure]
│   │   └── config/                     Configuration files
│   ├── test/                           Test files
│   └── scripts/                        Utility scripts
│
├── docs/                               Documentation
│   ├── project-plan.md                 Project plan and timeline
│   ├── design-document.md              Technical design document
│   ├── user-guide.md                   User guide
│   ├── api-documentation.md            API documentation (if applicable)
│   └── screenshots/                    Project screenshots
│
├── infrastructure/                     Infrastructure as Code
│   ├── docker/                         Docker configurations
│   │   ├── Dockerfile
│   │   └── docker-compose.yml
│   ├── kubernetes/                     K8s manifests
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   │   └── configmap.yaml
│   ├── puppet/                         Puppet manifests
│   └── terraform/                      Terraform scripts
│
├── pipelines/                          CI/CD Pipeline definitions
│   ├── Jenkinsfile                     Jenkins pipeline
│   ├── .github/workflows/              GitHub Actions
│   │   └── ci-cd.yml
│   └── gitlab-ci.yml                   GitLab CI
│
├── tests/                              Test suites
│   ├── unit/                           Unit tests
│   ├── integration/                    Integration tests
│   ├── selenium/                       Selenium tests
│   └── test-data/                      Test data
│
├── monitoring/                         Monitoring configurations
│   ├── nagios/                         Nagios configurations
│   ├── alerts/                         Alert rules
│   └── dashboards/                     Monitoring dashboards
│
├── presentations/                      Presentation materials
│   ├── project-presentation.pptx/pdf
│   └── demo-script.md
│
└── deliverables/                       Final deliverables
    ├── demo-video.mp4                  5-10 minute demo
    ├── final-report.pdf                Final report
    └── assessment/                     Self-assessment
 --- 
## Configuration

### Environment Variables
Create a .env file in the root directory:

env
APP_ENV=development
DB_HOST=localhost
DB_PORT=5432
API_KEY=your_api_key_here

---
## CI/CD Pipeline

### Pipeline Stages
1. Code Quality Check
2. Build Application
3. Run Unit Tests
4. Docker Image Build
5. Security Scan
6. Deployment (Staging/Production)

---

## Testing

- Unit Tests: pytest
- Integration Tests: API testing using requests
