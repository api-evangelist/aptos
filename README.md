# Aptos (aptos)

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

Aptos is a Move-based Layer 1 blockchain platform that exposes a REST API for reading on-chain state and submitting transactions, a GraphQL Indexer API for high-level queries over processed blockchain data (NFTs, objects, custom Move contracts), and a gRPC Transaction Stream for real-time and historical event feeds. Public endpoints are provided by Aptos Labs for mainnet, testnet, and devnet; enhanced rate limits are available through Geomi (formerly Aptos Labs Developer Portal).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aptos/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aptos/refs/heads/main/apis.yml)

## Tags

- Blockchain
- Web3
- Move
- Layer 1
- Cryptocurrency
- NFT
- Smart Contracts
- DeFi
- Transactions
- Accounts
- GraphQL
- gRPC

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Aptos Fullnode REST API

Low-latency REST API for reading on-chain state and submitting transactions to the Aptos blockchain. Endpoints cover accounts (authentication key, sequence number, resources, modules, balances), blocks (by height or ledger version), events, transactions (read, submit, simulate), table items, Move view functions, and node health/info. Available on mainnet, testnet, and devnet.

- **Human URL:** [https://aptos.dev/en/build/apis/fullnode-rest-api](https://aptos.dev/en/build/apis/fullnode-rest-api)
- **Base URL:** `https://api.mainnet.aptoslabs.com/v1`

#### Tags

- Accounts
- Transactions
- Blocks
- Events
- Modules
- Resources
- Move
- REST

#### Properties

- [Documentation](https://aptos.dev/en/build/apis/fullnode-rest-api)
- [API Reference](https://api.mainnet.aptoslabs.com/v1/spec)
- [OpenAPI](https://raw.githubusercontent.com/aptos-labs/aptos-core/main/api/doc/spec.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://geomi.dev/docs/api-keys)
- [Sandbox](https://api.testnet.aptoslabs.com/v1)
- [Graph Q L](graphql/aptos-graphql.md)

### Aptos Indexer GraphQL API

High-level GraphQL API backed by the Aptos Indexer, providing opinionated access to processed blockchain data. Optimized for querying NFTs, Aptos Objects, token balances, fungible assets, custom Move contract events, and account activities. Available on mainnet and testnet with optional API key from Geomi for elevated rate limits.

- **Human URL:** [https://aptos.dev/en/build/indexer/indexer-api](https://aptos.dev/en/build/indexer/indexer-api)
- **Base URL:** `https://api.mainnet.aptoslabs.com/v1/graphql`

#### Tags

- GraphQL
- NFT
- Objects
- Tokens
- Fungible Assets
- Indexer

#### Properties

- [Documentation](https://aptos.dev/en/build/indexer/indexer-api)
- [API Reference](https://aptos.dev/en/build/indexer/indexer-api/indexer-reference)
- [Authentication](https://geomi.dev/docs/api-keys)
- [Sandbox](https://api.testnet.aptoslabs.com/v1/graphql)
- [Graph Q L](graphql/aptos-graphql.md)

### Aptos Transaction Stream API

gRPC streaming API that delivers historical and real-time transaction data from the Aptos blockchain. Used to power the Aptos Core Indexer and to build custom app-specific real-time event processors. Available on mainnet, testnet, and devnet via grpc endpoints.

- **Human URL:** [https://aptos.dev/en/build/apis](https://aptos.dev/en/build/apis)
- **Base URL:** `https://grpc.mainnet.aptoslabs.com`

#### Tags

- gRPC
- Streaming
- Transactions
- Real-time
- Indexer

#### Properties

- [Documentation](https://aptos.dev/en/build/apis)
- [Authentication](https://geomi.dev/docs/api-keys)

### Aptos Faucet API

Testnet and devnet faucet that distributes APT test tokens for development and testing. Available programmatically on devnet; testnet faucet is accessible via the mint page. Not available on mainnet.

- **Human URL:** [https://aptos.dev/en/network/nodes/networks](https://aptos.dev/en/network/nodes/networks)
- **Base URL:** `https://faucet.devnet.aptoslabs.com`

#### Tags

- Faucet
- Testnet
- Devnet
- Test Tokens

#### Properties

- [Documentation](https://aptos.dev/en/network/nodes/networks)

## Common Properties

- [Portal](https://aptos.dev)
- [Documentation](https://aptos.dev/en/build/apis)
- [API Reference](https://api.mainnet.aptoslabs.com/v1/spec)
- [Getting Started](https://aptos.dev/en/build/get-started)
- [Sign Up](https://geomi.dev/)
- [Pricing](https://geomi.dev/pricing)
- [Rate Limiting](https://geomi.dev/docs/admin/billing)
- [Networks](https://aptos.dev/en/network/nodes/networks)
- [Blog](https://aptoslabs.medium.com)
- [Terms of Service](https://aptoslabs.com/terms)
- [Privacy Policy](https://aptoslabs.com/privacy)
- [GitHub Organization](https://github.com/aptos-labs)
- [OpenAPI](https://raw.githubusercontent.com/aptos-labs/aptos-core/main/api/doc/spec.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://github.com/aptos-labs/aptos-ts-sdk)
- [SDK](https://github.com/aptos-labs/aptos-python-sdk)
- [SDK](https://github.com/aptos-labs/aptos-go-sdk)
- [SDK](https://github.com/aptos-labs/aptos-core/tree/main/sdk)
- [Plans](plans/aptos-plans-pricing.yml)
- [Rate Limits](rate-limits/aptos-rate-limits.yml)
- [Fin Ops](finops/aptos-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
