# CI/CD Cheat Sheet

A quick personal reference guide for Continuous Integration and Continuous Deployment practices, tricks, and tips.

## Docker

### Dockerfile templates

Available templates:

- Angular:
  - `docker/angular/Dockerfile.pnpm`
- NestJS:
  - `docker/nest-js/Dockerfile.npm`

### Run a local PostgreSQL container

Start the PostgreSQL container using Docker Compose:

```bash
docker compose -f docker/postgres/docker-compose.yaml up -d
```

Stop the PostgreSQL container using Docker Compose:

```bash
docker compose -f docker/postgres/docker-compose.yaml down
```

## GitHub Actions

Take YAML files from the `github` directory and put them in your GitHub repository's `.github/workflows` directory to enable the corresponding CI/CD workflows.
