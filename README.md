# Caddy for Remnawave

Обратный прокси для Remnawave на основе Caddy. Предназначен для запуска панели вместе с нодой на одном сервере. В такой конфигурации панель и подписки запускаются на кастомных портах, а Xray на 443 порту. Также предоставляется selfsteal заглушка, вам осталось положить свою статику в папку `html`.

## Установка и запуск

1. Склонируйте репозиторий:

```bash
git clone https://github.com/xxphantom/caddy-for-remnawave.git
cd caddy-for-remnawave
```

2. Скопируйте файл .env.sample и отредактируйте файл `.env`:

VIM

```bash
cp .env.sample .env
vim .env
```

- Поменяйте значения в `.env`:

3. Запустите проект:

```bash
docker compose up -d
```
