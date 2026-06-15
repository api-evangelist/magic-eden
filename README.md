# Magic Eden (magic-eden)

Magic Eden is a multi-chain NFT marketplace offering REST and instruction-generation APIs for Solana, EVM chains (Ethereum, Polygon, Base, ApeChain, Arbitrum, Berachain, BSC, SEI, Abstract), and Bitcoin Ordinals (inscriptions, rare sats, and runes). Developers can fetch collections, tokens, listings, bids, activity, holder stats, AMM pool data, launchpad data, and generate signed transactions or PSBTs for listing, buying, bidding, transferring, swapping, and minting across all supported chains.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/magic-eden/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/magic-eden/refs/heads/main/apis.yml)

## Tags

- NFT
- Web3
- Blockchain
- Marketplace
- Solana
- Ethereum
- Bitcoin
- Ordinals
- Runes
- Multi-chain

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Magic Eden Solana API

REST endpoints and signed-transaction instruction generators for the Solana marketplace - collections, tokens, wallets, listings, bids, activity, MMM AMM pools, marketplace popular collections, and launchpad. Public reads are free at 120 QPM; instruction endpoints require a Bearer API key.

- **Human URL:** [https://docs.magiceden.io/reference/solana-api-keys](https://docs.magiceden.io/reference/solana-api-keys)
- **Base URL:** `https://api-mainnet.magiceden.dev/v2`

#### Tags

- REST
- Solana
- Instructions
- MMM

#### Properties

- [Documentation](https://docs.magiceden.io/reference/solana-api-keys)
- [OpenAPI](openapi/magic-eden-solana-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/magic-eden-solana.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magic-eden-solana.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.magiceden.io/reference/solana-api-keys)

### Magic Eden EVM API

Reservoir-powered v4 REST API for EVM chains (Ethereum, Polygon, Base, ApeChain, Arbitrum, Berachain, BSC, SEI, Abstract) covering collections, user collections, search, NFT activity, asks (listings), bids (offers), assets, and signed-transaction instruction endpoints for bidding, listing, buying, selling, cancelling, and bulk transfers.

- **Human URL:** [https://docs.magiceden.io/reference/evm-api-overview](https://docs.magiceden.io/reference/evm-api-overview)
- **Base URL:** `https://api-mainnet.magiceden.dev/v4/evm-public`

#### Tags

- REST
- EVM
- Reservoir
- Multi-chain

#### Properties

- [Documentation](https://docs.magiceden.io/reference/evm-api-overview)
- [OpenAPI](openapi/magic-eden-evm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/magic-eden-evm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magic-eden-evm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.magiceden.io/reference/evm-api-keys)

### Magic Eden Bitcoin Ordinals & Runes API

REST and PSBT-generation endpoints for the Bitcoin Ordinals marketplace - ordinal collections, block activities, rare sats batch listings, and full Runes lifecycle (orders, market sells, quotes, swaps, sweeping, wallet balances, and activities). Free tier limited to 30 QPM; instruction endpoints require Bearer auth.

- **Human URL:** [https://docs.magiceden.io/reference/ordinals-api-keys](https://docs.magiceden.io/reference/ordinals-api-keys)
- **Base URL:** `https://api-mainnet.magiceden.dev/v2`

#### Tags

- REST
- Bitcoin
- Ordinals
- Runes
- PSBT

#### Properties

- [Documentation](https://docs.magiceden.io/reference/ordinals-api-keys)
- [OpenAPI](openapi/magic-eden-ordinals-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/magic-eden-ordinals.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magic-eden-ordinals.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.magiceden.io/reference/ordinals-api-keys)

## Common Properties

- [Website](https://magiceden.io)
- [Portal](https://docs.magiceden.io)
- [API Reference](https://docs.magiceden.io/reference/getting-started-1)
- [Getting Started](https://docs.magiceden.io/reference/getting-started-1)
- [Changelog](https://docs.magiceden.io/changelog)
- [GitHub Organization](https://github.com/magiceden)
- [GitHub Organization](https://github.com/magicoss)
- [SDK](https://github.com/magiceden/magiceden-sdk)
- [L L Ms Txt](https://docs.magiceden.io/llms.txt)
- [Terms of Service](https://magiceden.io/terms-of-service.pdf)
- [Bug Bounty](https://hackerone.com/magic-eden)
- [Discord](https://discord.com/invite/magiceden)
- [Plans](plans/magic-eden-plans-pricing.yml)
- [Rate Limits](rate-limits/magic-eden-rate-limits.yml)
- [Fin Ops](finops/magic-eden-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
