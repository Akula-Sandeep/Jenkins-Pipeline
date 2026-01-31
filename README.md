CI/CD Pipeline with Jenkins, SonarQube, Docker, Helm, Argo CD & Kubernetes
📌 Project Overview

This project demonstrates an end-to-end DevOps CI/CD workflow for deploying a Java Spring Boot application into a Kubernetes environment.

The goal of this project was to gain hands-on experience integrating multiple DevOps tools and understanding how modern cloud-native application delivery works in real-world environments.

🛠 Tools & Technologies Used

Jenkins – CI/CD pipeline automation

Maven – Application build & dependency management

SonarQube – Static code quality analysis

Docker – Application containerization

Helm – Kubernetes package management

Argo CD – GitOps-based continuous deployment

Kubernetes – Container orchestration platform

Git & GitHub – Source code and deployment manifest version control

⚙️ CI/CD Workflow

Code Commit → Application source code pushed to GitHub

Jenkins Pipeline Triggered

Builds the application using Maven

Runs SonarQube code quality scan

Docker Image Build

Application packaged into a Docker container

Image Push

Docker image pushed to container registry

Helm Deployment Files Updated

Kubernetes manifests managed using Helm charts

Argo CD Sync

Argo CD detects changes in Git

Automatically deploys the application to Kubernetes

☸️ Kubernetes Deployment Features

Deployment and Service configurations using YAML

Replica scaling for high availability

Rolling updates for zero downtime

Health checks using liveness and readiness probes

🎯 Learning Outcomes

Through this project, I learned:

How CI and CD stages work together in a pipeline

Integrating code quality checks into automated workflows

Containerizing applications for consistent environments

Managing Kubernetes deployments using Helm

Implementing GitOps principles using Argo CD