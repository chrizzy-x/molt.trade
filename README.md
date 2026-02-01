# Molt.Trade 🤖

Molt.Trade is a configurable crypto trade automation web app designed for launchpads and decentralized exchanges (DEXs), with primary support for **Solana** and **Base** chains.

The app is built in **Python** using **Streamlit** for a user-friendly dashboard and supports **simulation mode by default** for safe testing.

---

## ✨ Features

### Wallet Management
- Create new wallets (Solana & Base)
- Connect existing wallets securely
- Private keys are never stored (session-only)

### Market & Meme Detection
- Scan X (Twitter) handles for new ticker mentions
- Detect early meme and launchpad tokens

### Chain Analysis
- Volume & liquidity tracking
- Holder concentration analysis
- Risk & rug detection signals

### Confidence Scoring
- 0–100% confidence score
- User-defined thresholds
- Adjustable risk controls

### Trade Automation
- Spot & perpetual trading
- Simulation mode (default)
- Optional live trading with explicit confirmation

### Supported Platforms
- Solana: Jupiter, Raydium, Pump.fun, Bags
- Base: Uniswap
- Perpetuals: SiloPerps

---

## 🛠 Tech Stack

- Python 3.10+
- Streamlit
- solana-py & solders
- web3.py
- pandas & numpy
- requests
- snscrape / X APIs (ethical use)

---

## 🚀 Getting Started

```bash
pip install -r requirements.txt
streamlit run molt_app.py
