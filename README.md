# docker-kafka-connect-compose

## network
```shell
    docker network create --gateway 172.18.0.1 --subnet 172.18.0.0/16 my-network
```

## docker build (Dockerfile)
```shell
    docker build -t [image-name] [file-path]
```

## docker compose run
```shell
    docker-compose -f [compose-file-path] up -d 
```