<h1 align="center">Tomás Araújo</h1>

<h3 align="center">
Blockchain Engineer
</h3>

<p align="center">
Solidity • TypeScript • EVM • Protocol Architecture
</p>

---

## About

I design reliable EVM-based systems by combining smart contracts with backend infrastructure.

My work centers on protocol architecture, deterministic execution, state modeling, and event-driven systems, with an emphasis on clear boundaries between canonical on-chain state and derived application data.

I build modular blockchain systems that prioritize composability, security, and long-term maintainability.

---

## Technical Focus

### Protocol Engineering

- Protocol architecture and system design
- Deterministic execution models
- State machines and state transitions
- Financial primitives and protocol mechanisms
- Modular protocol components
- Separation between protocol state and application layers

---

### Smart Contracts

- Solidity development for EVM-compatible networks
- Smart contract architecture and composability
- Gas-aware contract design
- Contract testing with Foundry and Hardhat
- Security-conscious development
- OpenZeppelin-based implementations

---

### Blockchain Infrastructure

- Event-driven blockchain architectures
- Blockchain indexing pipelines
- Derived state management
- Off-chain services connected to smart contracts
- Transaction lifecycle management
- Backend infrastructure using TypeScript and Node.js

---

### Security & Verification

- Invariant-driven development
- Fuzz testing
- Static analysis
- Smart contract validation workflows

Tooling: Slither • Mythril

---

### Application Layer

- Web3 frontend applications
- Wallet-based authentication flows
- Blockchain transaction interfaces
- React and Next.js applications
- ethers.js integrations

---

## Projects

<details open>
<summary><b>ExeKPro</b> — Execution-Selection Protocol for Web3 Intents</summary>

<br/>

Execution-selection protocol for Web3 intents with modular strategies and deterministic scoring.

Competing execution modules are simulated and scored through a deterministic `ScorePolicy`, with the highest-scoring module executing on-chain through the protocol's `ExecutionEngine` kernel.

### Architecture

- Intent layer for standardized, owner-registered intent types
- On-chain `ExecutionEngine` kernel for scoring and executing candidate modules
- Modular execution modules competing for selection
- Deterministic scoring via `ScorePolicy`
- Observability and indexing layer for execution performance
- SDK layer for developer integration
- Separation between canonical protocol state and supporting execution/application services

**Stack**

`Solidity` • `Foundry` • `TypeScript` • `Node.js` • `viem` • `wagmi` • `Next.js` • `Cloudflare Workers`

</details>

---

<details>
<summary><b>Provenance Registry</b> — On-Chain Audit Provenance Layer</summary>

<br/>

An on-chain audit provenance registry for versioned protocol records, making document and artifact integrity cryptographically verifiable.

The system creates immutable, publicly verifiable references between off-chain artifacts and on-chain records using `keccak256` cryptographic commitments.

### Features

- On-chain protocol version registry
- Audit metadata storage
- Commit hash verification
- Timestamped blockchain records
- Cryptographic linking using `keccak256`

### Web3 Flow

`User → Wallet Authentication → Transaction Signing → Smart Contract Execution → Blockchain State Update → Frontend Synchronization`

**Stack**

`Solidity` • `Hardhat` • `React` • `TypeScript` • `Vite` • `TailwindCSS` • `ethers.js` • `Ethereum Sepolia`

</details>

---

<details>
<summary><b>StakeVerse</b> — DAO-Governed Staking and Governance Protocol</summary>

<br/>

DAO-governed staking and governance protocol with historical ERC20Votes voting power, protected reward accounting, and on-chain execution.

### Components

- DAO governance with on-chain proposal execution
- Historical, checkpointed voting power via ERC20Votes delegation
- Protected reward accounting
- Fixed-rate, time-locked staking and reward distribution
- Chainlink oracle integration for price data
- ERC-20 utility token
- ERC-721 membership NFT (secondary, non-gating credential)

### Engineering

- Modular smart contract architecture
- OpenZeppelin standards
- Automated contract testing
- Security analysis workflows
- Frontend wallet integration

**Stack**

`Solidity` • `Hardhat` • `OpenZeppelin` • `Chainlink` • `React` • `TypeScript` • `Vite` • `TailwindCSS` • `ethers.js v6` • `Slither` • `Mythril`

</details>

---

## Engineering Principles

### Architecture

- Deterministic systems
- Explicit state transitions
- Modular architecture
- Composable components
- Clear system boundaries

---

### Reliability

- Event-driven architectures
- Data consistency
- Predictable execution
- Security-first design

---

## Engineering Toolkit

| Domain | Technologies |
|---------|--------------|
| Smart Contracts | Solidity, Foundry, Hardhat, OpenZeppelin |
| Blockchain Infrastructure | TypeScript, Node.js, ethers.js, Event-Driven Systems |
| Frontend | React, Next.js, Vite, Wallet Integration |
| Tooling | Linux, Git, Docker, CI/CD |

---

<h2 align="center">Connect with Me</h2>

<p align="center">

<a href="https://linkedin.com/in/psatomas">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

<a href="mailto:psatomas@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
</a>

</p>
