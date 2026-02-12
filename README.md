# eks-wp-gitops — Phase 2 ✅

This repository contains the GitOps (ArgoCD) manifests and Helm values for the *second phase* of the EKS + WordPress project.

Phase 2 focuses on GitOps-based deployment on an existing EKS cluster created by the Terraform project:

- Terraform (Phase 1): https://github.com/uvegesi/eks-wordpress2

> Note: make sure the infrastructure from the Terraform repo is provisioned before applying the manifests in this repository.

Quick start
- Use ArgoCD to sync the `root-app` (it bootstraps the `wordpress` application).
