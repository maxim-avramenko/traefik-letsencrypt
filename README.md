```bash
cp .env.dist .env

docker network creatre traefik

docker compose pull

touch letsencrypt/acme.json

chmod 600 letsencrypt/acme.json

docker compose up -d
```