# docker-postgresql

PostgreSQL Docker Image with the latest PostgreSQL 9.3 from apt.postgresql.org

## Usage

1. Run this image, e.g.
  `docker run -d -name postgresql zumbrunnen/postgresql`
2. Connect to it via link or with `psql`:

```
psql -h <containerip> -U docker
docker run -d -link postgresql:db <otherimage>
```
Use `docker` as username and password.
