# Lovelace card for Pandora CAS integration

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)
[![Donate](https://img.shields.io/badge/donate-Yandex-orange.svg)](https://money.yandex.ru/to/41001690673042)

![Screenshot](https://github.com/turbulator/pandora-cas-card/raw/master/images/screenshot.png)

## Установка

1. Добавить кастомный репозиторий https://github.com/turbulator/pandora-cas-card.git
2. Установить Pandora CAS card
3. В нужном месте lovelace добавить саму карточку, указав id своей машины

```
views:
  - name: Example
    cards:
      - type: 'custom:pandora-cas-card'
        pandora_id: 1234567890
```

Для затравочки вывел пока только статус охраны и двигатель.
