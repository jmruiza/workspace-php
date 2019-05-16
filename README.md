# PHP (with apache) and MySQL with docker

Workspace in docker to build PHP apps with MySQL.

## Commands

```docker
# Run and build (First time) containers
docker-compose up
# Run and rebuild containers
docker-compose up -d --build
```

```docker
# View running containers
docker ps
# View all containers
docker ps -a
```

```docker
# Get the ip assigned to container
docker inspect -f '{{ range .NetworkSettings.Networks }}{{ .IPAddress }}{{ end }}' <conteiner_id>
```

## Resources
 * [Desarrollando con docker](https://blog.irontec.com/desarrollando-con-docker/)