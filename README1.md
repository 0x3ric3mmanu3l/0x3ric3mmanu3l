"0x3ric3mmanu3l" — Full-Stack Web3 Developer

Building the decentralized web, one block at a time.

<p align="center">
  <img src="https://img.shields.io/badge/Web3-Ethereum%20%7C%20EVM-8B5CF6?style=for-the-badge" alt="Web3 Ethereum EVM"/>
  <img src="https://img.shields.io/badge/Smart%20Contracts-Solidity%20%7C%20Foundry-F59E0B?style=for-the-badge" alt="Smart Contracts"/>
  <img src="https://img.shields.io/badge/Full%20Stack-Next.js%20%7C%20TypeScript-111827?style=for-the-badge" alt="Full Stack"/>
  <img src="https://img.shields.io/badge/Focus-Open%20Source-10B981?style=for-the-badge" alt="Open Source"/>
</p><p align="center">
  <b>Smart Contracts · dApps · DeFi · Blockchain Infrastructure · Web3 Security</b>
</p>I'm a Web3 developer focused on building decentralized applications, secure smart contracts, and full-stack blockchain products. My interests span the entire Web3 application lifecycle — from designing responsive interfaces and integrating wallets to developing on-chain logic, engineering backend services, testing protocol behavior, and deploying applications to decentralized networks.

I believe great Web3 engineering requires more than writing smart contracts. It requires understanding how frontend applications, wallets, RPC providers, backend systems, cryptographic primitives, and blockchain execution work together to deliver reliable products.

My goal is to build software that is secure, composable, transparent, accessible, and useful beyond the blockchain itself.

- Primary ecosystem: Ethereum and EVM-compatible blockchains
- Smart contract development: Solidity, Foundry, Hardhat, OpenZeppelin
- Frontend engineering: TypeScript, React, Next.js
- Web3 application integration: Wagmi, Viem, WalletConnect
- Systems programming interests: Rust and blockchain infrastructure
- Engineering interests: DeFi, protocol design, security research, account abstraction, and decentralized infrastructure
- Open to: Remote Web3 developer roles, smart contract development, dApp engineering, and open-source collaboration

---

🧭 Engineering Philosophy

«Understand the system. Design for failure. Test the assumptions. Ship useful software.»

My approach to Web3 engineering is built around six principles:

- Security by design: Identify trust boundaries, authorization requirements, and attack surfaces before deployment.
- Test-driven confidence: Test normal behavior, failure conditions, edge cases, and adversarial inputs.
- End-to-end understanding: Understand how the interface, wallet, RPC, transaction, and smart contract connect.
- Readable engineering: Favor maintainable code, clear interfaces, meaningful errors, and well-documented decisions.
- Protocol awareness: Understand economic assumptions, external dependencies, oracle risks, and composability.
- Continuous learning: Study established protocols, reproduce vulnerabilities in controlled environments, and contribute to open source.

---

🏗️ My Web3 Technology Stack

My technical roadmap spans frontend engineering, backend development, smart contracts, blockchain infrastructure, security, and production deployment.

The technology lists below describe my areas of focus and development roadmap. A listed tool is not a claim of professional mastery; completed projects and documentation should demonstrate actual proficiency.

01. Frontend Engineering

Building responsive, accessible, high-performance interfaces for decentralized applications.

Languages and web fundamentals

- HTML5
- CSS3
- JavaScript (ES6+)
- TypeScript
- Responsive design
- Accessibility fundamentals
- HTTP, HTTPS, DNS, and browser networking
- JSON, REST, and asynchronous programming

Frameworks and UI libraries

- React
- Next.js
- React Server Components
- Next.js App Router
- Tailwind CSS
- shadcn/ui
- Radix UI
- Material UI
- Framer Motion
- Motion
- Lucide Icons
- CSS Modules

Frontend engineering concepts

- Component architecture
- State management
- Server-side rendering (SSR)
- Static site generation (SSG)
- Incremental static regeneration (ISR)
- Client-side rendering (CSR)
- Server Components and Client Components
- Form validation
- Error boundaries
- Loading and empty states
- Responsive dashboards
- Performance optimization
- Search engine optimization
- Accessibility and semantic HTML

State management and data fetching

- React Context
- Zustand
- Redux Toolkit
- TanStack Query
- SWR
- React Hook Form
- Zod

Goal: Build production-quality interfaces that make complex blockchain operations understandable and easy to use.

02. Web3 Frontend Integration

Connecting decentralized applications to wallets, contracts, and blockchain networks.

Core libraries

- Wagmi
- Viem
- Ethers.js
- Web3.js
- ConnectKit
- RainbowKit
- Reown AppKit
- WalletConnect
- MetaMask SDK

Wallets and authentication

- MetaMask
- WalletConnect-compatible wallets
- Coinbase Wallet
- Browser-injected wallets
- SIWE — Sign-In with Ethereum
- ERC-4361
- EIP-1193 provider interface
- EIP-6963 multi-wallet discovery

Smart contract interaction

- ABI encoding and decoding
- Contract reads and writes
- Transaction submission
- Transaction receipt handling
- Event and log parsing
- Contract error handling
- Gas estimation
- Network and chain switching
- Token balances and allowances
- Signature generation and verification
- Contract deployment integration

Account abstraction and advanced UX

- ERC-4337
- Smart accounts
- Account abstraction
- Paymasters
- Bundlers
- Gas sponsorship
- Session keys
- Batch transactions
- EIP-7702 concepts
- Safe smart accounts

Goal: Build dApps where wallet connectivity, transaction signing, on-chain reads, and transaction feedback work reliably.

03. Smart Contract Development

Designing and implementing on-chain logic with security, correctness, and maintainability in mind.

Languages

- Solidity
- Yul
- Rust
- Vyper — ecosystem exploration

Solidity fundamentals

- Contract architecture
- Functions, modifiers, and visibility
- Events and custom errors
- Mappings, arrays, and structs
- Storage, memory, and calldata
- Inheritance and interfaces
- Libraries and reusable components
- Payable functions and native assets
- Fallback and receive functions
- Low-level calls
- ABI encoding and decoding
- Gas optimization
- Immutable and constant variables
- Access control
- Contract composition
- Upgradeability patterns

OpenZeppelin ecosystem

- OpenZeppelin Contracts
- Ownable and role-based access control
- ReentrancyGuard
- Pausable
- SafeERC20
- ERC20
- ERC721
- ERC1155
- ERC4626
- ERC2981
- ERC1967 proxy patterns
- UUPS upgradeability
- Governor and governance modules

Ethereum standards and EIPs

- ERC20 — fungible tokens
- ERC721 — non-fungible tokens
- ERC1155 — multi-token standard
- ERC4626 — tokenized vaults
- ERC2612 — permit approvals
- ERC2771 — meta-transactions
- ERC4337 — account abstraction
- ERC1271 — contract signature validation
- ERC2981 — NFT royalty standard
- ERC-2612 and signature-based approvals
- EIP-712 — typed structured data
- EIP-1967 — proxy storage slots
- EIP-1559 — transaction fee mechanism
- ERC-1167 — minimal proxy contracts

Goal: Build contracts with explicit invariants, well-defined permissions, tested failure paths, and understandable security assumptions.

04. Smart Contract Development and Testing Toolchain

Foundry

- Forge — compilation, testing, deployment, and scripting
- Anvil — local Ethereum development node
- Cast — blockchain interaction and inspection
- Chisel — Solidity REPL
- forge-std
- Foundry fuzz testing
- Invariant testing
- Fork testing
- Cheatcodes
- Gas snapshots
- Test fixtures
- Deployment scripts

Hardhat ecosystem

- Hardhat
- Hardhat Toolbox
- Hardhat Network
- Hardhat Ignition
- Hardhat testing and deployment workflows
- TypeChain
- ethers.js integration

Other development tools

- Remix IDE
- OpenZeppelin Contracts Wizard
- Tenderly
- Slither
- Solhint
- Solidity compiler ("solc")
- "solc-select"
- Mythril
- Echidna
- Medusa
- Halmos

Testing methodology

- Unit testing
- Integration testing
- Fork testing
- Fuzz testing
- Invariant testing
- Differential testing
- Property-based testing
- Regression testing
- Gas benchmarking
- Negative testing
- Authorization testing
- Stateful testing
- Failure-path testing

Goal: Develop repeatable testing workflows that help identify bugs before contracts are deployed.

05. Backend Engineering

Designing the services, databases, APIs, and background processes that support full-stack Web3 applications.

Backend languages

- TypeScript
- JavaScript
- Rust
- Python

Runtime and frameworks

- Node.js
- Express.js
- Fastify
- NestJS
- Hono
- Next.js Route Handlers
- Next.js Server Actions

APIs and communication

- REST APIs
- GraphQL
- WebSockets
- Server-Sent Events
- Webhooks
- JSON-RPC
- OpenAPI
- Authentication and authorization
- Rate limiting
- Input validation
- API versioning
- Background jobs
- Event-driven architecture
- Idempotency
- Retry and timeout strategies

Databases and data access

- PostgreSQL
- Supabase
- Prisma
- Drizzle ORM
- Redis
- MongoDB
- SQLite
- SQL fundamentals
- Database migrations
- Indexing and query optimization
- Transactions and concurrency
- Connection pooling

Authentication and identity

- Sign-In with Ethereum (SIWE)
- Session management
- JWT
- OAuth 2.0 concepts
- Role-based authorization
- Nonce generation and verification
- Signature verification
- Secure cookie handling
- Wallet-based identity

Background processing

- BullMQ
- Redis-backed queues
- Scheduled jobs
- Event consumers
- Retry and dead-letter strategies
- Transaction status monitoring
- Blockchain event processing

Goal: Build reliable off-chain services without confusing database state with authoritative on-chain state.

06. Blockchain Architecture and Infrastructure

Understanding the systems beneath decentralized applications.

Ethereum and EVM concepts

- Ethereum execution model
- EVM bytecode
- Transaction lifecycle
- Gas accounting
- Contract storage
- Memory and calldata
- ABI and function selectors
- Logs, events, and topics
- Receipts and transaction traces
- Nonces and transaction ordering
- Block confirmations and reorgs
- Consensus and finality concepts
- RPC architecture
- Mempools
- Transaction simulation
- Account and contract models

RPC providers and infrastructure

- Alchemy
- Infura
- QuickNode
- Ankr
- Chainstack
- Public RPC endpoints
- Self-hosted execution clients
- RPC reliability and failover
- Request batching
- WebSocket subscriptions
- Archive-node concepts
- Rate limits and provider security

Ethereum clients and node infrastructure

- Geth
- Nethermind
- Erigon
- Besu
- Reth
- Lighthouse
- Prysm
- Lodestar
- Teku

Blockchain explorers and debugging

- Etherscan
- Blockscout
- Tenderly
- Transaction traces
- Event logs
- Contract verification
- Source maps
- Opcode inspection
- Gas profiling
- Forked-chain debugging

Goal: Understand not just how to call a contract, but what happens from transaction submission to execution, confirmation, and application state updates.

07. Rust and Systems-Level Web3 Development

Developing systems-oriented programming skills for blockchain infrastructure and performance-sensitive applications.

Rust fundamentals

- Ownership and borrowing
- Lifetimes
- Structs and enums
- Traits and generics
- Pattern matching
- Error handling with "Result" and "Option"
- Iterators and closures
- Modules and crates
- Cargo and dependency management
- Testing and documentation
- Async programming
- Concurrency
- Memory safety
- Serialization and deserialization

Rust ecosystem

- Cargo
- Tokio
- Serde
- Axum
- Actix Web
- SQLx
- "tracing"
- "anyhow"
- "thiserror"

Ethereum and EVM development with Rust

- Alloy
- ethers-rs — legacy ecosystem familiarity
- REVM
- Reth
- Foundry's Rust-based tooling ecosystem
- EVM execution and tracing
- ABI interaction
- Transaction signing
- JSON-RPC clients

Solana development

- Solana SDK
- Anchor Framework
- Program Derived Addresses (PDAs)
- Cross-Program Invocation (CPI)
- Account-based data model
- SPL Token programs
- Solana testing tools
- Local validator workflows

Other blockchain ecosystems

- Cosmos SDK
- CosmWasm
- Polkadot SDK / Substrate
- ink! — ecosystem exploration
- NEAR SDK
- Move-based ecosystems — exploration

Goal: Progress from Rust fundamentals to practical blockchain tooling, infrastructure services, and ecosystem-specific development.

08. DeFi and Protocol Engineering

Understanding how decentralized financial systems work, how they compose, and where they can fail.

Protocol concepts

- Automated Market Makers (AMMs)
- Constant-product market makers
- Liquidity pools
- Liquidity providers
- Swaps and routing
- Slippage and price impact
- Impermanent loss
- Lending and borrowing
- Collateralization
- Liquidations
- Interest-rate models
- Flash loans
- Oracles
- Yield strategies
- Tokenized vaults
- Staking and restaking
- Governance and voting
- Bridges and cross-chain messaging
- MEV and transaction ordering

Protocols and infrastructure to study

- Uniswap
- Aave
- Compound
- Maker / Sky
- Lido
- Curve
- Balancer
- Chainlink
- Safe
- ENS
- OpenZeppelin
- Across
- LayerZero

DeFi engineering principles

- Accounting invariants
- Share-price calculations
- Rounding direction
- Oracle freshness and manipulation
- Liquidation incentives
- Reentrancy across protocol boundaries
- External dependency risk
- Token compatibility assumptions
- Economic attack modeling
- Governance and administrative risk
- Upgradeability and migration risk

Goal: Understand protocol mechanics well enough to implement, test, integrate, and critically evaluate DeFi components.

09. Smart Contract Security and Auditing

Developing a security-first approach to contract development and vulnerability analysis.

Vulnerability classes

- Reentrancy
- Access-control failures
- Broken authorization
- Integer and precision errors
- Incorrect accounting
- Signature replay
- EIP-712 domain-separation errors
- Front-running and transaction ordering
- Oracle manipulation
- Flash-loan-assisted attacks
- Unchecked external calls
- Denial of service
- Unsafe initialization
- Proxy and storage-layout mistakes
- Incorrect upgrade authorization
- Insecure randomness
- Griefing
- Slippage failures
- MEV exposure
- Cross-contract assumptions
- Bridge validation failures
- Governance attacks

Security tools and platforms

- Slither
- Echidna
- Medusa
- Mythril
- Foundry
- Halmos
- Tenderly
- Certora Prover
- OpenZeppelin Defender
- Immunefi
- Code4rena
- Sherlock
- CodeHawks
- Cantina
- Secureum

Security methodology

- Threat modeling
- Attack-surface identification
- Trust-boundary analysis
- Manual code review
- Static analysis
- Dynamic testing
- Fuzz testing
- Invariant design
- Fork-based reproduction
- Proof-of-concept development
- Root-cause analysis
- Remediation validation
- Severity assessment
- Responsible disclosure
- Clear audit reporting

Goal: Develop the ability to identify realistic attack paths, prove findings through reproducible tests, and communicate risk clearly.

Security tooling and audit platforms are areas of study and practice, not a claim of completed professional audits or certifications.

10. Indexing, Data Availability, and Decentralized Storage

Building applications that need efficient access to on-chain data and off-chain content.

Indexing and querying

- The Graph
- GraphQL
- Subgraphs
- Envio
- Goldsky
- Subsquid
- Ponder
- Custom event indexers
- Blockchain event listeners
- Reorg-aware indexing
- Historical data reconstruction

Decentralized storage

- IPFS
- Pinata
- Filecoin
- Arweave
- Content addressing
- CIDs
- Pinning services
- Metadata design
- Content integrity verification
- Storage and retrieval strategies

Data engineering concepts

- Event-driven data pipelines
- Blockchain log ingestion
- Data normalization
- Cursor-based pagination
- Reorg handling
- Idempotent event processing
- Database indexing
- Caching
- Historical state reconstruction

Goal: Build applications that can efficiently retrieve, verify, and present blockchain data without relying on expensive repeated RPC calls.

11. Layer 2s, Scaling, and Interoperability

Exploring the infrastructure that extends Ethereum and connects blockchain ecosystems.

Layer 2 ecosystems

- Optimism
- Arbitrum
- Base
- zkSync
- Starknet
- Polygon
- Scroll
- Linea
- Mantle
- OP Stack
- Arbitrum Orbit

Scaling concepts

- Optimistic rollups
- Zero-knowledge rollups
- Sequencers
- Fraud proofs
- Validity proofs
- Data availability
- Cross-domain messaging
- L1 settlement
- Bridge security
- Finality and withdrawal periods

Cross-chain development

- Chainlink CCIP
- LayerZero
- Wormhole
- Hyperlane
- Axelar
- Cross-chain message verification
- Replay protection
- Source-chain and destination-chain validation
- Bridge accounting
- Message ordering and failure recovery

Goal: Understand the security and architectural trade-offs involved in deploying applications across multiple networks.

12. Testing, Quality Assurance, and Developer Experience

Writing code is only part of delivering reliable software.

Testing tools

- Vitest
- Jest
- React Testing Library
- Playwright
- Cypress
- Supertest
- Forge
- Hardhat testing tools
- Echidna
- Medusa

Code quality

- ESLint
- Prettier
- TypeScript strict mode
- Solhint
- EditorConfig
- Code review
- Static analysis
- Dependency auditing
- Reproducible builds

Engineering workflows

- Git
- GitHub
- Branching strategies
- Pull requests
- Code review
- Issue tracking
- Semantic versioning
- Conventional Commits
- Changelogs
- Technical documentation
- Architecture Decision Records

Goal: Make projects easier to maintain, review, reproduce, and contribute to.

13. DevOps, Deployment, and Observability

Building and deploying applications with reliable development and production workflows.

Deployment platforms

- Vercel
- Railway
- Fly.io
- Render
- AWS
- Google Cloud
- Cloudflare
- Docker
- Docker Compose

CI/CD

- GitHub Actions
- Automated testing
- Build validation
- Linting
- Type checking
- Contract compilation
- Automated security checks
- Deployment workflows
- Environment separation

Monitoring and reliability

- Sentry
- OpenTelemetry
- Prometheus
- Grafana
- Structured logging
- Error tracking
- RPC health checks
- Transaction monitoring
- Alerting
- Retry policies
- Rate limiting
- Secret management

Infrastructure fundamentals

- Linux
- Bash
- Networking
- DNS
- HTTPS and TLS
- Environment variables
- Secrets management
- Containers
- Cloud deployment
- Database backups
- Service availability

Goal: Ship applications that can be tested, deployed, monitored, and maintained beyond a local development environment.

14. AI, Automation, and Web3

Exploring the intersection of intelligent software, developer tooling, and decentralized applications.

AI application development

- Python
- OpenAI APIs
- Model APIs
- Structured outputs
- Tool calling
- Retrieval-Augmented Generation (RAG)
- Embeddings
- Vector search
- pgvector
- MCP (Model Context Protocol)
- AI agents
- Workflow orchestration
- Evaluation and guardrails

Automation and infrastructure

- Webhooks
- Event-driven workflows
- Task queues
- API integrations
- Scheduled processing
- On-chain event triggers
- Human approval workflows
- Transaction simulation before execution

Web3 and AI design considerations

- Verifiable on-chain actions
- Off-chain computation
- Wallet permissions
- Transaction simulation
- Key management
- Agent spending limits
- Auditability
- Deterministic contract execution
- Human confirmation for sensitive actions

Goal: Explore how AI can improve developer workflows and user experiences while keeping transaction authorization, contract execution, and key security explicit.

---

🚀 Featured Projects

My portfolio is intended to demonstrate complete engineering workflows, not just isolated code snippets.

The projects below define the areas I want to demonstrate through working repositories, automated tests, architecture documentation, and deployments.

01 — On-Chain Escrow

Category: Full-Stack dApp · Payments · Smart Contracts

A decentralized escrow application for managing payments between parties under predefined contract conditions.

Planned engineering features

- Create and manage escrow agreements
- Deposit and release funds
- Refund and cancellation rules
- Role-based authorization
- State-transition validation
- ERC20 token support
- Wallet connectivity
- Transaction history
- Automated Foundry tests
- Security-focused documentation

Stack: Solidity · Foundry · OpenZeppelin · Next.js · TypeScript · Wagmi · Viem

Repository: [Add repository link]

02 — DeFi Vault

Category: DeFi · Token Accounting · Smart Contracts

A tokenized vault exploring deposits, withdrawals, share accounting, and asset management.

Planned engineering features

- Deposit and withdrawal flows
- Share-to-asset accounting
- Rounding and precision tests
- Access control
- Emergency-pause design
- Reentrancy considerations
- Invariant and fuzz testing
- Gas measurements
- Technical documentation

Stack: Solidity · Foundry · OpenZeppelin · TypeScript

Repository: [Add repository link]

03 — Solidity Security Labs

Category: Security Research · Testing · Vulnerability Analysis

A collection of controlled security exercises documenting vulnerable patterns, reproducible exploits, and remediations.

Planned engineering features

- Minimal vulnerable contracts
- Foundry exploit tests
- Root-cause explanations
- Corrected implementations
- Regression tests
- Severity and impact analysis
- Lessons learned

Stack: Solidity · Foundry · Slither · Echidna

Repository: [Add repository link]

04 — Blockchain Event Indexer

Category: Backend Engineering · Blockchain Data

A service that listens to contract events, processes logs, and stores queryable application data.

Planned engineering features

- Event ingestion
- Persistent storage
- Duplicate-event protection
- Reorg-aware processing
- Retry and recovery logic
- REST API
- Database indexing
- Monitoring and structured logs

Stack: TypeScript · Node.js · PostgreSQL · Viem · Docker

Repository: [Add repository link]

05 — Rust Blockchain Toolkit

Category: Systems Programming · Rust · Blockchain Infrastructure

A Rust project exploring blockchain RPC interaction, transaction inspection, and developer tooling.

Potential engineering features

- JSON-RPC client
- Transaction and receipt retrieval
- Typed request and response handling
- Error handling
- Async operations
- Structured logging
- Unit and integration tests

Stack: Rust · Cargo · Tokio · Serde · Alloy

Repository: [Add repository link]

These project descriptions are implementation targets. Update them as features are completed, and link only to real repositories and working demos.

---

🗺️ My Engineering Roadmap

My learning strategy is to progress from strong fundamentals to complete applications and then into protocol-level engineering.

Phase| Focus| Evidence of progress
01| TypeScript, React, Next.js, Git| A clean, responsive frontend and maintainable code
02| Solidity, EVM, OpenZeppelin| Contracts with clear permissions and state transitions
03| Foundry and testing| Unit, fuzz, invariant, and failure-path tests
04| Wagmi, Viem, wallet UX| A working wallet-connected dApp
05| Backend and databases| A documented API and persistent data model
06| Security engineering| Reproducible findings and validated fixes
07| DeFi and protocol architecture| A tested vault or other protocol component
08| Rust and infrastructure| A tested blockchain tooling project
09| Indexing and Layer 2s| An event-driven service or multi-network application
10| Production engineering| CI/CD, monitoring, documentation, and deployment

My priority is to demonstrate each stage through completed work rather than simply moving through a list of tutorials.

---

🔐 Security Principles

I treat smart-contract security as a design responsibility, not a final checklist.

My security workflow aims to include:

1. Define the protocol's intended behavior and trust assumptions.
2. Identify privileged actors, external calls, and dependencies.
3. Specify critical invariants.
4. Write unit and negative tests.
5. Use fuzzing and invariant testing where appropriate.
6. Review access control, accounting, signatures, and upgradeability.
7. Use static-analysis tools as supporting evidence.
8. Reproduce suspected vulnerabilities in a controlled environment.
9. Verify remediations with regression tests.
10. Document limitations and unresolved risks honestly.

Security tools cannot guarantee that a contract is safe. Findings require careful validation, and production deployment should involve appropriate independent review for the level of risk.

---

🌐 Open Source and Collaboration

I want to contribute to the Web3 ecosystem by:

- Improving tests and documentation in established repositories.
- Investigating reproducible bugs.
- Submitting focused pull requests.
- Learning from maintainers and code reviews.
- Writing technical notes about EVM behavior and smart-contract design.
- Sharing security research responsibly.
- Building tools that make blockchain development more accessible.

I value clear communication, thoughtful reviews, readable code, and a willingness to challenge assumptions.

---

💼 Opportunities

I'm interested in remote opportunities across:

- Web3 / Blockchain Developer
- Junior Solidity Developer
- Smart Contract Developer
- EVM Developer
- Web3 Full-Stack Developer
- dApp Developer
- Blockchain Backend Developer
- Junior Protocol Engineer
- Smart Contract Security Research — learning and research opportunities

I'm particularly interested in teams building developer infrastructure, decentralized finance, blockchain applications, and open-source protocols.

I aim to contribute through practical implementation, strong testing habits, continuous learning, and transparent engineering.

---

📬 Connect

- GitHub: "@0x3ric3mmanu3l" (YOUR_GITHUB_PROFILE_URL)
- Portfolio: "Your developer portfolio" (YOUR_PORTFOLIO_URL)
- LinkedIn: "Connect professionally" (YOUR_LINKEDIN_URL)
- X: "Follow my technical journey" (YOUR_X_PROFILE_URL)
- Email: YOUR_PROFESSIONAL_EMAIL

---

<p align="center">
  <b>Building useful software for a decentralized world.</b>
</p><p align="center">
  <i>Learn deeply. Build carefully. Test relentlessly. Contribute openly.</i>
</p>
