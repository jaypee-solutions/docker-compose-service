[![Yamllint](https://github.com/jaypee-solutions/docker-compose-service/actions/workflows/yamllint.yml/badge.svg)](https://github.com/jaypee-solutions/docker-compose-service/actions/workflows/yamllint.yml)
[![Ansible Lint](https://github.com/jaypee-solutions/docker-compose-service/actions/workflows/ansible-linting.yml/badge.svg)](https://github.com/jaypee-solutions/docker-compose-service/actions/workflows/ansible-linting.yml)

# Variables

- docker_compose_service_name: The service name
- docker_compose_service_basedir: The directory of the service containing docker-compose.yml
- docker_compose_service_respawn: Define if respawn should be enabled

## Defaults

- docker_compose_executable: /usr/bin/docker-compose
