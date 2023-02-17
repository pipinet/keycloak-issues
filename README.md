### STEPS
- setup domain keycloak.banshan.ren to local  in /etc/hosts

- start keycloak with command
```shell
docker compose up -d
```
- login keycloak admin
- restart keycloak with command
```shell
docker compose down && docker compose up -d
```
- refresh web
- got 502
