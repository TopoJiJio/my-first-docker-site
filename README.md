# My First Docker Site

Простой статический сайт на HTML, запущенный в Docker с помощью Nginx.

## Требования

- Docker Engine
- Docker Compose
- Доступ к терминалу

## Запуск проекта

Скачайте репозиторий:

```bash
git clone https://github.com/TopoJiJio/my-first-docker-site.git
```

Перейдите в папку проекта:

```bash
cd my-first-docker-site
```

Соберите образ и запустите сайт:

```bash
docker compose up -d --build
```

Откройте сайт в браузере:

http://localhost:8081

## Проверка состояния

```bash
docker compose ps
```

## Просмотр логов

```bash
docker compose logs
```

## Остановка сайта

```bash
docker compose down
```

