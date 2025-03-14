# Homelab Network Diagram

Welcome to my homelab network diagram repository! This diagram highlights the architecture and design of my homelab setup, documenting the use of virtualization, containerization, and application services for personal use.

## What You'll Find Here

- **Up-to-Date Diagram**: The latest reversion of my homelab network diagram, including some details about:
  - **Hypervisors**: The foundation of my CTs and VMs.
  - **Virtual Machines (VMs)**: Deployed for various purposes, from development to testing.
  - **Containers**: Lightweight and efficient solutions for running isolated applications.
  - **Application Services**: App services such as media organizing, web servers, network monitoring, backups, and home automation.

- **Ongoing Improvements**: As my homelab grows and evolves, this repository will be continuously updated to reflect its latest state.


![Homelab Network Diagram](https://github.com/danieljai/homelab/blob/4eee310b72505c710949d1557f1c88788d08bfdf/diagram/92king_homelab.png)
Updated: 2024-03-07

## Pending list

- Reverse proxy with SSL
- Explore other ways to keep media player secure, using custom domain name while not exposing to public.
- Minimalistic web server CT, capable of serving a web form to accept user input data and process it through Python trained ML model, returning the inference output.
- Set up Proxmox Backup Service to push LXC backups to S3
