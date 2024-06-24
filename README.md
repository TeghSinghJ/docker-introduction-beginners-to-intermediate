
# Docker : Beginner to Intermmediate 🐳
Welcome to the Docker Beginner to Intermediate repository! This repository is dedicated to helping developers transition from basic to intermediate proficiency with Docker.



## What is Docker?
Docker is an open-source platform for developing, delivering, and running applications. Docker shortens the time between code creation and deployment by coordinating infrastructure management with application processing. 

Applications are packaged and run inside what are known as containers, which are loosely isolated environments in the Docker ecosystem. Because of this isolation, more containers can run concurrently on a single host, improving security. 

As they are lightweight, containers eliminate the need for host setups by encapsulating all requirements for application execution. 

Since containers are consistent across shared environments, collaboration is smooth.

Docker simplifies the process of building, testing, and deploying applications by using containerization.

Containers are lightweight and contain everything needed to run the application, ensuring consistency across different environments.


## Installation

### Installing Docker Desktop on Windows

1. **Download Docker Desktop**: Go to the [Docker Desktop download page](https://www.docker.com/products/docker-desktop) and download the installer for Windows.
2. **Run the Installer**: Follow the instructions in the installation wizard.
3. **Start Docker Desktop**: Open Docker Desktop from the Start menu.
4. **Verify Installation**: Open a terminal and run:
    ```bash
    docker --version
    ```

    
## Basic Docker Commands

- **Pull an Image**: Download a Docker image from Docker Hub.
    ```bash
    docker pull image_name
    ```
- **Run a Container**: Create and start a container from an image.
    ```bash
    docker run -it image_name
    ```
- **List Containers**: Show all running containers.
    ```bash
    docker ps
    ```
- **Stop a Container**: Stop a running container.
    ```bash
    docker stop container_id
    ```


