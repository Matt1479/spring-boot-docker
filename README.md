# Spring Boot Docker

This project demonstrates how to containerize and run a Spring Boot application using Docker. Docker Compose Watch is configured to rebuild the `api` service when files in `src/` change.

Check out the `dev` branch for the development setup using Spring Boot DevTools and Docker Compose Watch.

```bash
docker init
docker compose up --build --watch
```

`docker compose up --build --watch` combines the following:

```bash
docker compose up --build
docker compose watch
```

Visit: `http://localhost:8080/api/`

## Tech Stack

- Java 25
- Spring Boot 4.1.2
    - Spring Web
