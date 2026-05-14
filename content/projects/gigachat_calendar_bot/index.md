---
title: GigaChat Calendar Bot
date: 2025-05-14
summary: Телеграм-бот для управления расписанием с интеграцией GigaChat API.
tags:
  - Python
  - GigaChat
  - LangChain
  - Telegram
  - AI

links:
  - name: GitHub
    icon: brands/github
    url: https://github.com/tsypinda/gigachat-calendar-bot
    icon_pack: fab

  - name: Release
    icon: hero/rocket-launch
    url: https://github.com/tsypinda/gigachat-calendar-bot/releases/tag/v1.0.0

image:
  filename: featured.png
  caption: ""
  focal_point: Smart

weight: 10
---

Бот-помощник для управления расписанием с интеграцией GigaChat API.

## Функционал

- Добавление, удаление и просмотр событий
- Режим академического чата с GigaChat
- Ежедневная автоматическая рассылка расписания

## Технологии

- Python
- GigaChat API (LangChain)
- PyTelegramBotAPI
- APScheduler
- Pydantic

## Как это работает

Пользователь отправляет команду боту, например `/calendar`, затем пишет "добавь математику 25.05.2025 в 10:30". GigaChat распознаёт команду и сохраняет событие в JSON-файл. В 17:44 бот автоматически присылает расписание на следующий день.
