# HyperSPEED-contracts 🚗💨

Welcome to the engine room of **HyperSPEED**, the fastest token launchpad on Hyperliquid EVM. This repo holds the smart contracts that power token creation, pre-sales, and SPEED-seeded liquidity pools. Built for speed and thrill, HyperSPEED is here to turbocharge the HyperEVM ecosystem. Ready to race? Let’s dive in!

## What’s HyperSPEED?
HyperSPEED is a platform where anyone can launch tokens on Hyperliquid EVM, fueled by the **SPEED** token. Pre-sales let users grab allocations, and every launch gets a SPEED-paired liquidity pool. These contracts are the heart of it all—high-performance, self-sustaining, and ready to roll.

## Repo Structure
- `/contracts/`: Core Solidity contracts.
  - `SPEED.sol`: The SPEED token (ERC-20) that drives the ecosystem.
  - `PreSale.sol`: Manages token pre-sales with SPEED.
  - `LaunchPad.sol`: The main hub for launching tokens.
  - `LiquidityPool.sol`: Handles SPEED-based liquidity pools.
- `/test/`: Unit tests to keep the engine humming.
- `/scripts/`: Deployment and utility scripts for HyperEVM.

## Getting Started
### Prerequisites
- [Foundry](https://github.com/foundry-rs/foundry) (recommended) or [Hardhat](https://hardhat.org/)
- Node.js (v16+)
- A HyperEVM testnet RPC endpoint (grab one from the Hyperliquid docs)

### Setup
1. **Clone the repo**:
   ```bash
   git clone https://github.com/HyperSPEEDxyz/HyperSPEED-contracts.git
   cd HyperSPEED-contracts
   ```
2. **Install dependencies**:
   - With Foundry: `forge install`
   - With Hardhat: `npm install`
3. **Build the contracts**:
   - Foundry: `forge build`
   - Hardhat: `npx hardhat compile`
4. **Run tests**:
   - Foundry: `forge test`
   - Hardhat: `npx hardhat test`

### Deploying to HyperEVM
1. Configure your `.env` file with:
   ```env
   HYPEREVM_RPC_URL=<your-testnet-rpc>
   PRIVATE_KEY=<your-wallet-key>
   ```
2. Deploy with:
   - Foundry: `forge script scripts/Deploy.s.sol --rpc-url $HYPEREVM_RPC_URL --private-key $PRIVATE_KEY --broadcast`
   - Hardhat: `npx hardhat run scripts/deploy.js --network hyperevm`

## Contributing
Want to tune the engine? We’re open to PRs! Here’s how:
1. Fork the repo.
2. Create a branch (`git checkout -b feature/turbo-boost`).
3. Commit your changes (`git commit -m "Added turbo boost feature"`).
4. Push it (`git push origin feature/turbo-boost`).
5. Open a PR and tell us what you’ve revved up.

Focus areas:
- Optimizing gas for HyperEVM.
- Enhancing security (audits welcome!).
- Adding features like governance or staking.

## Roadmap
- **Q1 2025**: Testnet deployment, SPEED token airdrop prep.
- **Q1 2025**: Mainnet launch with pre-sales and pools.
- **Q2 2025**: Advanced features (TBD based on community input).

## Questions?
Hit up the team: [@McqueenHL](https://twitter.com/mcqueenhl), [@0xSallyHL](https://twitter.com/0xSallyHL), or [@MaterHL](https://twitter.com/MaterHL). Let’s build the fastest launchpad in DeFi together!

---

