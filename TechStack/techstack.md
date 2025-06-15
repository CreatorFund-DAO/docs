---

# Core Tech Stack

---

##  Core Architecture Stack

| **Component**            | **Technology / Protocol**               | **Purpose**                                                |
|--------------------------|-----------------------------------------|-----------------------------------------------------------|
| **Identity & Wallet**    | **Tomo** + TEE-based Wallet Server      | Social login → Secure wallet creation, address generation |
| **IP Registration**      | **Story Protocol (ERC-721, ERC-6551)**  | Mint IP as NFT → Register → Deploy programmable IP Account |
| **Metadata Storage**     | IPFS                          | Storage of NFT Metadata (Opensea Standard) + IP Metadata (Story Standard) |
| **Token Bound Accounts** | ERC-6551                                | Wallet-like contract accounts bound to IP NFTs            |
| **Governance Tokens**    | ERC-20                                  | DAO token for fractional IP ownership and governance      |
| **DAO Governance**       | Snapshot / Custom Solidity DAO          | Voting, treasury management, licensing decision-making    |
| **Monetization Modules** | Royalty Module + Licensing Module       | Royalty NFTs, Licensing fees, fractionalization, borrowing |
| **Funding DAO Treasury** | Custom Smart Contracts                  | Manages royalties, DAO share allocations, disbursements   |
| **Dispute Resolution**   | Story Dispute Modules                   | On-chain enforcement of infringement, freezing metadata   |
| **Frontend Framework**   | Next.js + Tailwind CSS                  | User interface for creators, funders, DAO participants     |
| **Blockchain Interaction** | Ethers.js / Wagmi                      | On-chain read/write interactions with smart contracts     |
| **Wallet Connection**    | WalletConnect + RainbowKit              | Seamless multi-wallet UX                                  |
| **Indexing Layer**       | The Graph                               | Querying onchain data (funding rounds, royalties, licenses) |
| **AI Integrations**      | Tomo Modular Agents                     | IP validation, dynamic license pricing, proposal suggestions |

---

##  Tools & Development Stack

- **Smart Contract Dev:** Hardhat / Foundry
- **Frontend:** React (Next.js) + Tailwind CSS
- **Wallet Integration:** Wagmi + RainbowKit
- **File Storage:** IPFS
- **Indexing:** The Graph Protocol
- **Blockchain:** Base, Ethereum, Optimism, Polygon

---

##  Security & Privacy

- **TEE (Trusted Execution Environment)** → Wallet Server protection
- **Audited Smart Contracts** → Royalty, Licensing, DAO modules
- **Metadata Hashing** → Immutability & infringement protection
- **Optional ZK integrations** → For privacy-preserving creator identity (future)

---
