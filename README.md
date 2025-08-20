<h1 align="center">Solmate</h1>

<p align="center">
  Solana developer ergonomics. Minimal, composable TypeScript SDK.
</p>

## What it is
- **TypeScript-first** SDK for Solana (Node + browser).
- Focused on **fees/landing reliability**: compute units, priority fee, retries, optional Jito tips.
- Small modules, typed APIs, no hidden state.

## Principles
- Modular code
- SOLID Standard

## Modules
**Current**
- `fees`: CU & priority-fee estimation, retry/backoff, optional tips
- `tx-builder`: compute-budget helpers, v0 messages/LUTs (basics)
- `confirm`: confirmation policies & receipts (basics)

**Next**
- `actions`: server helpers for Actions/Blinks
- `token-extensions`: Token-2022 (hooks, fees, confidential)
- `compression`: cNFT/zk-compression proof helpers
- `mev`: Jito transport/bundles
- `index`: light clients for Geyser/Read APIs
- `standards`: utilities aligned to active SIMDs

## Install
