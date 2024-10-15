# Project Overview

This repository contains multiple projects related to Spring Boot, Kubernetes, Docker, Terraform, and other DevOps tools. Below are the key sections and technologies used in the projects.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Repository Structure](#repository-structure)
- [Spring Petclinic](#spring-petclinic)
- [Kubernetes Setup](#kubernetes-setup)
- [EKS Cluster and Node Groups](#eks-cluster-and-node-groups)
- [ArgoCD for CI/CD](#argocd-for-cicd)
- [Prometheus Monitoring](#prometheus-monitoring)
- [Jenkins Pipeline](#jenkins-pipeline)
- [MongoDB and MERN Stack](#mongodb-and-mern-stack)
- [Docker Best Practices](#docker-best-practices)
- [Business Plan](#business-plan)

## Technologies Used
- **Spring Boot** for backend development
- **Kubernetes** for container orchestration (manifests for Deployment, StatefulSet, Ingress, Services)
- **Amazon EKS** for managing Kubernetes clusters on AWS
- **ArgoCD** for GitOps-based CI/CD pipelines
- **Jenkins** for CI/CD automation
- **Prometheus** for monitoring and alerting
- **MongoDB** for database management
- **Docker** for containerizing applications
- **Terraform** for infrastructure as code on AWS
- **Helm** for managing Kubernetes resources
- **GCP** as an alternative cloud platform (SSM-like services)
- **Nexus** for managing Maven snapshots and artifacts
- **SonarQube** for code quality checks and quality gates
- **Ansible** for DevOps automation
- **Python** for DevOps-related scripting

## Repository Structure
The repository is organized into different directories for each project:

```plaintext
.
├── spring-petclinic/         # Spring Petclinic application
├── kubernetes/               # Kubernetes manifests (dev, prod namespaces)
├── terraform/                # Terraform scripts for AWS resources
├── jenkins/                  # Jenkins pipeline and job configurations
├── docker-compose/           # Docker Compose setups for various projects
├── mongodb/                  # MongoDB configurations and scripts
└── prom-monitoring/          # Prometheus alerts and monitoring setup
