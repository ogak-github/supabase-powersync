# Supabase Docker + Powersync (Demo)

This is a minimal Docker Compose setup for self-hosting Supabase. Follow the steps [here](https://supabase.com/docs/guides/hosting/docker) to get started.


Run Command:
```bash
docker compose --env-file .env -f docker-compose.yml up -d
docker compose --env-file .env -f powersync-service.yml up -d
```
