# Staking Airdrop (Stage 2, opens with mainnet)

Zentra's Stage 2 airdrop starts with mainnet, using a fixed **0.5% airdrop + 5% option pool** and a “funds × time” model, delivered via non-upgradable smart contracts to keep principal safe.

## Core Rules

* **Fixed allocation**: 0.5% of total supply (~105,000 tokens) for the airdrop, and an additional 5% reserved as the option pool. Depletion and pause are recorded and triggered by on-chain events.
* **Funds × time accrual**: Baseline rate is **every 1,000 USD stablecoin × 365 days = 1 Zentra token (delivered after TGE)** to keep participant cost equal. Funds can be deposited or withdrawn anytime before depletion.
* **Option bonus**: For each airdropped token you also get **10 option units** with a **$100 strike**, drawn from the 5% pool; exercise is optional, no upfront payment, and rights persist even if you withdraw principal later.
* **Dynamic depletion**: As total staking grows, tokens are consumed faster and the window shortens. The contract monitors remaining allocation and will pause new deposits before depletion.
* **After pause**: Only principal withdrawals are allowed; no new deposits.

## Flexible Participation

* **Flexible staking**: Deposit or withdraw anytime; no long lock-ups.
* **Multi-chain support**: Available on multiple Ethereum-compatible chains.

## Security and Transparency

* **Non-upgradable contracts**: Zentra cannot touch staked funds.
* **Open code**: Contracts will be published before launch for community audit.
* **Emergency withdraw logic**: Built-in path to pull funds from DeFi in emergencies; cannot eliminate systemic risk from a base chain or centralized L2 black swan.
