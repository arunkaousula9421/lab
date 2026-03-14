# DevOps Journey — Lab

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen)

## About

Continuous learning happens in the lab. This repository is a personal sandbox where I collect labs, projects, scripts, and experiments used for building hands-on DevOps skills. Each directory represents a topic or technology I am actively exploring.

## Topics Covered

| Topic | Description | Status |
|-------|-------------|--------|
| Kubernetes (K8S) | Cluster setup, deployments, services, configs | In Progress |

> More topics will be added as the journey continues — Docker, CI/CD, Terraform, Ansible, Observability, and more.

## Repository Structure

```
lab/
└── K8S/          # Kubernetes labs and manifests
```

## Prerequisites

Depending on the lab, you may need one or more of the following tools installed:

- [kubectl](https://kubernetes.io/docs/tasks/tools/) — Kubernetes CLI
- [minikube](https://minikube.sigs.k8s.io/docs/) or [kind](https://kind.sigs.k8s.io/) — local Kubernetes clusters
- [Docker](https://docs.docker.com/get-docker/) — container runtime
- [Helm](https://helm.sh/docs/intro/install/) — Kubernetes package manager

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/arunkumar-aousula/lab.git
   cd lab
   ```

2. Navigate to the topic directory you want to explore:
   ```bash
   cd K8S
   ```

3. Follow the instructions in each subdirectory's README (where applicable).

## Goals

- Build real, repeatable hands-on experience with DevOps tooling
- Document experiments and lessons learned
- Create a reference library for future projects

## License

This project is licensed under the [MIT License](LICENSE).
