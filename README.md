Create a **.env** file with this template:
```
MYSQL_PORT={{ your value }}
ADMINER_PORT={{ your value }}
```

Replace the variable values and run:
```
docker compose -f docker-compose.yaml --env-file .env up -d
```
