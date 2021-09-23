# Docker Images

## Introduction

In this exercise, we will be ...

## Prerequisites

1. Installed Docker Desktop
2. Forked the repository and checkout `main` branch to have the completed frontend and backend
3. Successfully ran `docker-compose up` for the frontend and backend from yesterday's workshop

## Exercises

### Understanding Docker

anatomy of the docker-compose file

anatomy of the Dockerfile

docker build

docker run

docker push

### Optimizing Images

Advantages of optimizing images

Replacing the base image for the frontend and backend image to reduce the size from 1gb to 300mb.

### Build and Push Images with GitHub Actions

Why push images to an image registry?

GitHub Actions to build and push images with Docker buildx

### Using Built Images

The current docker-compose.yml file builds the image locally and runs it.

We can modify the file to pull the images from GHCR instead. This is useful to share images with other team members and to ensure that everyone is using a consistent image to run their application.

Remove build keywords and replace with image + tag

### Stopping The Application

Once done, run `docker-compose down` to stop the containers that are running locally.

In the next exercise, we will begin deploying the frontend to AWS so that the application is accessible over the web.

---

[< Back to Exercises](../exercises/README.md) | [Solution](../solutions/32-Docker-Images.md) | [Next Exercise >](./33-InfrastructureAsCode.md)
