# Docker

A collection of helpful `docker-compose.yml` files.

## Keycloak

https://www.keycloak.org/

**Pre-deployment checklist**

- [ ] Configure Keycloak for production environments [(guide)](https://www.keycloak.org/server/configuration-production)
- [ ] Change command from `start-dev` to `start`
- [ ] Update environment variables

**Run**

```bash
docker compose -f keycloak.docker-compose.yml up -d
```

## PostgreSQL

https://www.postgresql.org/ <br />
https://www.pgadmin.org/

**Pre-deployment checklist**

- [ ] Update environment variables for Postgres
- [ ] Update environment variables for PG Admin 4

**Run**

```bash
docker compose -f postgres.docker-compose.yml up -d
```

## Nudge

https://api.oliverknox.io/nudge-gateway/swagger-ui/index.html

**Pre-deployment checklist**

- [ ] Update environment variables

**Run**

```bash
docker compose -f nudge.docker-compose.yml up -d
```

## Portfolio

https://oliverknox.io/

**Pre-deployment checklist**

- [ ] Update environment variables

**Run**

```bash
docker compose -f portfolio.docker-compose.yml up -d
```