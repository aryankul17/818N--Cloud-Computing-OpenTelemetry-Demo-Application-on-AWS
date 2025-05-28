# Phase 1: Environment and Initial Application Setup

## Objective
Set up a basic infrastructure to host the OpenTelemetry demo application using Docker and Kubernetes. Validate application functionality and lay the foundation for scalable deployment on AWS.

## Key Tasks
- **Docker Deployment (Part 1):** Deployed the application using Docker Compose on an EC2 instance to verify microservices interaction and health.
- **Kubernetes Setup (Part 2):** Created an Amazon EKS cluster using `eksctl`, connected via `kubectl`, and deployed the application using raw YAML manifests to validate Kubernetes readiness.

## Tools Used
- Docker, Docker Compose
- AWS EC2
- eksctl, kubectl
- Amazon EKS

## Outcome
We successfully validated the application using Docker locally and transitioned to a Kubernetes-managed deployment, setting up core services and confirming access to service endpoints in the cluster.
