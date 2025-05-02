# Genius Wallet

**Autonomous capital logic container built on ERC-3525.**

The Genius Wallet is an agentic AI framework designed to deploy modular, permissioned, and tokenized financial agents using the ERC-3525 token standard. It introduces a dynamic structure for trading agents, slot-based capital management, and a full logic governance layer via Agent Active Directory (AAD).

---

## 🔍 Overview

- **ERC-3525 Powered** — Tokenized strategy execution and fractional capital control.
- **Slot Bots** — Tactical agents deployed on demand via strategy-linked slot IDs.
- **Agent Active Directory (AAD)** — Role-based logic hierarchy with on-chain permissions, including multisig control.
- **Modular** — Plug-and-play architecture with support for custom strategy injection.
- **Auditable** — Full logs for trades, missed opportunities, and logic decisions.

---

## 📂 Project Structure

```
agent_wallet/
├── contracts/             # Solidity ERC-3525 + WalletAgent.sol
├── dashboard/             # CSV-based agent visualizer (FastAPI-ready)
├── diagrams/              # Architecture SVG + Agent Org Chart PNG
├── logs/                  # Example trading session logs
├── USE_CASE.md            # Practical use cases & flow explanations
├── README.md              # This file
├── LICENSE                # MIT License
└── whitepaper.pdf         # [Add here when uploaded]
```

---

## 🧠 Key Concepts

- **WalletAgent.sol**  
  A smart contract acting as the logic layer and identity for capital, implementing ERC-3525 and exposing up to 1000 function stubs for agent logic execution.

- **Slot Bots**  
  Snap-in tactical agents deployed under specific slot IDs with strategy and capital scoped permissions.

- **Agent Active Directory**  
  An on-chain role enforcement system. Agent One = admin logic. Slot Bots = scoped actors. Supports multi-agent approval for trades and asset operations.

---

## 📊 Use Cases

- Volatility-optimized capital deployment
- Missed profit tracking and regret analysis
- On-chain agent leasing and strategy tokenization
- Multi-agent logic routing with permission signatures

See [`USE_CASE.md`](USE_CASE.md) for full details.

---

## 🚀 Quick Start (Local)

1. Clone the repo  
   `git clone https://github.com/snaxx-snaxx/agent_wallet.git`
2. Install Python dashboard dependencies (optional)  
   `pip install -r dashboard/requirements.txt`
3. Run CSV visualizer  
   `python dashboard/csv_visualizer.py`

---

## 📄 Resources

- **Whitepaper** (Coming soon)
- **Résumé**: [Download Résumé (PDF)](https://yourlink.com/Agent_Snaxx_Resume.pdf) ← update this if needed
- **LinkedIn**: [Eric Wilson](https://www.linkedin.com/in/eric-wilson-944349193)
- **Twitter/X**: [@Agent_Snaxx](https://twitter.com/Agent_Snaxx)

---

## 🛡 License

MIT — free to fork, build, tokenize, and deploy. Just give Agent Snaxx his credit.

---
*Built for the post-SaaS world. Capital should think for itself.*
