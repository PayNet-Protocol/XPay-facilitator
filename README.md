# PayNet Facilitator

> Blockchain transaction verification service for the x402 payment protocol

PayNet is a facilitator service that verifies stablecoin transactions across multiple blockchains, enabling instant, programmatic payments for APIs and AI agents.

**Live Demo:** https://paynet.network

##  Features

- ✅ Multi-chain support (Solana, Base, Polygon, Avalanche)
- ✅ USDC verification in <1 second
- ✅ Replay attack prevention
- ✅ Production-ready x402 middleware
- ✅ RESTful API

##  Quick Start

Visit [paynet.network/quickstart](https://paynet.network/quickstart) for complete integration guide.

##  API Example

```bash
POST https://paynet.network/api/facilitator/verify

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
Website: https://paynet.network
Documentation: https://paynet.network/documentation
Live Demo: https://paynet.network/demo
Twitter: https://x.com/PayNetProtocol
📄 License
Apache 2.0
