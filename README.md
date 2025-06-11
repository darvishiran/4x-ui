[English](/README.md) | [فارسی](/README.fa_IR.md) | [العربية](/README.ar_EG.md) |  [中文](/README.zh_CN.md) | [Español](/README.es_ES.md) | [Русский](/README.ru_RU.md)

# 🌐 3X-UI Enhanced — Modern Xray Panel with Smart Access & Parental Controls

> A fully upgraded and refactored fork of the original [3x-ui](https://github.com/MHSanaei/3x-ui) with enhanced security, usability, and a powerful new **Parental Control System**.

[English](/README.md) | [فارسی](/README.fa_IR.md) | [العربية](/README.ar_EG.md) |  [中文](/README.zh_CN.md) | [Español](/README.es_ES.md) | [Русский](/README.ru_RU.md)

---

## 🚀 What's New in This Fork?

- ✨ Fully redesigned backend structure with more stable service handling
- 🧠 **Parental Control System**:
  - Domain-level logging
  - Time-based access rules
  - Category-based content filtering
  - Usage reports for each user (daily/weekly)
- 🔒 Advanced traffic rules per user (IP, Geo, bandwidth)
- 📊 Modern dashboard with real-time stats & charts
- 🔧 Protocols: VMess, VLess, Trojan, Shadowsocks, WireGuard
- 📅 Expiration and usage limit per user
- 📦 Docker-ready and easily extensible
- 🧪 Intelligent traffic anomaly detection (coming soon)

---

## 📦 Supported Protocols

| Protocol     | TLS | Non-TLS | Reality |
|--------------|-----|---------|---------|
| VMess        | ✅   | ✅       | ✅       |
| VLess        | ✅   | ✅       | ✅       |
| Trojan       | ✅   | ✅       | ❌       |
| Shadowsocks  | ✅   | ✅       | ❌       |
| WireGuard    | N/A | ✅       | ❌       |

---

## ⚡ Quick Start

### Install via Shell
```bash
bash <(curl -Ls https://raw.githubusercontent.com/darvishiran/4x-ui/main/install.sh)

