# Подготовка приложения к тестированию на PostgreSQL

Проект содержит настройку приложения `db-api.jar` для работы с СУБД PostgreSQL.

## Файлы
- `db-api.jar` — целевое приложение
- `application.properties` — настройки подключения к БД (хост, порт, БД, пользователь, пароль)
- `docker-compose.yml` — конфигурация контейнера PostgreSQL (образ 13-alpine)
- `.gitignore` — игнорируемые файлы

## Запуск

### 1. Запуск БД:
```bash
docker-compose up -d
```
### 2. Запуск приложения:
```bash
java -jar db-api.jar
```
### 3.  Проверка:
```bash
Открыть в браузере: http://localhost:9999/api/cards
```
### Скриншот ответа приложения:
```bash

```