# Running Jenkins in Docker

## Run Jenkins

```sh
docker compose up -d
```

## Unlock Jenkins

```sh
docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
```
