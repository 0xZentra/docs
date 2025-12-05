# Is Zentra Decentralized?

**What Does Decentralization Mean in Zentra?**

In Zentra, decentralization means that **everyone can run a Zentra indexer with limited hardware resources.** This keeps the execution and indexing components of the blockchain OS Layer accessible, resilient, and free from centralized control—regardless of how decentralized the upstream world computer (L1 or L2) is.

**Does Zentra Care if the Upstream Blockchain is Decentralized?**

Zentra is designed to function independently of the decentralization status of the upstream blockchain, whether it is a **Layer 1 (L1)** or **Layer 2 (L2).** While Zentra acknowledges the ideal scenario of a **purely decentralized Layer 1 with low access fees**, its primary focus is on maintaining its own decentralized nature. Zentra can run on relatively centralized world computers while partnering with more decentralized L1s and can switch to better bases when they arrive.

**How Does Zentra Maintain Its Decentralization?**

1. **Decentralized Indexers with Minimal Hardware Requirements:**\
   Zentra indexers can run on limited hardware, ensuring that participation is open to anyone. This lightweight infrastructure design promotes decentralization by lowering entry barriers for participants.
2. **Independence from Upstream Blockchain Design:**\
   Zentra’s indexing and execution layer components are standalone and decentralized, ensuring that the upstream blockchain’s architecture or control model does not compromise Zentra’s decentralization.
3. **Support for Diverse Blockchain Environments:**\
   Zentra is compatible with both decentralized and centralized blockchains, adapting to various blockchain ecosystems without compromising its core principles. This flexibility allows Zentra to serve as a robust execution and indexing layer for a wide range of applications.

#### Comparing Zentra Indexer to Inscription Indexers

**Inscription Indexers**

* **Rule Variability:** In inscription systems, the indexing rules may differ depending on the source code maintained by different teams. This variability can lead to inconsistencies in indexing results across different implementations.
* **Decentralization Challenge:** The lack of a unified standard makes it harder to achieve deterministic results across all indexers. This can introduce trust issues, as users may question the correctness or fairness of the indexing process.

**Zentra Indexers**

* **Unified Rule via STF:** Zentra introduces a standardized **State Transfer Function (STF)**, which is the Python code deployed on the **global state**. This STF acts as the definitive rule for all Zentra indexers, ensuring uniformity in computation.
* **Deterministic Results:** All Zentra indexers rely on the same Python version with standardized behavior. As a result, every indexer processes blockchain inputs in an identical manner, guaranteeing deterministic outputs.
* **Trust and Consistency:** Zentra’s approach eliminates discrepancies caused by differing codebases. This ensures all indexer runners produce the same results, reinforcing trust in the system’s integrity.
