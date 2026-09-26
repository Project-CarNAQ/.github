<div align="center">

"<img width="125" height="125" alt="Designer (2)" src="https://github.com/user-attachments/assets/b2411569-6c06-4485-9c23-d8717eaf8421"/>

### Blockchain-based, Shariah-compliant Asset Tokenization of Car Ownership

*Turning cars into fair, transparent, halal investments*

<br/>

[![Status](https://img.shields.io/badge/status-in%20development-F5B700?style=flat-square)]()
[![License](https://img.shields.io/badge/license-MIT-2ECC71?style=flat-square)]()
[![Blockchain](https://img.shields.io/badge/chain-Polygon-8247E5?style=flat-square)]()
[![Smart Contracts](https://img.shields.io/badge/contracts-Solidity-363636?style=flat-square)]()
[![Shariah](https://img.shields.io/badge/finance-Shariah--compliant-2ECC71?style=flat-square)]()
[![University](https://img.shields.io/badge/FYP-FAST--NUCES-blue?style=flat-square)]()

[About](#-about) • [How It Works](#-how-it-works) • [Islamic Finance Models](#-islamic-finance-models) • [Architecture](#%EF%B8%8F-architecture) • [Repositories](#-repositories) • [Roadmap](#%EF%B8%8F-roadmap) • [Contributing](#-contributing)

</div>

---

## 🚗 About

CarNAQ turns real vehicles into fractionally-owned blockchain tokens, letting multiple investors co-own a car and earn a share of the income it generates — with no interest-based (Riba) financing. Financing is structured around Musharakah, Diminishing Musharakah, and Ijarah, and profit distribution is automated through smart contracts.

|  | |
|---|---|
| 🪙 **Fractional ownership** | Vehicles are minted as blockchain tokens; investors buy a share, not the whole car |
| 🕌 **Shariah-compliant** | Musharakah, Diminishing Musharakah & Ijarah — no interest, ever |
| 🔗 **Automated payouts** | Smart contracts distribute profit to token holders, no intermediary |
| 🔑 **Optional usage rights** | An Ijarah-based time-sharing module lets token holders book the vehicle itself |
| 🛡️ **Fraud-resistant** | Revenue simulation, reputation staking, and on-chain audit trails |

## 🧩 How It Works

```
┌─────────────┐        ┌──────────────────┐        ┌──────────────────┐
│  Car Owner  │──────▶ │   Smart Contract  │◀────── │     Investors    │
│             │  lists    (tokenizes         buy    │                  │
│             │  vehicle   vehicle,           tokens │                  │
│             │            manages revenue)          │                  │
└─────────────┘        └──────────────────┘        └──────────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │  Automated profit split   │
                    │  + Diminishing Musharakah │
                    │    buyback schedule       │
                    └─────────────────────────┘
```

1. **List** — a car owner lists a vehicle and chooses a financing model
2. **Fund** — investors buy fractional tokens representing ownership %
3. **Earn** — vehicle income (ride-hailing, rental, Ijarah bookings) is deposited on-chain and split automatically
4. **Verify** — every transaction, distribution, and buyback is recorded immutably

## 🕌 Islamic Finance Models

| Contract | Role in CarNAQ |
|---|---|
| **Musharakah** | Joint ownership — owner contributes the vehicle, investors contribute capital, profit and loss are shared proportionally |
| **Diminishing Musharakah** | The owner gradually buys back investor shares over time until reaching full ownership |
| **Ijarah** | A lease structure that powers the optional time-sharing module — usage rights, not just income rights |

Every design decision actively avoids the three core prohibitions in Islamic finance:

- ❌ **Riba** (interest) → replaced by profit/loss sharing
- ❌ **Gharar** (excessive uncertainty) → all terms disclosed upfront and enforced on-chain
- ❌ **Maysir** (speculation) → every token is backed by a real, registered, insured vehicle

## 🏗️ Architecture

| Layer | Technology |
|---|---|
| ⛓️ Blockchain | Polygon (primary), Ethereum (secondary) |
| 📜 Smart contracts | Solidity, ERC-1155 |
| ⚙️ Backend | Node.js, Express.js |
| 🖥️ Frontend | React.js, Ethers.js / Web3.js |
| 👛 Wallets | MetaMask, WalletConnect |
| 🗄️ Data | PostgreSQL, MongoDB / IPFS |
| 💳 Payments | JazzCash / EasyPaisa on-ramp, USDT settlement |

## 👥 Status

CarNAQ is currently a **Final Year Project (FYP)** at the National University of Computer and Emerging Sciences (**FAST-NUCES**), Lahore, Pakistan — actively in development. It is a prototype, not yet audited or production-ready.

## 🤝 Contributing

CarNAQ isn't open for external contributions yet while the core team finalizes the MYP scope — but questions, feedback, and issue reports are always welcome. Open an issue on any repository above.

## 📄 License

Released under the [MIT License](LICENSE) — see individual repositories for specifics.

---

<div align="center">

**Built with 🤍 in Pakistan for WORLD**

<sub>CarNAQ — halal ownership, on-chain.</sub>

</div>
