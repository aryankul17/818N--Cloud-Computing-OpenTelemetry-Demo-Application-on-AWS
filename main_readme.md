# Cloud Computing Final Project – OpenTelemetry Demo Application on AWS EKS

This repository showcases the complete lifecycle of deploying, monitoring, and automating a cloud-native microservices application using AWS cloud infrastructure and DevOps tooling. The project uses the official OpenTelemetry Demo (https://github.com/open-telemetry/opentelemetry-demo) as the base application and demonstrates how to deploy it securely and observably on Amazon EKS using Helm, Prometheus, Grafana, Jaeger, and GitHub Actions.

---

## Project Breakdown

The project is divided into four distinct phases:

- **Phase 1 – Docker & Kubernetes Setup**  
  Deployed the OpenTelemetry application using Docker Compose on EC2 and later migrated it to EKS using `eksctl` and `kubectl`.

- **Phase 2 – Helm Deployment**  
  Switched from YAML-based Kubernetes deployment to Helm charts for modular, repeatable, and upgradeable deployment lifecycle.

- **Phase 3 – Observability & Alerts**  
  Integrated Prometheus, Grafana, and Jaeger into the Kubernetes cluster. Configured alert rules and email notifications to monitor pod health.

- **Phase 4 – CI/CD Integration**  
  Set up a CI/CD pipeline in GitHub Actions to automate building Docker images, pushing to AWS ECR, deploying to EKS, and rolling back on failure.

---

## Technologies & Tools

- **Cloud Platform**: AWS (EKS, EC2, IAM, VPC, S3, Route 53)
- **Containerization & Orchestration**: Docker, Kubernetes
- **Helm**: Kubernetes package manager for deployments
- **Observability**: Prometheus, Grafana, Jaeger
- **CI/CD**: GitHub Actions, AWS ECR
- **Security**: IAM roles, GitHub Secrets, private subnet EKS cluster

---

## Demo Video

A full walkthrough of the deployment and observability setup is available in the `video walkthrough.mp4` inside the `Document/` folder.

---

## Usage

1. Review the phase-wise `README.md` files for individual implementation steps.
2. Use the `manifests workflows/` folder for tested and working YAML configurations.
3. Refer to the PDF report and PowerPoint presentation in the `Document/` folder for a detailed explanation of each phase.

---

## Credits

This was developed as a group project for a University of Maryland, graduate studies masters course Cloud Computing. While it involved collaborative contributions, the repository is maintained by me for personal portfolio and learning demonstration purposes.

---



