# CI/CD Cheat Sheet

A quick personal reference guide for Continuous Integration and Continuous Deployment practices, tricks, and tips.

## Docker

### Run a local PostgreSQL container

Start the PostgreSQL container using Docker Compose:

```bash
docker compose -f docker/postgres/docker-compose.yaml up -d
```

Stop the PostgreSQL container using Docker Compose:

```bash
docker compose -f docker/postgres/docker-compose.yaml down
```
