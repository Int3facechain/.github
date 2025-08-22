## Welcome to BitFrost 👋
![banner](./images/bitfrost.svg)
Early multichain growth created real diversity, and a serious mobility problem for capital. Stranded across L1s and L2s, rebalancing takes hours, fees are volatile, and the UX breaks down after a few steps. Moving between Ethereum, Solana, and Bitcoin still
means stitching together multiple custodians, interfaces, and fee layers costing both yield and time. Until liquidity fragmentation is addressed at the primitive layer, DeFi cannot scale to mainstream adoption. Bitfrost is a unified liquidity layer to solve
this problem in a multichain world. 

The solution:
One pool, one risk surface. BitFrost’s unified liquidity layer, built on Threshold Signature Schemes (TSS) and [Wormhole’s Native Token Transfers](https://wormhole.com/products/native-token-transfers) standardizes the path assets take
across both account and non-account based chains:
1. Unified deposits. Any connected chain → TSS vault → fungible receipt token.
2. Atomic transfers. Burn receipt → Wormhole message → release native asset on destination.
3. Automatic rebalancing. Contracts maintain vault ratios and move inventory where demand appears.
4. On‑chain governance. DAOs encode limits, pause conditions, and slashing rules at the protocol layer.
The result is one pool of liquidity spanning all connected chains, one set of controls, and one operational surface – all without the overhead of multiple one‑off integrations.


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

