# 🔎 Solana Wallet Discord Tracker

A lightweight **Discord bot** that tracks **Solana wallets** in real-time.  
It fetches balances, token holdings, and live market data using **Solana RPC**, **CoinGecko**, and **Dexscreener** APIs, then displays everything directly in your Discord server.

---

## 🚀 Features

- **Track Solana Wallets**
  - `!track <wallet_address>` → start tracking a wallet
  - Displays **SOL balance**, USD equivalent, and total wallet value
  - Automatically fetches token balances and prices

- **View Current Positions**
  - `!show_positions` → show all token positions of the tracked wallet
  - Fetches **price (USD)**, **market cap**, and **current value**
  - Provides a **Dexscreener link** for quick research

- **Real-Time Data**
  - **CoinGecko API** → current SOL price in USD  
  - **Solana JSON-RPC** → wallet SOL + token balances  
  - **Dexscreener API** → token price & market cap  

- **Discord Commands**
  - `!track <wallet_address>` → track a Solana wallet  
  - `!show_positions` → show token positions  
  - `!help` → list available commands  

- **Portfolio Summary**
  - Calculates **total USD value** of SOL + tokens  
  - Tracks invested vs. remaining token values (in memory)  

---

## 🛠 Tech Stack

- **Python 3**
- **discord.py** → Discord bot framework  
- **requests** → API requests  
- **Solana JSON-RPC** → wallet & token balances  
- **CoinGecko API** → SOL/USD price feed  
- **Dexscreener API** → token market data  

---
