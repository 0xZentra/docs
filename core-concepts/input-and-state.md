# Input and State

At the heart of Zentra’s functionality lies the concept of input and state, modeled using a state machine. While this concept might sound complex, it is straightforward to understand in practice.

**State Machine Representation**: A blockchain can be viewed as a state machine, where the state represents the current condition of the system, and transitions between states are triggered by inputs (transactions).

* **Inputs**: Users submit transactions as inputs, which are processed by the blockchain system to modify its **State**. Each transaction provides instructions that drive these state transitions.
* **Deterministic State Changes**: State machine ensures that state changes are deterministic, meaning that given the same inputs and current state, the state transition will always produce the fixed new state under the fixed **State Transfer Function**.

