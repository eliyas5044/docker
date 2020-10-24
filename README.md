# Docker Environment

## Setup

> copy environment file
```bash
cp .env.example .env
```

> copy docker-compose file
```bash
cp docker-compose.yml.example docker-compose.yml
```
## Build

> build services
```bash
docker-compose build nginx

# build without cache
docker-compose build --no-cache nginx
```
## Start Service

> start service, i.e nginx
```bash
docker-compose up -d nginx
```
