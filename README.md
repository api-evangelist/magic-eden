# Magic Eden (magic-eden)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
