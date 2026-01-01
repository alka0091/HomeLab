# HomeLab

## Overview
This repository documents my personal IT home lab, designed to demonstrate hands on experience with virtualization, Linux system administration, networking, and secure service deployment. The lab is built relevant tools and best practices, focusing on service isolation, secure remote access, and real world usability.

This project serves as a practical portfolio showcasing my ability to design, deploy, manage, and document infrastructure.


## Current Services Summary

| Service | Description |
|------|------------|
| Proxmox VE | Bare-metal hypervisor hosting all virtual machines |
| OPNsense | Firewall and gateway providing network security |
| FileSrv | Centralized file server accessible via Windows File Explorer |
| Jellyfin | Self-hosted media server running in a dedicated VM |
| Tailscale VPN | VPN enabling secure remote access to the home lab from anywhere in the world via mobile and laptop devices, without exposing services publicly |

## Lab Environment

### Hardware
- Lenovo ThinkCentre

### Virtualization Platform
- Proxmox VE
  - Hosts multiple Linux virtual machines
  - Manages compute, storage, and networking resources

## Virtual Machines & Services

### Linux Servers
- Ubuntu Server
  - CLI-based administration
  - User and password management
  - SSH remote access
- Ubuntu Desktop
  - GUI-based management where appropriate

### File Server (FileSrv)
- Dedicated file server VM used to store:
  - School work
  - Personal files
  - Backups and archived data
- Files can be uploaded directly from my windows personal computer using file explorer
- User based authentication enforced
- No public or anonymous access

### Media Server (Jellyfin)
- Jellyfin deployed in a dedicated VM
- Managed via web based GUI
- Media accessed through internal network
- Service isolated from other workloads

### Remote Access & Networking
- Secure VPN based remote access using Tailscale (WireGuard)
- No direct exposure of Proxmox or internal services to the internet
- Experience with:
  - IP addressing
  - Proxmox network bridges
  - LAN vs VPN access validation

## Security Considerations
- Private internal services
- Authentication enforced on shared resources
- Least privilege mindset
- Secure remote management practices

## Skills Demonstrated
- Proxmox virtualization
- Linux system administration
- Network file sharing and permissions
- Secure VPN based remote access
- Deployment of self hosted services
- Practical troubleshooting and infrastructure design
