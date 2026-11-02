# GitHub Actions + Docker Demo

Пример простого CI/CD пайплайна с использованием GitHub Actions.

При каждом `git push` в ветку `main` автоматически запускается сборка Docker-образа.

## Что использовано
- GitHub Actions
- Docker
- Nginx
- HTML

## Как работает

1. Ты делаешь изменения в коде
2. Выполняешь `git push`
3. GitHub Actions автоматически:
   - Скачивает код
   - Собирает Docker-образ

## Структура проекта

- `.github/workflows/docker-build.yml` — конфигурация CI/CD
- `Dockerfile` — инструкция по сборке образа
- `index.html` — веб-страница
