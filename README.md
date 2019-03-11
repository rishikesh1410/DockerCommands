# DockerCommands

# Installation

sudo apt-get update
sudo apt-get insall docker.io

# Basic commands

docker -v
docker --version
docker version
docker info
docker --help

# Login to docker

First create a account on docker hub
docker login

# Docker Images

docker images --help
docker images
docker images -q
docker images -f "dangling=false"
docker pull <image_name>
docker rmi <image_name / image_id>
docker rmi -f <image_name / image_id>
docker inspect

# Docker Containers

docker ps
docker run <image_name / image_id>
docker start <image_name / image_id>
docker stop <image_name / image_id>

# Docker system 

docker stats
docker system df
docker system prune

