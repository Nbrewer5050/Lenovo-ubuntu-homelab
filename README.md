# Lenovo Lab | Linux Home Server Infrastructure

## Project Overview

Designed, configured, and tested a Linux-based home server environment to develop practical experience in systems administration, networking, containerization, and remote infrastructure management.

The project uses repurposed Lenovo hardware running Ubuntu Server to host and manage infrastructure services.

## Technologies Used

- **Operating System:** Ubuntu Server
- **Containerization:** Docker and Docker Compose
- **Container Management:** Portainer
- **Reverse Proxy:** Nginx Proxy Manager
- **Networking:** TCP/IP, Ethernet, DNS, SSH
- **Remote Connectivity:** SSH and remote network testing
- **Additional Technologies Explored:** Cloudflare Tunnel, WireGuard, Tailscale, UFW

## Project Objectives

1. Repurpose existing hardware into a functional Linux server.
2. Deploy and manage containerized applications.
3. Configure networking and remote administration.
4. Troubleshoot connectivity and service issues.
5. Build a foundation for future cloud, cybersecurity, and AI infrastructure projects.

## Implementation

### Phase 1: Server Setup
- Installed and configured Ubuntu Server.
- Updated system packages and prepared the environment.
- Configured network connectivity and administrative access.

### Phase 2: Container Infrastructure
- Installed Docker and Docker Compose.
- Deployed Portainer for container management.
- Started Nginx Proxy Manager containers.

### Phase 3: Networking and Remote Access
- Configured SSH connectivity.
- Worked with Starlink networking and Ethernet connections.
- Explored Cloudflare DNS, tunneling, and VPN technologies.
- Tested remote access using an external network.

### Phase 4: Troubleshooting and Validation
- Diagnosed SSH connectivity and service availability issues.
- Investigated networking and firewall configurations.
- Successfully established remote access from a separate physical location.

## Key Results

- Built a functioning Linux server environment using repurposed hardware.
- Gained hands-on experience deploying and managing containerized infrastructure.
- Successfully validated remote server connectivity outside the local network.
- Developed practical troubleshooting skills across Linux services and networking.

## Future Development

- Implement infrastructure monitoring and alerting.
- Automate server maintenance and backups.
- Strengthen security and access controls.
- Deploy additional self-hosted applications.
- Explore AI-assisted infrastructure monitoring and automation.

## Security

Credentials, private keys, authentication tokens, and sensitive network configuration details are excluded from this repository.

## Project Status

**Functional lab environment with ongoing improvements planned.**

This project serves as a foundation for continued learning in Linux administration, DevOps, cybersecurity, and AI infrastructure engineering.

## Project Results and Technical Accomplishments

### Infrastructure Deployment
- Configured an Ubuntu Server environment using repurposed Lenovo hardware.
- Deployed Docker containers and established a container management interface using Portainer.
- Deployed Nginx Proxy Manager as part of the lab's reverse proxy infrastructure.
- Configured networking and explored Cloudflare DNS and secure tunneling technologies.

### Remote Administration
- Configured and tested SSH connectivity.
- Troubleshot network connectivity across Starlink and external networks.
- Successfully connected to the Lenovo Lab server from a separate physical location, validating remote administration capabilities.

### Technical Troubleshooting
- Investigated SSH connection timeouts and service availability.
- Diagnosed Linux service configuration and network connectivity issues.
- Practiced troubleshooting firewall settings, network interfaces, and container services.

### Skills Demonstrated
Linux System Administration | Docker | Container Management | TCP/IP Networking | SSH | Remote Infrastructure Management | Technical Troubleshooting

### Future Development
- Implement centralized monitoring and alerting.
- Automate backups and routine maintenance.
- Expand containerized services.
- Explore AI-assisted infrastructure monitoring and security automation.


## Infrastructure Architecture

The homelab uses Ubuntu Server, Docker, and Tailscale VPN to support containerized services and secure remote administration.

[View Infrastructure Architecture and Network Diagram](docs/architecture.md)

## Troubleshooting and Lessons Learned

Documented real-world challenges encountered during the Lenovo Lab deployment, including SSH timeouts, VPN connectivity, Cloudflare service diagnostics, and Docker container management.

[View Troubleshooting Documentation](docs/troubleshooting.md)
