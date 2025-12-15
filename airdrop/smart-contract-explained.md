# Smart Contract Explained

The staking airdrop uses non-upgradable contracts to ensure Zentra cannot access user funds. Key characteristics:

* **Fixed airdrop allocation**: 0.5% of total supply for direct airdrop; depletion ends the program, with timing recorded via on-chain events.
* **Option pool reserve**: Additional 5% of total supply reserved as an option pool; each airdropped token is paired with **10 option units** at a **$100 strike**. Rights persist even if principal is later withdrawn.
* **Funds × time accounting**: Airdrop accrues by “staked amount × duration” at a transparent baseline rate (every $1,000 stablecoin × 365 days = 1 Zentra token, delivered after TGE).
* **Monitoring & pause**: Contracts track remaining allocation and auto-pause new deposits near depletion. After pause, only principal withdrawals are allowed to prevent programmatic hoarding.
* **Flexible staking**: Deposit/withdraw anytime; no long-term lock.
* **Emergency withdraw logic**: Supports pulling funds from DeFi dependencies when risk is detected.
* **Risk boundary**: A base-chain or centralized L2 black-swan exploit/outage cannot be fully mitigated; participants should assess this residual risk.

Full contract code will be published ahead of launch for community review and audits.
