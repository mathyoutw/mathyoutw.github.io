# Local Development with Docker

This folder contains Docker configuration for running your Jekyll site locally.

## Prerequisites

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)

## Quick Start

### Starting the Server

```bash
cd mathyoutw.github.io
./docker/serve.sh
```

Or from anywhere:

```bash
cd /path/to/mathyoutw.github.io
docker compose -f docker/docker-compose.yml up
```

The site will be available at: **http://localhost:4000**

### Stopping the Server

Press `Ctrl+C` in the terminal where the server is running.

Or use the stop script:

```bash
./docker/stop.sh
```

Or from anywhere:

```bash
docker compose -f docker/docker-compose.yml down
```

## Troubleshooting

### Container won't start

```bash
docker compose -f docker/docker-compose.yml down --remove-orphans
docker compose -f docker/docker-compose.yml up
```

### View logs

```bash
docker compose -f docker/docker-compose.yml logs
```

### Rebuild from scratch

```bash
docker compose -f docker/docker-compose.yml down --remove-orphans --rmi local
docker compose -f docker/docker-compose.yml up
```
