# Is Zentra a DA?

**What is a DA?**

A **DA** (Data Availability layer) is a concept in **modular blockchain architecture**. In modular blockchains, the responsibilities of a traditional monolithic blockchain are divided into separate layers, each specializing in a specific function. The DA layer focuses on ensuring that all the data required to verify the blockchain is readily available to all nodes in the network.

**Is Zentra a DA?**

No, **Zentra is not a DA**. Zentra does not follow the modular blockchain paradigm. Instead, Zentra is an **execution engine** and an **indexer** that complements blockchains while adhering to the principles of **Minus Theory**. Zentra views execution as an integral part of the blockchain system but positions it as a standalone component that works alongside blockchain nodes, rather than being split into multiple independent modules. With Zentra, a blockchain node could remove its **VM** and the **global state** completely but focus on storing messages/transactions.

**How Does Zentra’s Approach Differ from Modular Blockchain?**

In modular blockchain architectures, the blockchain system is divided into several layers, each handling a distinct function (e.g., consensus, execution, and data availability). Zentra takes a different approach:

1. **Lean Blockchain Philosophy:** According to Minus Theory, blockchains should remain lean and focus solely on their core purpose—achieving message consensus. This avoids unnecessary complexity within the blockchain itself.
2. **Standalone Execution:** Zentra provides execution as a **standalone component** that operates alongside blockchain nodes but remains a part of the broader blockchain system. This ensures that execution is tightly integrated with the blockchain while offloading the computational burden from consensus nodes.
3. **Unified Blockchain System:** Zentra believes the blockchain should be a cohesive module, not fragmented into separate layers like modular blockchain systems. The goal is to preserve the richness and integration of blockchain functionalities while offloading execution to dedicated components.

**Why Zentra is Not a DA or Modular Blockchain?**

* **Zentra’s Role:** Zentra focuses on **indexing and execution**, enabling blockchains to run complex applications without the constraints of gas limitations or heavy computation. Unlike a DA, it does not manage data availability but works with blockchain nodes to process data efficiently.
* **Avoiding Complexity:** Zentra follows Minus Theory, advocating that blockchains should avoid becoming overly complex by staying focused on their primary role—message consensus.
* **Execution Within the System:** While modular blockchains break functionalities into isolated layers, Zentra retains execution as a part of the blockchain system but implements it as a specialized, standalone component to maintain integration and efficiency.

