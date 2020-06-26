# Docker Node
Simple node application, using Docker and Docker Compose.

## Build the container (mounts the image)
```bash
docker build -t joao/dockernode .
```

### Docker Compose
Used in this case to nodemon. So you don't need to run command bellow
```bash
docker-compose up
```

### Run the application
```bash
docker run -p 3000:3000 -d joao/dockernode
```

### Shows containers running currently
```bash
docker ps
```

### Docker stop
You can copy the id found after running command above
```bash
docker stop container_id
```