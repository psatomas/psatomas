# Tomás Araújo

<h3 align="center">
Web3 Engineer  
(Solidity • TypeScript • Smart Contracts • Execution Layer)
</h3>

---

## Focus

Design and development of Web3 systems, combining smart contracts with robust off-chain execution layers. Emphasis on reliable contract interaction, event-driven architectures, and clear separation between on-chain logic and off-chain processing.

---

## Areas of Work

- Smart contract development in Solidity (EVM)
- Contract testing and validation using Foundry
- Development workflows and scripting with Hardhat
- Blockchain interaction and event handling via ethers.js
- Off-chain execution and data processing using Node.js
- Event indexing and persistence strategies (PostgreSQL)
- Frontend integration with React for contract interaction
- Wallet-based authentication and transaction flow with MetaMask

---

## Projects

### DeFi Micro SaaS

- Modular DeFi system built on deterministic on-chain vault and staking primitives, combined with an event-driven off-chain execution layer, deployed across EVM-compatible L2 environments such as Arbitrum and Optimism.
- Transactions emit events that drive execution pipelines, handling transaction lifecycle (pending → confirmed) and ensuring consistency between canonical on-chain state and derived data.
- The system enforces a strict separation between canonical on-chain state and derived off-chain representations, explicitly accounting for L2-specific constraints such as batched execution, calldata-driven cost models, and delayed finality in state propagation.

### Protocol Engineering Lab

- Exploration of protocol primitives and blockchain system design, focused on understanding execution-layer mechanics and how low-level decisions shape higher-level behavior.
- Study of state models, contract patterns, and system invariants, analyzing how protocols manage and transition state under deterministic execution constraints.
- Investigation of data structures and low-level EVM execution concepts, including storage layout, memory behavior, and gas implications.
- Solidity-based experiments to validate protocol mechanics, test edge cases, and observe how design choices impact execution semantics and system properties.

### Web3 Status Registry dApp

- Web3 application demonstrating end-to-end contract interaction and state persistence across client and blockchain layers.
- Users connect via MetaMask and initiate transactions that interact with deployed contracts, enabling read and write operations on on-chain state.
- Application state is synchronized through contract reads and transaction feedback, handling the asynchronous lifecycle (submission → confirmation) to maintain a consistent user experience.
- On-chain data serves as the canonical source of truth, with the interface reflecting state changes as they are finalized on the network. 

---

## Stack

**Smart Contracts**  
Solidity • Foundry • Hardhat • OpenZeppelin

**Backend**  
Node.js • TypeScript • ethers.js • PostgreSQL  

**Frontend**  
React • MetaMask  

**Infrastructure**  
Docker • Linux • Git  

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/psatomas)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&fs=1&to=psatomas@gmail.com)
