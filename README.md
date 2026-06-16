# Aptos (aptos)

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
