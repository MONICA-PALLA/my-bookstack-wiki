# Docker Commands Reference

This page contains useful Docker commands with their descriptions.

## 🔹 Docker Basics
- `docker --version`  
  Check the installed Docker version.

- `docker info`  
  Display system-wide information about Docker.

## 🔹 Working with Containers
- `docker ps`  
  Show running containers.

- `docker ps -a`  
  Show all containers (running & stopped).

- `docker run -it ubuntu bash`  
  Run an Ubuntu container interactively.

## 🔹 Working with Images
- `docker images`  
  List all Docker images on the system.

- `docker pull nginx`  
  Download the latest `nginx` image from Docker Hub.

- `docker rmi <image_id>`  
  Remove an image.

## 🔹 Networking
- `docker network ls`  
  List all Docker networks.

- `docker network inspect bridge`  
  Inspect the default bridge network.

- `docker network create my_network`  
  Create a custom network.

---
**More commands coming soon!**
