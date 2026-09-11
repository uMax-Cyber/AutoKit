<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>

# AutoKit — Скрипты автоматизации на Python

Коллекция практичных скриптов автоматизации: Wake-on-LAN по расписанию, управление устройствами через UniFi API и Telegram-демон автоотправки сообщений.

## ℹ️ Архивный проект

Это ранняя коллекция скриптов автоматизации, сохранённая для справки и истории. Она не поддерживается активно. Продуктовые подходы-преемники для автоматизации живут в более новых репозиториях (OpsPlaybook и другие).

## Скрипты

| Скрипт | Назначение |
|--------|-----------|
| `python_wol_8_00.py` | Wake-on-LAN — включение машин по расписанию |
| `unifi_api_block_unblock.py` | Блокировка/разблокировка сетевых устройств через UniFi API |
| `telegram-autosend` | Автоматическая отправка сообщений в Telegram |
| `autosend.service` | systemd-юнит для демона автоотправки |

## Скриншот

![Демонстрация](screenshots/demo.svg)

## Использование

```bash
# Wake-on-LAN в 8:00 утра (cron)
0 8 * * * python3 python_wol_8_00.py

# Блокировка/разблокировка устройства через UniFi
python3 unifi_api_block_unblock.py --mac AA:BB:CC:DD:EE:FF --action block

# Запуск демона автоотправки
systemctl start autosend
```

## Лицензия
GPL-3.0 — см. [LICENSE](LICENSE)

## 📬 Контакты
📧 **[allumaxmail@gmail.com](mailto:allumaxmail@gmail.com)**

---

<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>
