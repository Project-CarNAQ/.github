# .github

# CarNAQ

**Blockchain-based, Shariah-compliant asset tokenization of car ownership**

[![Status](https://img.shields.io/badge/status-in%20development-yellow)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()
[![Blockchain](https://img.shields.io/badge/chain-Polygon-8247E5)]()
[![Shariah](https://img.shields.io/badge/finance-Shariah--compliant-2ECC71)]()

---

## What is CarNAQ?

CarNAQ turns real vehicles into fractionally-owned digital assets, letting multiple investors co-own a car and earn a share of the income it generates — without interest-based (Riba) financing.

Car ownership in Pakistan is out of reach for most people: conventional auto loans run 16–22% APR, and religious objections to interest exclude a large share of potential buyers and investors outright. Informal shared-ownership arrangements exist, but they run on trust alone, with no transparent record of income or ownership.

CarNAQ replaces that with:

- **Fractional ownership** — vehicles are minted as blockchain tokens, and investors buy a share
- **Shariah-compliant financing** — Musharakah, Diminishing Musharakah, and Ijarah contracts instead of interest-based loans
- **Automated, transparent payouts** — smart contracts distribute profit to token holders on-chain, no intermediary
- **Optional usage rights** — an Ijarah-based time-sharing module lets token holders book the vehicle itself

## 🧩 How it works

```
Car Owner  →  lists vehicle, chooses financing model
Investors  →  buy fractional tokens representing ownership %
Smart Contracts → collect revenue, distribute profit, manage buybacks
Admin      →  verifies documents, monitors for fraud
```

## 🏗️ Architecture

| Layer | Technology |
|---|---|
| Blockchain | Polygon (primary), Ethereum (secondary) |
| Smart contracts | Solidity, ERC-1155 |
| Backend | Node.js, Express.js |
| Frontend | React.js, Ethers.js / Web3.js |
| Wallets | MetaMask, WalletConnect |
| Data | PostgreSQL, MongoDB / IPFS |

## 📂 Repositories

| Repo | Description |
|---|---|
| `carnaq-contracts` | Solidity smart contracts (tokenization, profit distribution, buybacks, Ijarah booking) |
| `carnaq-backend` | REST API, revenue simulation engine, KYC flow |
| `carnaq-frontend` | Investor & owner web app, marketplace, dashboards |
| `carnaq-docs` | Proposal, architecture docs, Shariah compliance notes |

*(Repos are added as they go live — this list will grow.)*

## 🕌 Shariah compliance, by design

CarNAQ is built to actively avoid the three core prohibitions in Islamic finance:

- **No Riba** — profit/loss sharing replaces interest
- **No Gharar** — all contract terms are disclosed upfront and enforced on-chain
- **No Maysir** — every token is backed by a real, registered, insured vehicle

## 🗺️ Status

This project is currently a Final Year Project (FYP) at the National University of Computer and Emerging Sciences (FAST-NUCES), Lahore — in active development. Not yet production-ready or audited.

## 🤝 Contributing

CarNAQ isn't open for external contributions yet while the core team finalizes the FYP scope, but feel free to open an issue with questions or feedback.

## 📄 License

MIT — see individual repositories for details.

---

<div align="center">
<sub>Built by the CarNAQ team · Lahore, Pakistan</sub>
</div>
A brief description of what this project does and who it's for

