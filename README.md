<h1 align="center">Tomás Araújo</h1>

<h3 align="center">
Blockchain Engineer
</h3>

<p align="center">
Solidity • TypeScript • EVM • Protocol Architecture
</p>

<p align="center">
<a href="https://psatomas.com">Portfolio</a>
</p>

---

## About

I build EVM protocols and supporting infrastructure across execution, state, governance, indexing, SDKs, and application-facing services.

I design around protocol guarantees: which state must be canonical, which data can be derived, how execution is constrained and verified, and where trust boundaries exist between on-chain and off-chain components.

I treat protocol engineering as systems engineering, emphasizing deterministic behavior, explicit state transitions, modular boundaries, observability, and security at the architectural level.

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

[Protocol Console](https://exekpro.com) · [Repository](https://github.com/psatomas/ExeKPro)

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

[Live App (Sepolia)](https://protocol-provenance-registry.vercel.app) · [Repository](https://github.com/psatomas/ProvenanceRegistry)

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

`Solidity` • `Hardhat` • `OpenZeppelin` • `Chainlink` • `React` • `TypeScript` • `Vite` • `TailwindCSS` • `ethers.js v6`

[Live App (Sepolia)](https://stakeverse.vercel.app/) · [Repository](https://github.com/psatomas/StakeVerse)

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
| Agent Orchestration | Workflow Engine, Claude Code, Codex CLI, Git Worktrees |
| Tooling | Linux, Git, Docker, CI/CD |

---

<h2 align="center">Connect with Me</h2>

<p align="center">

<a href="https://psatomas.com"><img src="assets/psat-mark.png" height="28" alt="PSAT"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge" height="28"></a>
<a href="https://linkedin.com/in/psatomas"><img src="assets/linkedin-badge.svg" height="28" alt="LinkedIn"></a>
<a href="mailto:psatomas@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="28"></a>

</p>
