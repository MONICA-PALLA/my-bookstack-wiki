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

- `docker run -it image_name`  
  Spin up a container.

## 🔹 Working with Images

- `docker image build -t image_name .`
  This command builds the docker image and it should run in the directory in which the Dockerfile is present  

- `docker images`
  List all Docker images on the system.

- `docker images`  

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
