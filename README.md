# Docker Community Edition

Use this role to install the latest stable release of Docker Community Edition Engine on these Ubuntu versions:
    - Ubuntu Kinetic 22.10
    - Ubuntu Jammy 22.04 (LTS)
    - Ubuntu Focal 20.04 (LTS)
    - Ubuntu Bionic 18.04 (LTS)

This role was built with the instructions found at https://docs.docker.com/engine/install/ubuntu/

## N/B
[Docker now ships with docker compose so no need to install the legacy docker-compose plugin separately](https://docs.docker.com/compose/compose-v2/)

## Variables
- `docker_install_docker_compose` - Whether to install the legacy docker-compose plugin
- `docker_users` - A list of pre-existing users that should have access to the Docker Daemon
