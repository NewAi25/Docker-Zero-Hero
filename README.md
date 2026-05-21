# Docker — Zero to Hero

A personal learning repository for going from absolute beginner to confident user of Docker, covering containers, images, volumes, networks and Compose.

## What's inside

Notes, commands, Dockerfiles and small exercises that build up Docker knowledge step by step.

## Roadmap

Install Docker and verify the daemon. Run your first container with `docker run`. Build your first image with a Dockerfile. Persist data with volumes. Connect containers using networks. Orchestrate multi-container apps with Docker Compose. Push images to a registry such as Docker Hub or GHCR.

## Useful commands

```bash
docker --version
docker run hello-world
docker build -t myapp:1.0 .
docker images
docker ps -a
docker exec -it <container> sh
docker compose up -d
docker compose down
```

## Goals

Use Docker confidently in day-to-day development. Build small, secure, layered images. Understand the difference between images, containers, volumes and networks. Be ready to use Docker in CI/CD pipelines.

## License

MIT
