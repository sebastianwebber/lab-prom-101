# prometheus 101 lab

## dependencies

1. Docker
1. Docker compose
1. [Play-with-docker](https://labs.play-with-docker.com)

## basic usage

1. Clone this repo:

    ```bash
    git clone https://github.com/sebastianwebber/lab-prom-101.git ; cd lab-prom-101
    ```

1. Start the containers

    ```bash
    docker-compose up -d
    ```

### all at once

```bash
git clone https://github.com/sebastianwebber/lab-prom-101.git ; cd lab-prom-101
docker-compose up -d
```


## postgres usage

```bash
docker exec -it postgres psql -U postgres
```