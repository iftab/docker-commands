# docker-commands

# 🐳 Docker Cheat Sheet

A quick reference guide for Docker essentials.  
> 📘 **Reference:** [Docker Docs - Get Started](https://docs.docker.com/get-started/docker-overview/)  
> 🎥 **Video Tutorial:** [Docker for Beginners](https://www.youtube.com/watch?v=X3Wtjwu0vBI&t=1324s)

---

## 📌 What is Docker?

Docker is an open platform for developing, shipping, and running applications. It allows you to separate your applications from your infrastructure and helps ensure that your software runs reliably when moved from one environment to another.

Docker provides the ability to package and run an application in a loosely isolated environment called a **container**.

---

## 🧰 Docker Basic Commands

| Command | Description |
|--------|-------------|
| `docker pull IMAGE_NAME` | Download an image from Docker Hub |
| `docker images` | List all Docker images on your system |
| `docker run IMAGE_NAME` | Create and start a new container |
| `docker run -it IMAGE_NAME` | Run a container interactively |
| `docker ps` | List running containers |
| `docker ps -a` | List all containers (running & stopped) |

---

## ⚙️ Container Management

| Command | Description |
|--------|-------------|
| `docker start CONTAINER_ID/NAME` | Start a stopped container |
| `docker stop CONTAINER_ID/NAME` | Stop a running container |
| `docker restart CONTAINER_ID/NAME` | Restart a container |
| `docker rm CONTAINER_ID/NAME` | Remove a stopped container |
| `docker rmi IMAGE_NAME` | Remove an image |

---

## 🛠️ Container Operations

| Command | Description |
|--------|-------------|
| `docker exec -it CONTAINER_ID /bin/bash` | Access container bash shell |
| `
