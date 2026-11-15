# Lenovo Ubuntu Homelab - Troubleshooting and Lessons Learned

## Overview

This document records technical challenges encountered while configuring and testing a Linux home server environment.

## 1. SSH Connection Timeouts

**Issue:** SSH connections to the Ubuntu server occasionally timed out.

**Investigation:**
- Checked server network connectivity.
- Investigated SSH service availability.
- Reviewed firewall and network configuration.
- Tested connections from different networks.

**Outcome:** Successfully established remote SSH connectivity using Tailscale VPN from a separate physical location.

**Lesson Learned:** Remote access troubleshooting requires checking the network path, service availability, authentication, and VPN connectivity.

## 2. Remote Access Across Different Networks

**Issue:** Needed to administer the Lenovo server while away from its local network.

**Investigation:**
- Tested connectivity using Starlink and a mobile hotspot.
- Explored multiple remote access technologies.
- Configured and tested Tailscale connectivity.

**Outcome:** Verified remote administration using Tailscale VPN.

**Lesson Learned:** A mesh VPN can simplify remote access without requiring direct public exposure of SSH.

## 3. Cloudflare Tunnel Service Investigation

**Issue:** During testing, the Cloudflare Tunnel service was observed in an inactive state.

**Investigation:**
- Checked service status.
- Reviewed connectivity and tunnel configuration.

**Outcome:** The service issue was investigated; successful tunnel operation was not independently verified.

**Lesson Learned:** Service status and successful end-to-end connectivity should be verified separately.

## 4. Container Deployment and Management

**Task:** Deploy and manage infrastructure applications using Docker.

**Actions:**
- Installed and configured Docker.
- Started Portainer and Nginx Proxy Manager.
- Accessed the Portainer management interface.

**Outcome:** Established a working container management environment.

**Lesson Learned:** Container status, exposed ports, and application availability are separate checks.

## Key Skills Demonstrated

- Linux troubleshooting
- SSH remote administration
- TCP/IP networking
- VPN connectivity
- Service diagnostics
- Docker container management
- Systematic fault isolation

## Future Improvements

- Add sanitized terminal command examples.
- Document repeatable diagnostic procedures.
- Implement infrastructure monitoring.
- Record configuration changes and validation results.
