# Travel Vault — Dockerized Site

## Run with Docker Compose (recommended)
```bash
docker compose up --build
```
Visit http://localhost:8080

## Run with plain Docker
```bash
docker build -t travel-vault .
docker run -p 8080:80 travel-vault
```
Visit http://localhost:8080

## Files
- `index.html` — the site
- `Dockerfile` — nginx:alpine serving index.html
- `docker-compose.yml` — convenience runner (maps port 8080)
