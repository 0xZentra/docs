# App State

The **global state** is sufficient for simple applications, such as token management. However, in more complex applications, excessive use of the global state may lead to the inefficient consumption of public resources.

To address this, we introduce the concept of **local state**, which we define as **App State** for better clarity.

* **An indexer must store the global state** to ensure consistency across the network.
* **Storing AppState is optional**, allowing indexers to manage storage resources efficiently.
* **App State (local state) cannot affect the global state**, ensuring that it remains isolated and does not compromise the integrity of the blockchain.

By introducing App State, Zentra provides a scalable way to support complex applications while optimizing resource utilization. Meanwhile, with this design, it is also possible to bring Zentra Tokenomic paradigm to Zentra apps.
