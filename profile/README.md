# P2Pay

Open-source, settlement-first Bitcoin payment infrastructure for merchants who want to accept fiat and crypto while receiving final settlement in bitcoin.

P2Pay is a modular, self-custodial payment architecture built around BTCPay Server, Bitcoin rails, and peer-to-peer integrations. It is designed for cross-border, censorship-resistant, and operationally difficult payment environments.

---

## Focus

P2Pay is currently focused on three codebases:

- **mono** — the main repository where active development happens
- **wallet** — the mobile wallet repository, based on an Aqua fork
- **miniapp** — an upcoming Nuxt mini app that will run inside the wallet

Older experiments and split repositories are no longer the center of development.

---

## Core Principles

- **Settlement-first** — bitcoin is the final settlement layer
- **Multi-rail** — fiat, cards, P2P, and crypto can be used as entry rails
- **Self-custodial by default**
- **Vendor-neutral**
- **KYC-free where legally possible**
- **Built for failure scenarios, not demo environments**

---

## What P2Pay aims to solve

P2Pay is built for cases where traditional payment stacks break down:

- merchants that need fiat reach without fiat custody
- cross-border businesses with unreliable banking access
- high-risk but legal industries
- users in emerging markets
- builders who want modular Bitcoin-native payment infrastructure

---

## Architecture

P2Pay is not a traditional payment processor. It is a modular payment architecture where multiple rails can be combined, while keeping bitcoin as the final settlement layer.

Current and planned components include:

- BTCPay Server integration
- Bitcoin on-chain payments
- Lightning support
- USDt rails
- P2P fiat-to-BTC flows
- booking and invoicing flows
- embeddable Nuxt interfaces
- wallet-connected signing flows
- API-first integrations

---

## Active Repositories

## [mono](https://github.com/p2payto/mono)
Main P2Pay repository.

This is where active development now happens. It contains the core application logic, rail integrations, payment flows, shared utilities, and app surfaces such as the dashboard and future mini app integrations.

## [wallet](https://github.com/p2payto/wallet)
Mobile wallet repository based on an Aqua fork.

The wallet is used for merchant-controlled signing and self-custodial payment flows. It is part of the broader P2Pay architecture, not a standalone generic wallet product.

## [miniapp](https://github.com/p2payto/miniapp)
Upcoming Nuxt mini app for the wallet.

This app is being prepared as a lightweight embedded interface inside the wallet, extending P2Pay flows through a wallet-native Nuxt experience.

---

## Development Status

- active development is concentrated in **mono**
- the **wallet** remains a core part of the architecture
- **miniapp** is the next app surface being added
- the project is evolving toward a tighter repo structure with fewer moving parts

---

## Support

- [Discussions](https://github.com/orgs/p2payto/discussions)
- [Telegram group](https://t.me/P2PayTo)

---

## Commercial advisory

P2Pay is open-source infrastructure under active development.

Commercial architecture advisory, integration design, and implementation support may be offered separately where relevant.

For teams looking for production-ready, commercial payment architecture solutions today,
Blockchange provides independent multi-rail payment advisory:
https://www.blockchange.expert/en/#book



