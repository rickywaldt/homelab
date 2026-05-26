# homelab

My Kubernetes homelab powered by Talos Linux.

Hardware:

- HP EliteDesk 800 G2 i5-6500T/4CPU/32GB/250GB SSD
- HP EliteDesk 800 G2 i5-6500T/4CPU/32GB/256GB SSD
- HP EliteDesk 800 G2 i3-6100/4CPU/32GB/250GB SSD

Proxmox 3-node cluster. HA Kubernetes cluster with 3 control planes and 3 workers managed by Talos Omni.

| Role  | Memory | Cores  | System Disk |
|-------|-----|-----------|-------------|
| Control Plane | 4 GiB  | 4  | 32 GiB  |
| Worker   | 16 GiB  | 4    | 32 GiB    |

Infra:

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/13629408?s=200&v=4"></td>
        <td><a href="https://kubernetes.io">Kubernetes</a></td>
        <td>Core orchestration platform powering container workloads managed by Talos Omni.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://helm.sh/img/helm.svg"></td>
        <td><a href="https://helm.sh">Helm</a></td>
        <td>Simplifies application deployments in Kubernetes using reusable charts.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://dashboard.snapcraft.io/site_media/appmedia/2020/06/kustomize.png"></td>
        <td><a href="https://kustomize.io">Kustomize</a></td>
        <td>Manages Kubernetes manifest customization without relying on templates.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://raw.githubusercontent.com/fluxcd/website/main/static/img/flux-icon@2x.png"></td>
        <td><a href="https://fluxcd.io">Flux CD</a></td>
        <td>Handles GitOps deployments by continuously reconciling cluster state with Git.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://raw.githubusercontent.com/traefik/traefik/master/docs/content/assets/img/traefik.logo.png"></td>
        <td><a href="https://traefik.io">Traefik</a></td>
        <td>Acts as the ingress controller and reverse proxy for services running in the cluster.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://longhorn.io/img/logos/longhorn-icon-color.png"></td>
        <td><a href="https://longhorn.io">Longhorn</a></td>
        <td>Provides persistent distributed storage tailored for Kubernetes workloads.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://external-secrets.io/latest/pictures/eso-logo-large.png"></td>
        <td><a href="https://external-secrets.io">External Secrets Operator</a></td>
        <td>Syncs secrets from external providers into Kubernetes secrets automatically.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/3380462?s=200&v=4"></td>
        <td><a href="https://prometheus.io">Prometheus</a></td>
        <td>Collects cluster and application metrics for monitoring and alerting.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://grafana.com/static/img/menu/grafana2.svg"></td>
        <td><a href="https://grafana.com">Grafana</a></td>
        <td>Used for dashboards and visualizing metrics collected across the cluster.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://docs.renovatebot.com/assets/images/logo.png"></td>
        <td><a href="https://www.mend.io/renovate">Renovate</a></td>
        <td>Keeps dependencies and container images updated through automated pull requests.</td>
    </tr>
</table>
