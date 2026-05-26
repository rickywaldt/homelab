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
