# Movie Picture Pipeline

This project implements CI/CD pipelines for the frontend and backend applications using GitHub Actions.
The pipelines run linting, testing, Docker image builds, and Kubernetes deployments.
The frontend application is located in `starter/frontend`.
The backend application is located in `starter/backend`.
Frontend and backend images are pushed to Amazon ECR.
Applications are deployed to Amazon EKS using Kubernetes manifests and Kustomize.
Frontend CI runs on pull requests to `main`.
Backend CI runs on pull requests to `main`.
Frontend CD runs on pushes to `main`.
Backend CD runs on pushes to `main`.
Docker images are tagged with the Git commit SHA.
