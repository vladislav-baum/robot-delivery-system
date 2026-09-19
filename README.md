# robot-delivery-system

Небольшой учебный проект для управления роботом доставщика. Здесь ты соберешь HTTP service на Python и по шагам добавишь базовую основу для SLAM и Computer vision в будущем. В процессе ты потренируешься работать с request handling и простой структурой проекта.

## How to run

`python -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt && python src/main.py`

## Tasks

1. Настроить стартовый каркас проекта: healthcheck endpoint, README и базовый entry point.
2. Реализовать core endpoint для POST и GET только на stdlib.
3. Добавить validation, обработку ошибок и простое хранение состояния.

## Концепции, которые отрабатываются

- [TCP: надёжная доставка](https://mind-forge.ru/lesson/net-15-tcp-basics)
- [HTTP: язык веба](https://mind-forge.ru/lesson/net-21-http-basics)
- [HTTP заголовки](https://mind-forge.ru/lesson/net-22-http-headers)
- [Кеширование](https://mind-forge.ru/lesson/sd-07-caching)
- [API Gateway](https://mind-forge.ru/lesson/sd-11-api-gateway)
