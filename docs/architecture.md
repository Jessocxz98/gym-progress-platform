# Architecture

## Overview
The Gym Progress API is deployed to AWS using a production-style DevOps platform.

## High Level Flow
1. Developer pushes code
2. GitHub Actions builds Docker image
3. Image pushed to Amazon ECR
4. GitOps repository updated with new image tag
5. ArgoCD detects change
6. Application deployed to EKS