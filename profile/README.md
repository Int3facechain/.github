## Welcome to BitFrost ☃️
![banner](./images/bitfrost.svg)
Product:
Bitfrost is a permissionless market creation platform for venues like Hyperliquid.  Users deposit assets from any blockchain to launch new markets and earn revenue as collective owners.

The infrastructure:
Bitfrost is a synthetic asset issuance platform built on a cross-chain state machine that enables native assets, real-world assets (RWAs), LSTs and LRTs to flow securely and efficiently into active DeFi venues on any chain.
Bitfrost introduces several key innovations in interoperability to ensure secure, capital-efficient synthetic issuance across chains:

- TSS vaults & authorization - Create 1:1, composable representations of native assets and move them reliably across chains. A supermajority TSS signatures secure external-chain events and enable direct redemption back to the native asset.

- Cross-chain state machine - Orchestrates state and events across external chains to maintain global consistency of all assets, preventing double spending or invalid duplication. The design minimizes fragmentation through a single pool and risk surface, with atomic burns/mints and inventory that rebalances to demand.

- Decentralized validator network - Supermajority TSS signatures secure external-chain events and enable direct redemption back to the native asset. The user always controls custody of their underlying asset through the TSS vaults.

- Direct market integration - Connects Bitfrost-issued assets directly to active DeFi markets, enabling an abstracted cross-chain user experience that supports yield-bearing strategies and direct deployment into liquidity.

- Institutional-grade capital efficiency - Allows assets to move across chains without KYC friction, MEV exposure, or unnecessary gas overhead, while preserving security and composability.

- Rapid chain and asset expansion - A custom Wormhole NTT integration allows Bitfrost to support many more assets and chains without compromising on security.

### Run a Node or a Validator
Please contact us in any way possible to include you in the network.

### Contribute to the Project
BitFrost's blockchain node implements the core protocol, written in Go using
[Cosmos SDK](https://github.com/cosmos/cosmos-sdk) and [Comet BFT](https://cometbft.com/). Protocol contracts implement the core protocol and are
deployed on BitFrost and on connected chains, written in Solidity. See the list
of pinned repos below for the projects to contribute to.

### Responsible Disclosure
If you’ve found a security issue or vulnerability in our project, we would love
to hear from you! Please let us know responsibly so we can fix it quickly and
keep the community safe.

