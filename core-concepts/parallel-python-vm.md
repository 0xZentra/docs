# Parallel VM

Python VM is a powerful programming language, but when execution pressure shifts from nodes to the indexer, a large number of transactions that can be agreed upon in consensus to form a block must still be executed one by one in the execution layer to update the global state.

Since execution can be deferred, the execution time is not constrained by block intervals. However, if users have to wait too long to confirm whether their transactions are successful, it negatively impacts user experience.

To address this, **Zentra introduces a parallel Python VM** to accelerate global state updates after consensus, ensuring faster transaction finality while maintaining scalability.
