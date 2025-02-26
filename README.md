# GhostCMS Deploy Compose

This repository provides Docker Compose configurations for deploying Ghost CMS. It includes options with and without a MySQL database, using either the `alpine` or `latest` Ghost image tags.

## Available Configurations
- `docker-compose-db-alpine.yml`: Ghost 5.x (Alpine) with MySQL included.
- `docker-compose-no-db-alpine.yml`: Ghost 5.x (Alpine) without MySQL (for external DB).
- `docker-compose-db-latest.yml`: Ghost latest version with MySQL included.
- `docker-compose-no-db-latest.yml`: Ghost latest version without MySQL (for external DB).

## Usage
1. Download the desired configuration:
   ```bash
   wget https://raw.githubusercontent.com/yourusername/ghostcms-deploy-compose/main/docker-compose-db-alpine.yml -O docker-compose.yml