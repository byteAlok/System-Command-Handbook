# Docker Commands Cheat Sheet

## Image Management
- `docker pull <image>`: Download an image from Docker Hub
- `docker images`: List local images
- `docker rmi <image>`: Remove an image
- `docker build -t <name> .`: Build an image from a Dockerfile

## Container Management
- `docker run <image>`: Create and start a container
- `docker run -d -p 8080:80 <image>`: Run container in background and map ports
- `docker ps`: List running containers
- `docker ps -a`: List all containers (including stopped)
- `docker stop <container>`: Stop a container
- `docker start <container>`: Start a stopped container
- `docker rm <container>`: Remove a container

## Interacting with Containers
- `docker exec -it <container> sh`: Access the shell of a running container
- `docker logs <container>`: View container logs
