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

docker run <image_name>

docker start <image_name / image_id>

docker stop <image_name / image_id>

docker pause <image_name / image_id>

docker unpause <image_name / image_id>

docker top <image_name / image_id>

docker stats <image_name / image_id>

docker rm <image_name / image_id>

docker kill <image_name / image_id>

docker history <image_name / image_id>


# Docker system 

docker stats

docker system df

docker system prune


# Dockerfile

FROM

RUN

CMD


# Docker compose Installation

pip install -U docker-compose


# docker-compose 

Create docker-compose.yml

docker-compose config

docker-compose up -d

 docker-compose down
 
 —scale
docker-compose up -d --scale database=4





