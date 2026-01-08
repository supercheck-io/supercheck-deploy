<img src="https://raw.githubusercontent.com/supercheck-io/supercheck/main/supercheck-logo.png" alt="Supercheck Logo" width="75">

# Supercheck Deploy

**Community-Supported Deployment Arrangements**

[![Website](https://img.shields.io/badge/Website-supercheck.io-orange?logo=firefox)](https://supercheck.io)
[![Deploy](https://img.shields.io/badge/Deploy%20with-Docker%20Compose-blue?logo=docker)](./docker/docker-compose-secure.yml)
[![Deploy](https://img.shields.io/badge/Deploy%20with-Kubernetes-blue?logo=kubernetes)](./k8s)
[![Helm](https://img.shields.io/badge/Helm-Charts-0F1689?logo=helm&logoColor=white)](./k8s/charts)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository hosts the official community-driven infrastructure configurations for deploying SuperCheck. It separates operational concerns from the core application logic.

## Repository Contents

| Folder | Description |
|--------|-------------|
| **[`/docker`](./docker)** | Production-ready Docker Compose templates. |
| **[`/k8s`](./k8s)** | Kubernetes manifests and Helm charts. |


## Contributing

We welcome contributions to improve deployment flexibility and reliability. Please read our [Contributing Guide](CONTRIBUTING.md) before submitting a Pull Request.

- **Helm Charts**: Creation and refinement of official charts.
- **Cloud Providers**: Specific guides and templates for AWS, GCP, Azure, and Hetzner.
- **Security**: Hardening of network policies and container contexts.

## Resources

- **Main Repository**: [supercheck-io/supercheck](https://github.com/supercheck-io/supercheck)
- **Documentation**: [supercheck.io/docs/deployment](https://supercheck.io/docs/deployment)
