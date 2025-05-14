+++
title = 'Docker commands'
+++

## List of Docker commands

### **Docker Command Cheatsheet**

![Docker Cheatsheet](/images/cheatsheets/dockerCheatsheet.png) 


### **🛠 Docker Container Commands**

| **Command**                              | **Description**                              |
|------------------------------------------|----------------------------------------------|
| `docker run --name <container_name> <image_name>` | Run a container                             |
| `docker run -d <image_name>`              | Run a container in the background           |
| `docker start/stop <container_name>`      | Start or stop a container                   |
| `docker rm <container_name>`              | Remove a stopped container                  |
| `docker ps`                               | List running containers                     |
| `docker ps -a`                            | List all containers                         |
| `docker exec -it <container_name> sh`     | Open a shell inside a running container     |
| `docker logs -f <container_name>`         | Fetch and follow logs                       |
| `docker inspect <container_name>`         | Inspect a container                         |
| `docker stats`                            | View resource usage stats                   |

### **🛠 Docker Image Commands**

| **Command**                              | **Description**                              |
|------------------------------------------|----------------------------------------------|
| `docker build -t <image_name> .`         | Build an image                              |
| `docker images`                          | List local images                           |
| `docker rmi <image_name>`                | Remove an image                             |
| `docker image prune`                     | Prune unused images                         |
| `docker pull <image_name>`               | Download an image from a registry          |
| `docker tag <image_name> <repo_name>:<tag>` | Tag an image for repository use            |
| `docker push <repo_name>:<tag>`          | Push an image to a repository               |

### **🛠 Docker Volume Commands**
| **Command**                              | **Description**                              |
|------------------------------------------|----------------------------------------------|
| `docker volume create <volume_name>`     | Create a volume                             |
| `docker volume ls`                       | List volumes                                |
| `docker volume rm <volume_name>`         | Remove a volume                             |
| `docker volume inspect <volume_name>`    | Inspect a volume                           |
| `docker run -v <volume_name>:/path <image_name>` | Mount a volume to a container               |

### **🛠 Docker Networking Commands**

| **Command**                              | **Description**                              |
|------------------------------------------|----------------------------------------------|
| `docker network create <network_name>`   | Create a network                            |
| `docker network ls`                      | List networks                               |
| `docker network inspect <network_name>`  | Inspect a network                          |
| `docker network connect <network_name> <container_name>` | Connect a container to a network            |
| `docker network disconnect <network_name> <container_name>` | Disconnect a container from a network       |


### External resources

[Docker CLI Cheatsheet](https://docs.docker.com/get-started/docker_cheatsheet.pdf)

[The Ultimate Docker Cheat Sheet](https://dockerlabs.collabnix.com/docker/cheatsheet/)

