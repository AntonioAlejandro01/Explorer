# Explorer

## Backend

### Download docker-compose.yml for microservices

```bash
curl https://raw.githubusercontent.com/AntonioAlejandro01/Explorer/master/docker-compose.yml -o ./docker-compose.yml
```

### Run microservices

```bash
docker-compose up -d
```

## Run Frontend

```bash
docker run -p"80:80" -t antonioalejandro01/explorer-web:1
```

**Docker and docker-compose is neccesary**
