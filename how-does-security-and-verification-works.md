# How Do Security and Verification Work?

Security is the foundation of any blockchain system. As the blockchain OS Layer, Zentra’s security spans several dimensions, including:

* Theoretical foundations
* Security of the underlying L1 or L2 networks
* Zentra system security
* Programming language security


### Theoretical foundations

Zentra was created as an implementation of [Minus Theory](https://github.com/0xZentra/whitepaper). More precisely, Minus Theory is based on the textbook State Machine Theory. (See  [State Machine Overview](https://zentra.gitbook.io/dev/state-machine) for more detail.)

A solid mathematical foundation ensures that security is built into Zentra's design from inception. Zentra's Minus Theory is grounded in classic State Machine Theory, providing rigorous mathematical underpinnings for deterministic results. Any honest individual running an unmodified Zentra indexer, given the same block order, will always produce the same state result due to its deterministic nature, unless a hardware error occurs.&#x20;

Like Bitcoin, Zentra relies on the majority of consensus participants acting honestly. However, it extends this model with universal verifiability: anyone can run a Zentra indexer locally to recompute the state from consensus-ordered blocks and identify malicious indexers providing false results through Merkle proofs, multiple indexer checks, or fraud proofs.

Zentra removes the state root (Merkle trie) to unlock performance, contrasting Ethereum's three locks that include state immutability and concurrency constraints. This simplification enhances efficiency while maintaining security through decoupled execution.

### Security of the underlying L1 or L2 networks

Zentra is a blockchain OS Layer, not a standalone L1 or L2. We borrow existing world computers for consensus, rely on them for immutable blocks, and keep the option to switch to better bases.

If an upstream chain hard forks or reorganizes, Zentra recomputes those blocks to update state; if a faster or more decentralized L1 appears, we can migrate to that world computer while carrying the ecosystem forward.
### Zentra system security

Security challenges increase in complexity when moving from theory to engineering.

The Zentra system may contain bugs during the engineering process. However, the strength of **decoupling consensus from computation** is that the blocks are frozen by the underlying world computer while we retain OS Layer autonomy. Zentra can fix bugs, replay all transactions, and recover the correct state; when the base chain is more centralized, we can still run decentralized indexers and collaborate with more decentralized L1s.

### Programming language security

Modern blockchain systems and cryptography are generally robust, but attackers continually look for vulnerabilities in immature or unstable designs, including those introduced by programming languages. For example, recent exploits in the Vyper compiler and the Move language on Sui highlight how language-level flaws can undermine blockchain security.

For this reason, Zentra does not attempt to create a new programming language. Instead, it chooses a well-designed, mature language —Python—and brings it into the blockchain ecosystem. This aligns with Minus Theory’s principle of minimizing complexity and avoiding unnecessary verification burdens.

As a dynamic language, Python allows developers to focus on high-level business logic without worrying about low-level type conversions. Python’s integers are arbitrary-precision, eliminating issues such as converting `uint128` to `uint64`. While static analysis in compiled languages can detect many issues before runtime, Python avoids lengthy compilation and shifts emphasis toward thorough test coverage, which complements Zentra’s off-chain computation model.

A key security advantage in Zentra’s model is code readability. Significantly fewer developers are fluent in C++ or Rust compared to Python, meaning a larger pool of programmers can review and audit Python-based smart contract code. This broader accessibility increases the likelihood of detecting vulnerabilities and strengthens the overall security model.

## Developer Confidence and Mainnet Launch

Zentra's simple design, built from Minus Theory's foundations, instills confidence in its security. After thorough testnets, mainnet launched with real funds, demonstrating trust in the system. While confident, we invite feedback on potential attack vectors—provide specific steps, and we'll address them to improve Zentra.
