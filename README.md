Create a **.env** file with this template:
```
COMPOSE_NAME={{ your value }}
NGINX_PORT={{ your value }}
```

Replace the variable values and run:
```
docker compose -f docker-compose.yaml --env-file .env up -d
```
