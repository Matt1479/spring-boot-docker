# Spring Boot Docker

This project demonstrates how to containerize and run a Spring Boot application using Docker. Docker Compose Watch is configured to sync changes in `src/` to the `api` service, recompile the application, and restart it using Spring Boot DevTools.

```bash
docker init
docker compose up --build --watch
```

Visit: `http://localhost:8080/api/`

## Tech Stack

- Java 25
- Spring Boot 4.1.2
    - Spring Web
    - Spring Boot DevTools
