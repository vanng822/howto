### Start container

```bash
docker run --restart=always --network NETWORK --ip 172.18.0.7 \
  -v app:/app --name NAME -d -p PORT:PORT -it IMAGE_TAG
```

### Stop container

```bash
docker stop NAME
```

### Delete container

```bash
docker rm NAME
```

### Get container id

```bash
docker ps -f name=NAME -q
```

### watching log from container

```bash
docker logs -f CONTAINER_ID
```

### go in to container with bash

```bash
docker exec -it CONTAINER_ID /bin/bash
```

### Inspect configuration

```bash
docker inspect CONTAINER_ID
```
