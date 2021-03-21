# Learning Docker

## How to use?
Execute the commands below in cmd.

1. Run ```docker-compose up -d```.
2. Run ```docker-compose ps```.
3. Run ```docker container exec -ti learn-docker_mysqldb_1 bash```.
4. Run ```apt update && apt install -y iputils-ping```.
5. Run ```ping -c3 nginx```.
6. Run ```mysql -u root -p mydatabase```. The password is **root**.

## Prerequisite
- Docker
- Docker Compose
  
## Essential Commands
```docker run``` - Run container.</p>
```docker ps``` - List containers.</p>
```docker rm {ID/name}``` - Remove container.</p>
```docker images``` - List images.</p>
```docker rmi {ID/name}``` - Remove image.</p>
```docker logs {ID/name}``` - Show log.</p>
```docker inspect {ID/name}``` - Info container.</p>
```docker stats {ID/name}``` - cpu/mwm container.</p>
```docker login``` - Login repository.</p>
```docker push``` - Up imagem repo.</p>
```docker build``` - Create image from Dockerfile.</p>
```docker-compose up``` - Up images.</p>
```docker-compose ps``` - View images UP.</p>
```docker-compose stop/start``` - Stop or Start containers.</p>
```docker-compose down``` - Delete containers UP.</p>
