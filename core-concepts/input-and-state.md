# Input and State

At the heart of Zentra’s functionality lies the concept of input and state, modeled using a state machine. While this concept might sound complex, it is straightforward to understand in practice.

**State Machine** Representation: A blockchain can be viewed as a state machine, where the state represents the current condition of the system, and transitions between states are triggered by inputs.

* **Inputs**: Users submit transactions as inputs, which are processed by the blockchain system to modify its **State**. Each transaction provides instructions that drive these state transitions.
* **Deterministic State Changes**: State machine ensures that state changes are deterministic, meaning that given the same inputs and current state, the state transition will always produce the fixed new state under the fixed **State Transfer Function**.

In blockchain, this concept corresponds to:

* **Input → Transaction**: A transaction serves as the input to the blockchain, triggering state changes. For example, a user sending a transfer or executing a function in a smart contract.
* **State → Global State**: The global state represents the collection of all accounts and smart contract storage on the blockchain. When transactions are executed, the blockchain’s global state updates accordingly.
* **State transition function → smart contracts:** When a transaction (input) is applied to the current global state, the smart contract executes predefined logic, updating the blockchain's state and producing a new global state.
