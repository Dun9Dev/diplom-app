# Тестовое приложение для дипломной работы

Простой веб-сервер на nginx, отдающий статическую страницу.

## Сборка образа

```bash
docker build -t diplom-app:latest .
```

## Запуск локально

```bash
docker run -p 8080:80 diplom-app:latest
```

## Публикация в Container Registry

```bash
docker tag diplom-app:latest cr.yandex/<registry-id>/diplom-app:latest
docker push cr.yandex/<registry-id>/diplom-app:latest
```

## Версии

- v1.0.0 - initial release

# test
