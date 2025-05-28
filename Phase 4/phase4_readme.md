# Phase 4: CI/CD Integration

## Objective
Automate application deployment using GitHub Actions to create a streamlined CI/CD pipeline that handles build, test, push, deploy, and rollback.

## Key Tasks
- **Pipeline Setup:** Configured `cicd-pipeline.yml` GitHub workflow to build Docker images, push to AWS ECR, and deploy to EKS.
- **Testing & Validation:** Ran image vulnerability scans, lint checks, and post-deploy health checks.
- **Rollback Mechanism:** Integrated `helm rollback` into pipeline to ensure recovery from failed deployments.
- **IAM Access Control:** Used `eksctl-accessentry.yaml` to grant required EKS access for CI runner user.

## Tools Used
- GitHub Actions
- AWS ECR & EKS
- Helm
- eksctl

## Outcome
Achieved end-to-end CI/CD automation with secure secret handling via GitHub Secrets. The system supports rollback and dynamic updates, simulating a production-grade DevOps workflow.
