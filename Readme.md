# About VERT
VERT container definition.

## Frameworks used
- VERT

# Docker image details
Base image: ghcr.io/vert-sh/vert:latest
Exposed ports: 80 (mapped to 3000 on host)

# Deployment
## General
Service: levell-vert-web
Access URL: vert.app.levell.ch

## Attached Networks
- traefik-public - access to reverse proxy

## Restart Policy
unless-stopped
