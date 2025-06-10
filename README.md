# Task-2
Blockchain Platform Comparison Table
| **Blockchain Name**    | **Type**   | **Consensus Mechanism**             | **Permission Model** | **Speed / Throughput (TPS)** | **Smart Contract Support**    | **Token Support** | **Typical Use Case**                  | **Notable Technical Feature**               |
| ---------------------- | ---------- | ----------------------------------- | -------------------- | ---------------------------- | ----------------------------- | ----------------- | ------------------------------------- | ------------------------------------------- |
| **Ethereum**           | Public     | Proof of Stake (PoS - Ethereum 2.0) | Open                 | \~30–100 TPS (Layer 1)       | Yes (Solidity, Vyper)         | Native (ETH)      | Decentralized apps (DeFi, NFTs)       | Smart contracts, EVM compatibility          |
| **Hyperledger Fabric** | Private    | Pluggable (default: Solo/Raft)      | Permissioned         | \~3,000 TPS                  | Yes (Chaincode: Go, Java, JS) | No native token   | Enterprise supply chain, healthcare   | Modular architecture, private channels      |
| **R3 Corda**           | Consortium | Notary-based (pluggable)            | Permissioned         | \~100–200 TPS                | Yes (JVM-based: Kotlin, Java) | No native token   | Inter-bank settlements, trade finance | Point-to-point transactions, strong privacy |


Short Report
Ethereum, Hyperledger Fabric, and R3 Corda each serve different blockchain needs due to their architecture, consensus, and permissioning models. Ethereum, a public blockchain, emphasizes decentralization and openness. Its Proof of Stake consensus provides moderate throughput and energy efficiency, and its support for smart contracts (in Solidity) and native tokens (ETH) makes it ideal for decentralized applications.

Hyperledger Fabric, a private blockchain, is optimized for enterprise use. It features pluggable consensus, high throughput (~3,000 TPS), and fine-grained access controls. While it lacks native tokens, its smart contracts (called chaincode) support multiple languages and benefit from Fabric’s modular, privacy-focused design.

R3 Corda, a consortium blockchain, targets financial institutions. It avoids broadcasting transactions to all nodes—instead, it enables point-to-point communication, enhancing privacy and scalability. Though it lacks native token support, it integrates tightly with financial systems and supports JVM-based smart contracts.
