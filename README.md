# Nextjs 14 - Realtime
Dockerize Nextjs 14 Realtime

### Up
``` bash
cd next-realtime
docker compose -f docker/docker-compose.development.yaml up -d --build
```

### Down
``` bash
cd next-realtime
docker compose -f docker/docker-compose.development.yaml down -rmi all --remove-orphans
```

App: http://localhost:3000  
