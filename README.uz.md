<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>

# AutoKit — Python avtomatlashtirish skriptlari

Amaliy avtomatlashtirish skriptlari toʻplami: reja boʻyicha Wake-on-LAN, UniFi API orqali qurilmalarni boshqarish va Telegram avto-xabar yuboruvchi demon.

## ℹ️ Legacy loyiha

Bu — havola va tarix uchun saqlanib qolgan erta davrdagi avtomatlashtirish skriptlari toʻplami. Faol ravishda qoʻllab-quvvatlanmaydi. Avtomatlashtirish uchun mahsulot darajasidagi voris yondashuvlar yangi repozitoriyalarda joylashgan (OpsPlaybook va boshqalar).

## Skriptlar

| Skript | Vazifasi |
|--------|----------|
| `python_wol_8_00.py` | Wake-on-LAN — reja boʻyicha mashinalarni yoqish |
| `unifi_api_block_unblock.py` | UniFi API orqali tarmoq qurilmalarini bloklash/ochish |
| `telegram-autosend` | Telegramga avtomatik xabar yuborish |
| `autosend.service` | Avto-yuborish demoni uchun systemd unit |

## Skrinshot

![Namoyish](screenshots/demo.svg)

## Foydalanish

```bash
# Wake-on-LAN soat 8:00 da (cron)
0 8 * * * python3 python_wol_8_00.py

# Qurilmani UniFi orqali bloklash/ochish
python3 unifi_api_block_unblock.py --mac AA:BB:CC:DD:EE:FF --action block

# Avto-yuborish demonini ishga tushirish
systemctl start autosend
```

## Litsenziya
GPL-3.0 — [LICENSE](LICENSE) faylini qarang

## 📬 Aloqa
📧 **[allumaxmail@gmail.com](mailto:allumaxmail@gmail.com)**

---

<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>
