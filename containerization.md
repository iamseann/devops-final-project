# Containerization with Docker

Guidelines for packaging applications and their dependencies into portable containers.

## Docker Basics

docker build -t <image-name> .: Builds a Docker image from a Dockerfile.
docker run -p 8080:80 <image-name>: Starts a container and maps host port 8080 to container port 80.
docker ps: Lists all currently running containers.
docker stop <container-id>: Stops a running container.

## Docker Compose

Used for defining and running multi-container applications.

docker compose up -d: Starts all services defined in docker-compose.yml in detached mode (background).

docker compose down: Stops and removes all containers, networks, and images defined in the file.

docker compose logs -f: Follows the live output of the container logs.