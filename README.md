# Docker Community Edition

Use this role to install the latest stable release of Docker Community Edition Engine on these Ubuntu versions:
    - Ubuntu Lunar 23.04
    - Ubuntu Kinetic 22.10
    - Ubuntu Jammy 22.04 (LTS)
    - Ubuntu Focal 20.04 (LTS)

This role follows the [install instructions found here](https://docs.docker.com/engine/install/ubuntu/)

## N/B
[Docker now ships docker compose natively so no need to install the legacy docker-compose plugin separately](https://docs.docker.com/compose/compose-v2/)

## Variables
- `docker_install_docker_compose` - Whether to install the legacy docker-compose plugin
- `docker_compose_version` - Version of the legacy docker-compose plugin to install
- `docker_users` - A list of pre-existing users that should have access to the Docker Daemon
