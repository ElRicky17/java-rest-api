# Java REST API

A backend REST API built with **Java** and **Maven**, containerized with **Docker**.

---

## Project Structure

```
java-rest-api/
├── src/                    # Application source code
├── .github/workflows/      # GitHub Actions CI configuration
├── Dockerfile              # Docker image definition
├── docker-compose.yml      # Multi-container Docker setup
├── pom.xml                 # Maven dependencies and build config
├── .env.example            # Environment variable template
└── .gitignore
```

---

## Requirements

- Java 21+
- Docker + Docker Compose

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ElRicky17/java-rest-api.git
   cd java-rest-api
   ```

2. Set up environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

3. Build and start the containers:
   ```bash
   docker-compose up --build
   ```

The API will be available at the URL defined in `docker-compose.yml`.
