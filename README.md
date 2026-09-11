<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>

# AutoKit — Python Automation Scripts

Collection of practical automation scripts: Wake-on-LAN scheduling, UniFi API device management, and Telegram auto-messaging daemon.

## ℹ️ Legacy Project

This is an early collection of automation scripts, kept for reference and history. It is not actively maintained. The production-grade successor approaches for automation live in the newer repositories (OpsPlaybook and others).

## Scripts

| Script | Purpose |
|--------|---------|
| `python_wol_8_00.py` | Wake-on-LAN — powers on machines at scheduled time |
| `unifi_api_block_unblock.py` | Block/unblock network devices via UniFi API |
| `telegram-autosend` | Automated Telegram message sender |
| `autosend.service` | systemd unit for auto-send daemon |

## Screenshot

![Demo](screenshots/demo.svg)

## Usage

```bash
# Wake-on-LAN at 8:00 AM (cron)
0 8 * * * python3 python_wol_8_00.py

# Block/unblock device via UniFi
python3 unifi_api_block_unblock.py --mac AA:BB:CC:DD:EE:FF --action block

# Start auto-send daemon
systemctl start autosend
```

## License
GPL-3.0 — see [LICENSE](LICENSE)

## 📬 Contact
📧 **[allumaxmail@gmail.com](mailto:allumaxmail@gmail.com)**

---

<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>
