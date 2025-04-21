# Docker Commands

A comprehensive collection of Docker commands to help you manage containers, images, volumes, and networks efficiently.

---

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Basic Docker Commands](#basic-docker-commands)
  - [Container Management](#container-management)
  - [Image Management](#image-management)
  - [Volume Management](#volume-management)
  - [Network Management](#network-management)
- [Advanced Docker Commands](#advanced-docker-commands)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
Docker is an open platform for developing, shipping, and running applications. This repository provides a list of essential Docker commands for both beginners and advanced users.

---

## Getting Started
To work with Docker, ensure you have Docker installed on your system. Visit [Docker's official documentation](https://docs.docker.com/get-docker/) for installation instructions.

---

## Basic Docker Commands

### Container Management
- `docker ps` - List running containers.
- `docker ps -a` - List all containers (including stopped ones).
- `docker start <container_id>` - Start a stopped container.
- `docker stop <container_id>` - Stop a running container.
- `docker rm <container_id>` - Remove a container.

### Image Management
- `docker images` - List all Docker images.
- `docker pull <image_name>` - Pull an image from Docker Hub.
- `docker rmi <image_name>` - Remove a Docker image.
- `docker build -t <image_name> .` - Build an image from a Dockerfile.

### Volume Management
- `docker volume ls` - List all Docker volumes.
- `docker volume create <volume_name>` - Create a new volume.
- `docker volume rm <volume_name>` - Remove a volume.

### Network Management
- `docker network ls` - List all Docker networks.
- `docker network create <network_name>` - Create a new network.
- `docker network rm <network_name>` - Remove a network.

---

## Advanced Docker Commands
- `docker-compose up` - Start all services defined in a `docker-compose.yml` file.
- `docker-compose down` - Stop all services and remove containers, networks, and volumes.
- `docker exec -it <container_id> <command>` - Execute a command inside a running container.
- `docker logs <container_id>` - View logs of a container.
- `docker inspect <resource>` - View detailed information about a resource (container, image, etc.).

---

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and submit a pull request.

---

## License
This repository is licensed under the [MIT License](LICENSE).

---

## Feedback
If you have any suggestions or improvements, feel free to create an issue or submit a pull request.

---

Happy Dockering! 🐳
