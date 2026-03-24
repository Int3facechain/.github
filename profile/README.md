## Welcome to BITFROST ☃️
![banner](./images/bitfrost.svg)

BitFrost is a clearing architecture for fragmented digital asset markets. It is built for a world in which collateral, leverage, execution, and liquidity are distributed across centralized exchanges, decentralized lending venues, and autonomous financial agents.

Traditional systems margin locally, liquidate locally, and source capital locally. That model is operationally simple, but economically inefficient: it ignores portfolio offsets, duplicates collateral requirements, and constrains balance sheet scaling.

### The Infrastructure

BitFrost provides a fully integrated infrastructure that unifies four previously disconnected concerns:

- **BitFrost Prime** — Venue-facing master accounts with tiered auto-deleveraging (ADL) isolation. Prime connects to external exchanges and manages position lifecycle, margin allocation, and ADL defense across venues.

- **Unified Clearing Engine** — Computes portfolio-level margin, nets risk across venues, and actively manages ADL exposure through position resets that simultaneously serve as hedge rebalancing operations.

- **Curated Vaults** — Morpho-style curated vault infrastructure supplies programmable external capital. Capital providers compete to finance strategies, while BitFrost allocates and risk-manages their deployment. 

### The Product

The first use case is the **carry trade**: a collateral or spot leg combined with a hedged short perpetual or futures leg to capture funding or basis yield.

BitFrost transforms this from a fragmented treasury workflow into a programmable clearing product.

### Contribute to the Project
BitFrost's blockchain node implements the core protocol, written in Go using
[Comet BFT](https://cometbft.com/). Protocol contracts implement the core protocol and are
deployed on BitFrost and on connected chains, written in Solidity. See the list
of pinned repos below for the projects to contribute to.

### Responsible Disclosure
If you’ve found a security issue or vulnerability in our project, we would love
to hear from you! Please let us know responsibly so we can fix it quickly and
keep the community safe.

