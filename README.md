# Docker Practice

Учебный проект: веб-страница в Docker на базе Nginx.

## Сборка образа

docker build -t my-docker-site:1.0 .

## Запуск контейнеров

docker run -d --name site1 -p 8081:80 my-docker-site:1.0
docker run -d --name site2 -p 8082:80 my-docker-site:1.0

## Адреса

- http://localhost:8081
- http://localhost:8082
