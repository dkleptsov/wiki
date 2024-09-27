# My Docker cheatsheet

## 🛠️ Installation of Docker and Docker-compose
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Usefull commands
1. **Stop all containers**
  ```bash
docker stop $(docker ps -q)
  ```
2. **Delete all containers**
  ```bash
docker rm $(docker ps -a -q)
  ```
3. **Clean unused images**
  ```bash
docker image prune -a
  ```
