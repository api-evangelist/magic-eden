# Magic Eden (magic-eden)

Magic Eden is a multi-chain NFT marketplace offering REST and instruction-generation APIs for Solana, EVM chains (Ethereum, Polygon, Base, ApeChain, Arbitrum, Berachain, BSC, SEI, Abstract), and Bitcoin Ordinals (inscriptions, rare sats, and runes). Developers can fetch collections, tokens, listings, bids, activity, holder stats, AMM pool data, launchpad data, and generate signed transactions or PSBTs for listing, buying, bidding, transferring, swapping, and minting across all supported chains.

Aggregated OpenAPI specs for the Solana, EVM, and Bitcoin Ordinals/Runes surfaces are captured in [`openapi/`](openapi/).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/magic-eden/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=magic-eden-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Magic Eden Solana API** - REST endpoints and signed-transaction instruction generators for the Solana marketplace: collections, tokens, wallets, listings, bids, activity, MMM AMM pools, marketplace popular collections, and launchpad. Public reads are free at 120 QPM; instruction endpoints require a Bearer API key.
- **Magic Eden EVM API** - Reservoir-powered v4 REST API for EVM chains (Ethereum, Polygon, Base, ApeChain, Arbitrum, Berachain, BSC, SEI, Abstract) covering collections, user collections, search, NFT activity, asks (listings), bids (offers), assets, and signed-transaction instruction endpoints for bidding, listing, buying, selling, cancelling, and bulk transfers.
- **Magic Eden Bitcoin Ordinals & Runes API** - REST and PSBT-generation endpoints for the Bitcoin Ordinals marketplace: ordinal collections, block activities, rare sats batch listings, and full Runes lifecycle (orders, market sells, quotes, swaps, sweeping, wallet balances, and activities). Free tier limited to 30 QPM; instruction endpoints require Bearer auth.

## Tags
 - NFT, Web3, Blockchain, Marketplace, Solana, Ethereum, Bitcoin, Ordinals, Runes, Multi-chain

## Timestamps
- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## Common Properties
- [Website](https://magiceden.io)
- [Portal](https://docs.magiceden.io)
- [APIReference](https://docs.magiceden.io/reference/getting-started-1)
- [ChangeLog](https://docs.magiceden.io/changelog)
- [GitHubOrganization (magiceden)](https://github.com/magiceden)
- [GitHubOrganization (magicoss)](https://github.com/magicoss)
- [SDK (TypeScript)](https://github.com/magiceden/magiceden-sdk)
- [LLMsTxt](https://docs.magiceden.io/llms.txt)
- [TermsOfService](https://magiceden.io/terms-of-service.pdf)
- [BugBounty (HackerOne)](https://hackerone.com/magic-eden)
- [Discord](https://discord.com/invite/magiceden)
- [Plans](plans/magic-eden-plans-pricing.yml)
- [RateLimits](rate-limits/magic-eden-rate-limits.yml)
- [FinOps](finops/magic-eden-finops.yml)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
