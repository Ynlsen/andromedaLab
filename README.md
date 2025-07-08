![AndromedaLab Banner](andromedalab-logo.png)

# AndromedaLab

This repository contains the config files for my docker based VM running on my own server. The VM hosts various services for personal use, media streaming, backups, and homelab/development. All services are containerized using Docker and are accessible through a single entry point managed by Traefik, which handles SSL/TLS and routing.

Each service has its own directory containing a docker compose file, its own README file [coming soon], and sometimes more.

This server is still in its growth phase and will be expanded with additional services in the future. For more information about the overall server infrastructure beyond this main VM, please refer to [coming soon].

## Services

The VM hosts the following services:

- **Yniederer** (`yniederer.ch/`): Personal website
- **Nextcloud** (`nextcloud/`): File storage/backup
- **Immich** (`immich/`): Photo backup/management
- **Jellyfin** (`jellyfin/`): Media streaming
- **Traefik** (`traefik/`): Reverse proxy
- **Vaultwarden** (`vaultwarden/`): Password manager
- **Minecraft** (`minecraft/`): Minecraft server
- **Website Alpina** (`website-alpina/`): Someone else's website
- **PostgreSQL** (`postgresqlDMDB/`): Database
- **Node Docker App** (`node-docker-app/`): Node testing
