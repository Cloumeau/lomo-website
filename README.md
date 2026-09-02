# Christopher Loumeau — Portfolio

A lightweight, responsive portfolio website packaged as a portable Docker image.

## Run locally

```bash
docker compose up --build
```

Open <http://localhost:8080>. The health endpoint is available at `/health`.

## Build and run the image

```bash
docker build -t lomo-website .
docker run --rm -p 8080:8080 lomo-website
```

The container runs as an unprivileged user and listens on port `8080`.
