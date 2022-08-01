# Ubuntu setup in Docker Compose

A template for experimenting with Ubuntu under Docker / Docker Compose.

You need [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed to run this.

## Start it

Open a terminal, change directory to this repo and:

```bash
docker compose up --build
```

## Shell in

In a new terminal:

```bash
docker exec -it ubuntu bash
```