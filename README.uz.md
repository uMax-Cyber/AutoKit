<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>

# AutoKit — Python avtomatlashtirish skriptlari

Amaliy avtomatlashtirish skriptlari toʻplami: belgilangan vaqtda kompyuterni masofadan yoqish (Wake-on-LAN), UniFi API orqali tarmoq qurilmalarini boshqarish va Telegramga avtomatik xabar yuboruvchi xizmat.

## ℹ️ Legacy loyiha

Bu — ilk avtomatlashtirish skriptlari toʻplami, havola va tarix uchun saqlanadi. Faol qoʻllab-quvvatlanmaydi. Avtomatlashtirishning zamonaviy, ishonchli yondashuvlari yangi repozitoriyalarda (OpsPlaybook va boshqalar).

## Skriptlar

| Skript | Vazifasi |
|--------|----------|
| `python_wol_8_00.py` | Wake-on-LAN — belgilangan vaqtda kompyuterlarni yoqadi |
| `unifi_api_block_unblock.py` | UniFi API orqali tarmoq qurilmasini bloklash/ochish |
| `telegram-autosend` | Telegramga avtomatik xabar yuboradi |
| `autosend.service` | Avtomatik yuborish xizmati uchun systemd unit |

## Skrinshot

![Namoyish](screenshots/demo.svg)

## Foydalanish

```bash
# Wake-on-LAN soat 08:00 da (cron)
0 8 * * * python3 python_wol_8_00.py

# Qurilmani UniFi orqali bloklash/ochish
python3 unifi_api_block_unblock.py --mac AA:BB:CC:DD:EE:FF --action block

# Xizmatni ishga tushirish
systemctl start autosend
```

## Litsenziya
GPL-3.0 — batafsil [LICENSE](LICENSE) faylida

## 📬 Aloqa
📧 **[allumaxmail@gmail.com](mailto:allumaxmail@gmail.com)**

---

<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>
