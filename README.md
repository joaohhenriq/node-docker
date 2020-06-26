# Docker Node
Simple node application, using Docker and Docker Compose.

## Build the container (mounts the image)
```bash
docker build -t joao/dockernode .
```

### Run the application
```bash
docker run -p 3000:3000 -d joao/dockernode
```

### Shows containers running currently
```bash
docker ps
```