# Aptos GraphQL API

The Aptos Indexer GraphQL API provides high-level access to processed Aptos blockchain data. Backed by a Hasura GraphQL engine over the Aptos Indexer database, it exposes queryable tables covering token and NFT ownership, fungible asset balances, account transactions, staking and delegation, governance proposal votes, Aptos Name Service (ANS) lookups, Move table items, block and transaction metadata, and confidential asset activities. It is optimized for read-heavy applications such as NFT marketplaces, wallets, DeFi dashboards, and analytics tools that need aggregated, pre-indexed blockchain state rather than raw node data.

Authentication is optional for public rate limits. For elevated throughput, supply an API key from Geomi (formerly Aptos Labs Developer Portal) via the `Authorization: Bearer <API_KEY>` header.

**Endpoint:** https://indexer.mainnet.aptoslabs.com/v1/graphql

**Testnet Endpoint:** https://indexer.testnet.aptoslabs.com/v1/graphql

**Documentation:** https://aptos.dev/en/build/indexer/indexer-api

**References:**
- Documentation: https://aptos.dev/en/build/indexer/indexer-api
- APIReference: https://aptos.dev/en/build/indexer/indexer-api/indexer-reference
- GettingStarted: https://aptos.dev/en/build/get-started
- Authentication: https://geomi.dev/docs/api-keys
