# Proxmox

## Bare metal vs Virtualization

I started with a K3s single node cluster on bare metal running Ubuntu Server. I then moved to Talos Linux on bare metal with 1 control plane and 2 worker nodes, and ultimately I moved to Talos Omni with 3 control planes (HA) and 3 workers. With a hardware limitation of 3 physical nodes, I had to move from bare metal to virtualization, and I picked Proxmox, because it's open source, and I've read lots of positive things about it in the homelabbing community.

## Proxmox cluster

It's a 3-node cluster without Ceph storage. I wanted to setup Ceph, but this needs a second hard drive, and while I could install an additional hard drive, I've read online that this is not recommended for the type of mini pc that I have, due to heating issues.

## Talos Omni

As mentioned, I'm using Talos Omni. At the moment I downloaded the iso image from Talos Omni, uploaded it to each node, and completed the setup for each VM manually. Talos Omni makes it relatively easy and straightforward, but I do want to implement Terraform the next time for the provisioning of the VM's.
