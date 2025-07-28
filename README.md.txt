# Crypto Wallet Balance Scanner

A simple Python tool that generates random Binance Smart Chain (BSC) and Ethereum wallet addresses and checks if they have any balance (BNB, ETH, USDT, BUSD, MATIC, etc.).

> ⚠️ **Warning**: This is for educational purposes only. The chance of finding a funded wallet is practically zero.

## 🚀 Features
- Generates random crypto wallets
- Checks BNB, ETH, and popular tokens (USDT, BUSD, USDC, DAI, MATIC)
- Uses BscScan & Etherscan APIs
- Lightweight and offline key generation
- Easy to run with Python

## 🛠 Requirements
- Python 3.7+
- `eth-keys`, `requests`

## 💾 Install & Run
```bash
git clone https://github.com/GBran88/crypto-wallet-scanner.git
cd crypto-wallet-scanner
pip install -r requirements.txt
python wallet_scanner.py