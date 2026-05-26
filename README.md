# homelab

My Kubernetes homelab powered by Talos Linux.

## Hardware

- HP EliteDesk 800 G2 i5-6500T/4CPU/32GB/250GB SSD
- HP EliteDesk 800 G2 i5-6500T/4CPU/32GB/256GB SSD
- HP EliteDesk 800 G2 i3-6100/4CPU/32GB/250GB SSD

Proxmox 3-node cluster. HA Kubernetes cluster with 3 control planes and 3 workers managed by Talos Omni.

| Role  | Memory | Cores  | System Disk |
|-------|-----|-----------|-------------|
| Control Plane | 4 GiB  | 4  | 32 GiB  |
| Worker   | 16 GiB  | 4    | 32 GiB    |

## Infrastructure

| Icon | Name | Description |
|------|------|-------------|
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/proxmox.png" width="30" alt="Proxmox logo"> | [Proxmox](https://www.proxmox.com/) | Virtualization platform used to host and manage the underlying infrastructure. |
| <img src="https://avatars.githubusercontent.com/u/138754790?s=200&v=4" width="30" alt="Talos Omni logo"> | [Talos Omni](https://www.siderolabs.com/platform/saas-for-kubernetes/) | Centralized platform for provisioning and managing Talos Kubernetes clusters. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/kubernetes.png" width="30" alt="Kubernetes logo"> | [Kubernetes](https://kubernetes.io/) | Container orchestration platform powering workloads across the cluster. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/longhorn.png" width="30" alt="Longhorn logo"> | [Longhorn](https://longhorn.io/) | Distributed storage solution providing persistent volumes for workloads. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/traefik.png" width="30" alt="Traefik logo"> | [Traefik](https://traefik.io/) | Ingress controller and reverse proxy for routing cluster traffic. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/cnpg.png" width="30" alt="CloudNativePG logo"> | [CloudNativePG](https://cloudnative-pg.io/) | Kubernetes operator for deploying and managing PostgreSQL clusters. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/velero.png" width="30" alt="Velero logo"> | [Velero](https://velero.io/) | Backup and disaster recovery tool for Kubernetes resources and volumes. |

## Platform Tooling

| Icon | Name | Description |
|------|------|-------------|
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/flux-cd.png" width="30" alt="Flux CD logo"> | [Flux CD](https://fluxcd.io/) | GitOps operator that continuously syncs cluster state from Git repositories. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/helm.png" width="30" alt="Helm logo"> | [Helm](https://helm.sh/) | Package manager for deploying Kubernetes applications using charts. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/kustomize.png" width="30" alt="Kustomize logo"> | [Kustomize](https://kustomize.io/) | Tool for customizing Kubernetes manifests without templating. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/renovate.png" width="30" alt="Renovate logo"> | [Renovate](https://www.mend.io/renovate/) | Automates dependency and container image updates through pull requests. |

## Observability & Security

| Icon | Name | Description |
|------|------|-------------|
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/prometheus.png" width="30" alt="Prometheus logo"> | [Prometheus](https://prometheus.io/) | Collects and stores metrics used for monitoring and alerting. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/grafana.png" width="30" alt="Grafana logo"> | [Grafana](https://grafana.com/) | Dashboarding and visualization platform for metrics and observability. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/keycloak.png" width="30" alt="Keycloak logo"> | [Keycloak](https://www.keycloak.org/) | Identity and access management platform providing centralized authentication. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/harbor.png" width="30" alt="Harbor logo"> | [Harbor](https://goharbor.io/) | Private OCI registry for securely storing and managing container images. |

## Applications

| Icon | Name | Description |
|------|------|-------------|
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/immich.png" width="30" alt="Immich logo"> | [Immich](https://immich.app/) | Self-hosted photo and video backup platform with mobile sync support. |
| <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/linkding.png" width="30" alt="Linkding logo"> | [Linkding](https://github.com/sissbruecker/linkding) | Minimal self-hosted bookmark manager for saving and organizing links. |
