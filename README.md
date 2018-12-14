# Docker Community Edition

Use this role to install the latest stable release of Docker Community Edition on Ubuntu 16.04 Xenial.

This role was built with the instructions found at https://docs.docker.com/install/linux/docker-ce-ubuntu/

## Variables

- `docker_version` - The version of the Docker Daemon to install
- `docker_compose_version` - The version of docker-compose to install
- `docker_install_docker_compose` - Whether to install docker-compose or not. The default value is `True`
- `docker_users` - A list of pre-existing users that should have access to the Docker Daemon
