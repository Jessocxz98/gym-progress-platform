# gym-progress-platform
A production-style DevOps platform for deploying the Gym Progress API on AWS.

## Purpose
This repo demonstrates platform engineering practices including:
- Infrastructure as Code with Terraform
- Kubernetes deployments on Amazon EKS
- GitOps with ArgoCD
- Application packaging with Helm
- CI/CD with GitHub Actions
- Secrets management with AWS Secrets Manager
- Observability with Prometheus, Grafana and Loki
- Multi-environment deployment workflows

## Repository Structure
```text
terraform/    Infrastructure as Code
helm/         Helm chart for the Gym Progress API
argocd/       ArgoCD application definitions
environments/ Environment-specific Helm values
docs/         Architecture and design notes
