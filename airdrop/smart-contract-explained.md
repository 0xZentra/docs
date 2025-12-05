# Smart Contract Explained

The staking airdrop uses non-upgradable contracts to ensure Zentra cannot access user funds. Key characteristics:

* **Funds × time accounting**: Airdrop accrues by “staked amount × duration” at a transparent baseline rate (every $1,000 stablecoin × 365 days = 1 Zentra token, delivered after TGE).
* **Option issuance**: Each airdropped token is paired with **10 option units** at a **$100 strike**; exercise is optional and not prepaid.
* **Monitoring & pause**: Contracts track remaining airdrop allocation and auto-pause new deposits near depletion. After pause, only principal withdrawals are allowed to prevent programmatic hoarding.
* **Flexible staking**: Deposit/withdraw anytime; no long-term lock.
* **Emergency withdraw logic**: Supports pulling funds from DeFi dependencies when risk is detected.
* **Risk boundary**: A base-chain or centralized L2 black-swan exploit/outage cannot be fully mitigated; participants should assess this residual risk.

Full contract code will be published ahead of launch for community review and audits.
