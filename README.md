# XPay Facilitator

> Blockchain transaction verification service for the x402 payment protocol

XPay is a facilitator service that verifies stablecoin transactions across multiple blockchains, enabling instant, programmatic payments for APIs and AI agents.

**Live Demo:** https://chargexpay.com

##  Features

- ✅ Multi-chain support (Solana, Base, Polygon, Avalanche)
- ✅ USDC verification in <1 second
- ✅ Replay attack prevention
- ✅ Production-ready x402 middleware
- ✅ RESTful API

##  Quick Start

Visit [chargexpay.com/quickstart](https://chargexpay/quickstart) for complete integration guide.

##  API Example

```bash
POST https://chargexpay.com/api/facilitator/verify

{
  "hash": "transaction_hash",
  "amount": "1000000",
  "network": "solana",
  "token": "USDC"
}

Supported Networks
Solana (USDC) - 32 confirmations
Base (USDC) - 12 confirmations
Polygon (USDC) - 20 confirmations
Avalanche (USDC) - 15 confirmations
🔗 Links
Website: https://chargexpay.com
Documentation: https://chargexpay.com/documentation
Live Demo: https://chargexpay.com/demo
Twitter: https://x.com/xpay402
📄 License
Apache 2.0
