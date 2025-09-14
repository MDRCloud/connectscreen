# rsupport (self-hosted remote support)


MVP monorepo with backend (Go), agent (Rust), SFU (Go + Pion), frontend (React/TS), and deploy (Compose + Helm).


## Quick start (dev)


```bash
cp .env.example .env
make dev # or docker compose -f deploy/docker-compose.dev.yml up --build
