# Argo CD and Argo Rollouts for GitOps: The Definitive Guide

This repository contains the code and materials for the **Argo CD** section of my **Argo CD & Argo Rollouts** course.

### Prerequisites

1.  **Kubernetes Cluster**: You can use a local cluster like [Minikube](https://minikube.sigs.k8s.io/docs/start/), [Kind](https://kind.sigs.k8s.io/), or [Docker Desktop](https://docs.docker.com/desktop/kubernetes/).
2.  **kubectl**: The Kubernetes command-line tool. [Installation guide](https://kubernetes.io/docs/tasks/tools/).
3.  **Helm**: The package manager for Kubernetes. [Installation guide](https://helm.sh/docs/intro/install/).
4.  **Argo CD CLI**: Command-line interface for Argo CD. [Installation guide](https://argo-cd.readthedocs.io/en/stable/cli_installation/).



## 📚 Repository Structure

This repository covers the following topics:

- **installing-argocd**: Getting Started with Argo CD. Covers installing Argo CD via Helm and setting up the namespace.
- **access-argocd**: Accessing the Argo CD Web UI and CLI, including retrieving the initial admin password.
- **deploy-first-application**: Core Argo CD Concepts. Deploying your first "Guestbook" application and understanding the Application CRD.
- **sync-process**: Understanding the Sync Process, Configuration Drift, and Application Health status.
- **intro-helm-charts**: Working with Helm Charts. Learn how Argo CD integrates with Helm as a template engine.
- **public-helm-charts**: Deploying Public Helm Charts from external repositories.
- **setting-chart-values**: Customizing Helm Values & Precedence using `values.yaml` and parameters.
- **automated-sync-pruning**: Advanced Sync & Automation. Configuring automated syncing and pruning of orphaned resources.
- **self-healing**: Implementing Self-Healing to automatically correct configuration drift.
- **private-repo-https**: Access Management. Connecting to private Git repositories using HTTPS and Personal Access Tokens.
- **private-repo-ssh**: Access Management. Connecting to private Git repositories using SSH and Deploy Keys.
- **projects**: Organizing & Orchestrating Applications. Using Argo CD Projects for multi-tenancy and access control.
- **sync-phases-hooks**: Using Sync Phases and Hooks to run custom logic during the deployment lifecycle.
- **sync-waves**: Orchestrating complex deployments using Sync Waves to define precise deployment order.

I'm looking forward to seeing you in the course!
