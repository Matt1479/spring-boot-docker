# Spring Boot Docker

This project demonstrates how to containerize and run a Spring Boot application using Docker. Docker Compose Watch is configured to rebuild the `api` service when files in `src/` change.

```bash
docker init
docker compose up --build --watch
docker compose up [--build]
docker compose watch
```

`docker compose up --build --watch` combines the following:

```bash
docker compose up --build
docker compose watch
```

Visit: `http://localhost:8080/api/`
