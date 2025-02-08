# Documentation

## Table of contents
- [Prerequisites before provision infra](#prerequisites-before-provision-infra)
- [Provision infra with docker compose](#provision-infra-with-docker-compose)

## Prerequisites before provision infra
```bash
docker network create traefik-vpc
```

## Provision infra with docker compose
Provision infra with docker compose

```bash
docker compose up -d
docker compose -f backend.yaml up -d
```
