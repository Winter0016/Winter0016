# 👋 Hi, I'm Phuc Chau
![](https://komarev.com/ghpvc/?username=Winter0016&color=green&style=flat-square)
I am a **Self-Taught Developer** building applications to study, experiment, and deeply understand how things work under the hood.

I am currently looking for an engineering position in both Web2 and Web3 to get my foot in the door, grow alongside an experienced team, and build software that matters.
---

### Tech Stack & Tools
* **Languages:** Solidity, Node.js, TypeScript/JavaScript
* **Frontend:** React.js, Next.js, Wagmi, Viem
* **Backend:** Nodejs, Nestjs, PostgreSQL, MongoDB, Redis
* **Web3 Infrastructure:** Foundry (Forge/Anvil/Cast), Chainlink (CCIP, VRF, Automation), Alchemy, IPFS/Pinata

---

### Projects 

#### RWA Tokenization Protocol
A platform to trade real US stocks on the blockchain using synthetic tokens. 
* **Hybrid Architecture:** Built a two-step settlement engine bridging Web2 brokerages (Alpaca API) and Web3 Smart Contracts.
* **UX & Security: Integrated Account Abstraction (Privy & Pimlico) for gasless USDC transactions. Engineered a zero-trust backend to mathematically prevent API spoofing, database data corruption, and Denial of Service (DoS).
* **Performance:** Replaced expensive blockchain HTTP polling with a real-time WebSocket indexer, dropping RPC compute usage by >95%.

#### King-Dom-Chan NFT Project
An upgradeable gaming marketplace with Token Bound Accounts (ERC-6551).
* **Gasless Trading:** Developed an off-chain Node.js/MongoDB relayer using EIP-712 signatures for gasless peer-to-peer escrow trades.
* **Fast Indexing:** Built a custom Viem indexer to sync contract events to MongoDB, drastically speeding up frontend queries.

#### Term-Deposit Banking Protocol
A DeFi protocol for fixed-term deposits with isolated treasury pools.
* **Gas Optimization:** Bit-packed 8 struct fields into a single 32-byte EVM storage slot, saving ~20,000 gas per deposit transaction.
* **Automation:** Integrated Chainlink Automation to monitor deposit maturity off-chain and automatically trigger on-chain rollovers.

#### Cross-Chain Rebase Protocol
A multi-chain reward token utilizing Chainlink CCIP.
* **Math & Testing:** Built an ERC-20 token that globally scales balances in real-time. Secured the complex math formulas against edge cases using Foundry invariant fuzz tests.
* **Bridging:** Implemented custom token pools to seamlessly transfer supply between Sepolia and Arbitrum while keeping interest rates synchronized.

---

### Let's Connect
- **Email:** chauquangphuc2604.2604@gmail.com
- **LinkedIn:** [linkedin.com/in/phúc-châu-65104a302](https://www.linkedin.com/in/phúc-châu-65104a302)
- **GitHub:** [github.com/Winter0016](https://github.com/Winter0016)

*(Currently open to Full-Stack Web3/Web2 Engineering roles!)*
