## Docker Media Platform (Secure + Automated)

Self-hosted Docker media stack with reverse proxy, HTTPS, and SSO.

### Overview

This project sets up a secure, containerized media server environment running on Linux Mint. Designed for reliability, privacy, and low-maintenance operation, it includes:
  - NGINX + Certbot for automatic HTTPS and reverse proxy
  - Authelia for SSO with 2FA
  - Sonarr, Radarr, Bazarr, Prowlarr for personal media organization and metadata
  - qBittorrent + Gluetun, NZBGet for network-isolated tools
  - rclone + Backblaze for automated offsite backups
  - Watchtower for zero-downtime Docker updates
  - Custom shell scripts for container health checks, network isolation verification, and failure alerting

Built to be self-sustaining and require minimal manual intervention after setup.

### Notes

  - Designed for LAN-first use, with external access strictly limited
  - Currently deployed on a 2010 Mac Pro running Linux Mint (and staying there until the 15+ year-old HDD dies)
  - Requires Docker and Docker Compose
