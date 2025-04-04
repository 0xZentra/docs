# Python Bytecode

Python, with its 30 years of active development and multiple redesigns, has established itself as one of the most popular and versatile programming languages in the world. Known for its simplicity, readability, and broad ecosystem, Python has become a preferred choice for developers across many domains, from web development to machine learning and now, blockchain programming.

Zentra’s approach to integrating Python into blockchain development is unique in that it does not rely on creating a new compiler, which **reduced the huge security risk**. Instead, Zentra directly converts Python source code into [python bytecode](https://docs.python.org/3.10/library/dis.html), ensuring seamless execution within the blockchain environment.

In Zentra’s architecture, Python code plays a critical role as the **state transfer function** on the blockchain, ensuring that each Zentra indexer node runs the same code for the blockchain inputs. This guarantees consistency and determinism across the entire blockchain network, a fundamental requirement for maintaining trust and integrity in decentralized systems.

By leveraging Python's mature language design, Zentra effectively capitalizes on the stability and robustness of Python's ecosystem. Developers can focus on the business logic and complex computations of blockchain applications without worrying about reliability of language infrastructure. People can also program blockchain in languages ​​they are familiar with.

Zentra's security model revolves around the thesis that the **programming language used for blockchain smart contracts should be readable by as many people as possible**, even if they are not the ones who originally wrote the code. This philosophy stems from the belief that **the more people who can review the code, the more secure the system becomes**. In other words, increasing the visibility and comprehensibility of the code directly contributes to its security, as more eyes can detect vulnerabilities, inefficiencies, or malicious logic.
