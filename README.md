## 운영 서버 도커 UP

```
docker compose up --build -d
```

## 개발 서버 도커 UP

```
docker compose -f docker-compose.dev.yml --env-file .env.dev up -d --build
```
