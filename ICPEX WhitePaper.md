# ICPEx: AI-Driven Decentralized Liquidity Network

## 1. Introduction

### 1.1 Redefining Decentralized Trading

ICPEx is a full-chain decentralized exchange (DEX) based on the PMM (Proactive Market Maker) algorithm, aiming to become the decentralized finance (DeFi) hub for Web3. Empowered by AI agent technology, ICPEx is designed to provide users with a smarter and more efficient DeFi trading experience. Both the front-end and back-end of ICPEx are deployed on ICP (Internet Computer), offering efficient on-chain liquidity for Web3 asset trading, allowing every Web3 user to easily issue and trade assets.

Since its launch in 2022, ICPEx has gradually developed into a crucial financial infrastructure within the IC (Internet Computer) ecosystem. Currently, its TVL (Total Value Locked) exceeds $250,000, with support for over 500 tokens and more than 3,000 active users. ICPEx remains highly active in community engagement, with its Twitter following surpassing 10,000, solidifying a strong user base and community consensus.

### 1.2 Project Origin and Goals

#### 1.2.1 Current DEX Landscape on IC ecosystem

The current DEX landscape within the IC ecosystem has some limitations:

- Some DEX architectures rely on centralized liquidity pools, where users must trust the platform.
- Liquidity pool information is often opaque, making it difficult for users to assess risks and rewards.
- The interaction process is cumbersome; for instance, completing a simple swap involves multiple steps, leading to a poor user experience.
- The platform is not user-friendly for creating new tokens, which hampers the growth of the DeFi ecosystem and limits trading venues for long-tail assets.

#### 1.2.2 ICPEx Solutions and Objectives

ICPEx aims to address these issues and, by leveraging AI agent technology, seeks to create:

- Decentralized liquidity pools without intermediary management, allowing users to directly interact with smart contracts, reducing trust risks.
- Transparent liquidity pool data, enabling users to easily access pool parameters and transaction data.
- A simplified interaction process, optimizing the user experience.
- A user-friendly token creation process, lowering the barrier to token issuance and fostering the long-tail market, thereby enriching the IC ecosystem.
- **Intelligent trading strategies powered by AI agents to enhance user profits.**

**Specific Goals:**

- **Short-term Goal:** Capitalize on the long-tail market effect to drive the development of the IC DeFi ecosystem, positioning ICPEx as the preferred DEX in the IC ecosystem.
- **Long-term Goal:** Leverage ICP's Chain Key and other technologies to enable cross-chain exchanges, creating a siphoning effect, and enter other mainstream token ecosystems to become a liquidity hub connecting different blockchains.
- **Visionary Goal:** Become an AI-driven DeFi trading infrastructure, enhancing liquidity and efficiency across the entire Web3 market.

------

## 2. Advantages and Innovations of ICPEx

To achieve the aforementioned goals, ICPEx boasts the following core product features:

### 2.1 Full-Chain Solution

The management modules of ICPEx are fully executed by decentralized on-chain smart contracts, including modules for Web asset management, token management, Exchange Router routing, oracles, and more. All trades and order matching are completed within smart contracts, eliminating the need for centralized servers, greatly reducing centralized risks.

### 2.2 PMM Algorithm

ICPEx implements the PMM (Proactive Market Making) algorithm within its routing system. PMM provides more accurate price discovery and liquidity management. It improves capital efficiency by dynamically adjusting capital allocation and slippage, thus enhancing capital utilization. Moreover, PMM’s adaptive capabilities excel at catering to both high and low liquidity assets, surpassing AMM models in several key areas.

### 2.3 User-Controlled Liquidity

Users have full control over the liquidity pools. Unlike typical liquidity pool models where tokens are pooled in a centralized account, the tokens in ICPEx’s pools are actual tokens owned and controlled by the pools themselves, ensuring greater security and transparency.

### 2.4 Smart Exchange Router

The Smart Exchange Router helps users select the optimal ratio for trading across multiple pools of the same token pair, ensuring the best price and minimal slippage.

### 2.5 Multi-Type Liquidity Pools

ICPEx supports various types of liquidity pools to meet the needs of different assets and users:

- Standard Pool (Public Pool Standard Mode):
  - Capital allocation similar to Uniswap, with the ability to set fees and volatility factors, and token prices determined by the liquidity provided by both parties.
- Single-Asset Pool (Public Pool Single-Asset Mode):
  - Allows liquidity provision by selling tokens without requiring liquidity from buyers, thus lowering the startup threshold.
- Private Pool:
  - Liquidity can only be added by the creator, targeting market makers and offering more flexible market-making strategies.
- Pegged Pool:
  - The price curve in pegged pools is similar to that of Curve, making it suitable for synthetic assets and reducing price volatility.

### 2.6 One-Click Token Creation

- **No Code Required:** Lowers the barrier for token issuance, enabling broader participation in Web3.
- Optional ICRC-2+ and DIP20+ Protocols:
  - Natively compatible with ICRC-2 and DIP20 standards for easy integration and interoperability.
  - Customizable deflationary burn mechanisms to meet the needs of different token models.
  - Optional additional token issuance functionality to support adjustments in tokenomics.
  - Ability to renounce ownership for fully decentralized management.
- Extremely competitive pricing to reduce the cost of token issuance.

### 2.7 AI Agent (Under Development)

ICPEx is actively developing the AI Agent functionality, which will provide users with the following features in the future:

- **Smart Trading Strategies:** Based on the Anda framework, AI analyzes on-chain data, market fluctuations, and historical trading behaviors to provide automated trading strategies that ensure optimal trade execution for users. The Anda framework ensures that the AI agents run on-chain while preserving the privacy of users' trading strategies via ICP’s technology.
- **Automated Arbitrage:** Based on the Anda framework, AI monitors price discrepancies across major liquidity pools and automatically executes arbitrage trades to improve returns and avoid market inefficiencies. The Anda framework ensures the AI agent safely records arbitrage execution on-chain, ensuring traceability and transparency of trades.
- **Smart Asset Management:** Leveraging the Anda framework, combined with liquidity mining, automated market making, and smart fund reallocation, the AI will assist liquidity providers (LPs) in maximizing profits and dynamically adjusting capital pools to improve fund utilization. The Anda framework ensures that asset management decisions are securely recorded on-chain while safeguarding users' asset data privacy.

------

## 3. Technical Architecture

### 3.1 Overview of the Technical Architecture

![image-20250214161140398](https://p.ipic.vip/mhcd9p.png)

ICPEx adopts a modular architecture design to ensure an efficient and scalable decentralized trading experience. The entire architecture focuses on three core needs: liquidity management, smart trading optimization, and on-chain interoperability, leveraging the computational power of the Internet Computer (IC) to achieve high throughput and low-cost on-chain transaction execution.

ICPEx’s code has been audited by professional auditing agencies to ensure the security of smart contracts, reduce potential risks, and guarantee the stability and reliability of transaction execution through continuous code optimization and testing.

The main technical architecture of ICPEx is divided into the following key modules:

- **Backend Services:** Handles transaction logic, data storage, and provides APIs for frontend interaction.
- **IC Canister Ecosystem:** Includes core on-chain components such as liquidity pools, trade routing, token management, and more, ensuring transaction security and reliability.
- **Frontend Interaction:** Provides the user interface to support decentralized trading, asset management, and liquidity interactions.
- **Oracle:** Feeds price data to the routing canisters.
- **AI Agent Module (Under Development):** Provides smart trading strategies, automated arbitrage, and smart asset management features.

### 3.2 Core Modules of the Technical Architecture

- **Backend Services**
  - **Order Management:** Accepts user order requests and invokes smart contracts for transaction execution.
  - **Market Data Storage:** Provides interfaces for querying market prices, trading depth, and other data to support trade optimization and user decision-making.
  - **Transaction Record Storage:** Records on-chain transaction history, allowing users to trace and analyze their past orders.
- **IC Canister Ecosystem**
  - **Router Canister:** Handles on-chain trade routing, optimizing capital flow and improving trade matching efficiency.
  - **Pool Canister:** Manages decentralized liquidity pools, ensuring the safety of liquidity providers' assets and providing the best trading depth.
  - **Token Canister:** Manages token storage and transfers, supporting on-chain management of user assets.
  - **Factory:** Used for creating new liquidity pools and trading pairs, ensuring the scalability of the ICPEx ecosystem.
  - All IC Canister-related contracts have been audited for security, ensuring the integrity and verifiability of transactions, while preventing potential security vulnerabilities.
- **Frontend Interaction**
  - **Decentralized Trading (Swap):** Users can directly swap tokens on ICPEx, enjoying low slippage and high liquidity trading experiences.
  - **Liquidity Management (LP Interaction):** Users can provide liquidity, earn transaction fees, and adjust their capital allocation based on market conditions.
  - **Market Information Query:** Displays real-time data such as liquidity pool depth and token prices, aiding user decision-making.
- **Oracle**
  - Feeds external price information reliably to smart contracts, ensuring accurate transaction pricing and preventing potential losses.
- **Data Storage (Trading Canister):**
  - Stores trading canister data to support the frontend dashboard.
- **AI Agent Module (Under Development)**
  - **Smart Trading Strategies:** (Under Development) Provides automated trading strategies to ensure optimal trade execution for users.
  - **Automated Arbitrage:** (Under Development) Monitors price discrepancies across liquidity pools and automatically executes arbitrage trades to improve returns and avoid market inefficiencies.
  - **Smart Asset Management:** (Under Development) Helps LPs maximize profits by dynamically adjusting capital pools and improving fund utilization.

ICPEx, through its modular architecture design, combining decentralized liquidity management and AI agent technology, aims to build an efficient, secure, and scalable decentralized trading network, providing innovative liquidity solutions for the DeFi ecosystem. All core code has been audited by third-party auditing agencies to ensure smart contract security, offering users a trustworthy trading environment.

## 4. Advantages of Internet Computer

ICPEx chose to build on the Internet Computer (IC) for the following key advantages:

- **Zero Gas Fees:** Eliminates the burden of excessive gas fees for users across different chains, effectively preserving the Web2-like user experience for newcomers.
- **Full-Chain Development Framework:** Achieves decentralization with the entire front and back end on-chain, alleviating concerns about centralization, while utilizing the SNS DAO system to implement on-chain governance.
- **High Performance:** IC offers low latency and high throughput, capable of supporting large-scale transaction concurrency and improving user experience.
- **On-Chain Storage and Computation Integration:** Smart contracts can directly store data without relying on centralized APIs, enhancing the decentralization degree.

------

## 5. ICPEx Tokenomics

ICPEx, a decentralized exchange (DEX) based on the Internet Computer (IC), is committed to building an efficient, secure, and scalable liquidity network. To achieve true decentralized governance, we need the deep participation and joint decision-making of community users.

### 5.1 Why SNS is Necessary?

- **Enhance Community Governance and Decision-Making Power**
  - Token holders can participate in protocol development decisions directly through SNS voting, enhancing governance transparency.
  - Community members can collectively decide on important matters such as protocol parameters, feature upgrades, etc., ensuring that the protocol evolves in line with community interests.
  - The SNS model will decentralize governance power, avoiding centralization risks and promoting long-term stable development of the protocol.

### 5.2 Decentralization Sale

| Allocation         | %    | Amount        | Note                                                         |
| ------------------ | ---- | ------------- | ------------------------------------------------------------ |
| Decentralized Swap | 15%  | 150,000,000   | Distributed to direct participants, dissolved at months 0, 3, and 6 with a 1-month dissolve delay |
| Developer Neurons  | 12%  | 120,000,000   | Distributed to developers, dissolved at months 3, 6, 9, 12, 15, 18, 21, 24 with varying dissolve delays |
| Treasury           | 73%  | 730,000,000   | Managed by SNS DAO governance for development, audit, CEX listing fees, hosting cycles, trading initiative rewards, partnership reserves, risk reserves, airdrops to users, etc. |
| **Total**          | 100% | 1,000,000,000 |                                                              |

### 5.3 Initial SNS Configuration

| Items                           | Numbers       |
| ------------------------------- | ------------- |
| Genesis $ICX Token Supply       | 1,000,000,000 |
| Ledger Transaction Fee          | 0.001 ICX     |
| Proposal Reject Fee             | 1000 ICX      |
| Minimum Direct Fund             | 50,000 ICP    |
| Maximal Direct Fund             | 300,000 ICP   |
| Minimum Participation Fund      | 1 ICP         |
| Maximal Participation Fund      | 100,000 ICP   |
| Minimum Participants            | 100           |
| Maximum Dissolve Delay          | 24 months     |
| Dissolve Delay Bonus            | 100%          |
| Maximum Neuron Age              | 12 months     |
| Age Bonus                       | 20%           |
| Minimum Creation Stake          | 10 ICX        |
| Initial Reward Rate             | 2.50%         |
| Final Reward Rate               | 0.1%          |
| Reward Rate Transition Duration | 5 years       |

### 5.4 Token Value

As a decentralized liquidity network, ICPEx's token economic model will revolve around three core directions **Transaction Fee Allocation, Liquidity Incentives, and Community Governance** to ensure the long-term value and sustainable growth of the token $ICX.

#### 5.4.1 **Transaction Fee Allocation**

- **Part of the transaction fee is destroyed** to reduce market liquidity and increase token scarcity.
- **Part of the transaction fee is used for buyback** to support token price stability and long-term value growth.
- **Flexible adjustment mechanism for handling fees**, dynamically optimized according to the market environment to ensure transaction experience and ecological sustainability.

#### 5.4.2 Liquidity incentives

- **LP position incentives**, distributing incentives for users who provide liquidity and enhancing capital utilization.
- **Intelligent Market Making Rewards**, optimize LP returns based on AI agent strategies to improve capital efficiency.
- **Ecological Contribution Reward**, supports liquidity building for new token projects and promotes ecological prosperity.

#### 5.4.3 Token Governance

- **Decentralized governance**, token holders can vote on key issues such as protocol upgrades and fee structures.
- **Community decision-making power**, holders of $ICX can participate in the proposal and vote on the development direction of DEX to promote the ecological evolution.
- **Governance Rewards**, encouraging long-term holders and users to participate in governance, enhancing community consensus.

Through the three value pillars of **transaction fee distribution, liquidity incentive and governance mechanism**, ICPEx ensures the core role of token $ICX in the ecology and builds a decentralized financial system with **long-term stability and sustainable growth**.

## 6. ICPEx Development Roadmap (2025-2026)

ICPEx's development goals for 2025 are to **Optimize trade execution efficiency**, **Enhance liquidity management capabilities**, and **Introduce AI-agent trading** to ensure fast trading speeds, low costs, and a great user experience. The entire plan follows a cycle of **3 months** to ensure that each phase has clear objectives and outcomes.

---

### **6.1 March - May 2025: Optimize deal execution and improve aggregation speed**

**Goals:**

- **Reduce trade latency** and optimize Canister call logic to improve summarization speed.
- **Optimize order management** to reduce trade failure rate and improve user trading experience.
- **Adjust AMM model** to improve capital utilization and optimize market maker returns.

**Specific actions:**

- **Trade Execution Optimization**
  - Redesign **Router Canister** to reduce the number of calls between subnets and improve summarization efficiency.
  - **Batch Summarize Orders** to reduce on-chain Gas costs and increase transaction throughput.
  - Realize **Partial Fulfillment Mechanism** to avoid order failure due to insufficient liquidity.

- **Liquidity optimization**
  - Introduced **Dynamic LP fund scheduling** to reduce invalid liquidity and improve pool utilization.
  - **Optimize AMM fund allocation mechanism** to improve fund utilization and reduce slippage.

---

### **6.2 June - August 2025: intelligent trade routing to optimize LP returns**

**Goals:**

- **Smart order allocation** to provide users with optimal trade routing and increase fill rates.
- **Optimize LP funds management** to reduce Impermanent Loss.
- **New Anchor Pool Mechanism** for stable coins or synthetic assets to improve market stability.

**Specific actions:**

- **Smart Transaction Routing**
  - Developed **Liquidity aggregation algorithm** to automatically distribute transactions among multiple pools to improve transaction efficiency.
  - **Cross-pool aggregation mechanism** to intelligently match orders based on the funding of different liquidity pools to reduce slippage.

- **LP Funding Optimization**
  - **Dynamic Liquidity Adjustment**, AI automatically adjusts the allocation of assets in the pool to improve yield.
  - **Anchored Pool (Curve-like)** for stable coins, synthetic assets to reduce slippage on large transactions.

---

### **6.3 September - November 2025: introduce AI agents to improve trading intelligence**

**Goals:**

- **AI trading strategies** that automatically optimize trade execution paths based on on-chain data.
- **Intelligent arbitrage strategy**, utilizing AI to monitor price differences and automatically execute arbitrage trades.
- **Optimize user trading experience**, reduce manual operations and allow AI agents to manage assets automatically.

**Specific actions:**

- **AI Intelligent Trading**
  - AI agents** automatically determine market trends**, optimize trade execution strategies, and increase win rates.
  - **Real-time prediction of market fluctuations** to reduce user losses due to market instability.
- **AI Arbitrage**
  - Monitor the price difference between **ICPEx internal pool** and **external decentralized exchanges** (e.g. Sonic, ICDex) to achieve low-cost arbitrage.
  - **Multi-path Arbitrage Execution** to optimize Gas costs and improve arbitrage success.

### **6.4 December 2025 - February 2026: Cross-chain liquidity consolidation to improve capital utilization**

**Goals:**

- **Support cross-chain redemption within the ICP ecosystem**, and open up liquidity between IC and other public chains.
- **Optimize the design of liquidity pool** to attract more LPs to participate and improve the utilization rate of funds.
- **Actualize AI intelligent fund scheduling** and dynamically adjust liquidity allocation according to market conditions.

**Specific actions:**

- **Cross-chain transactions**
  - Utilize **Chain Key technology** to realize cross-chain flow of assets between ICP ecosystem and other chains (e.g. ETH, Solana).
  - **Supports automatic on-chain exchange** to reduce manual operations and improve cross-chain efficiency.

- **Liquidity Pool Optimization**
  - **Introduces multi-asset pool**, supports joint market making of multiple tokens and improves capital utilization.
  - **Automatically adjusts handling fees**, dynamically adjusts transaction rates according to market demand, and improves LP revenue.

---

### **6.5 March - May 2026: Fully-automated AI trading system on line**

**Goals:**

- **Enable fully automated AI trading agent** where users do not need to operate manually and AI executes trades automatically.
- **Optimize AI trading strategies** to ensure capital safety and increase returns.
- **Improve AI asset management** to increase long-term investment returns.

**Specific actions:** 

- **AI trade optimization**
  - **AI agents automatically execute buy and sell trades**, reducing errors caused by manual trading.
  - **Dynamically adjusts trading strategies** to optimize trade timing based on market conditions.

- **AI Asset Management**
  - **Combined with liquidity mining**, it automatically selects the optimal liquidity pool for LPs to increase returns.
  - **Intelligent fund redistribution** to reduce the waste of low-yield funds and improve overall fund utilization.

## Summary

In the next **15 months**, ICPEx will focus on the four core directions of **improving transaction speed, optimizing liquidity management, introducing AI proxy trading, and expanding cross-chain liquidity**, to ensure efficient operation of liquidity, fast and stable transaction execution, and ultimately build an **AI-driven efficient decentralized trading platform**.

## 7. Team & Vision

ICPEx is driven by a team of passionate developers, product managers, and marketing professionals who are deeply engaged in the blockchain and DeFi ecosystem. Our mission is to leverage technology and products to solve real-world problems and create genuinely valuable solutions.

The team’s expertise spans smart contract development, on-chain trading systems, market operations, product design, and security research. Our vision is clear: to make DeFi trading more efficient, more intelligent, and to ensure that true decentralization is maintained.

### 7.1 Team Members

- **Ethan Wang - Head / Co-Founder**

  Ethan has been exploring the Web3 space for several years, having experienced various market cycles, and has developed a unique understanding of the DeFi ecosystem. He is responsible for project planning and overall operations, driving product deployment while staying attuned to the latest trends in DeFi. Ethan envisions ICPEx not just as a trading platform but as a long-term, sustainable ecosystem.

- **Jason Liu - Technical Lead**

  Jason is a typical tech enthusiast with expertise in smart contracts and decentralized architecture design. He has a deep understanding of the ICP ecosystem and a comprehensive grasp of on-chain trading execution efficiency and security. At ICPEx, he oversees the technical architecture, smart contract development, and trading system optimization, ensuring the platform's stability and seamless performance.

- **Ava Chen - Product**

  Ava previously worked in traditional financial products and believes that the user experience of DeFi products is still far from ideal. The entry barriers for ordinary users are too high, so she joined ICPEx to lead product design and user experience optimization. Her focus is on making DeFi trading more intuitive and genuinely appealing to users, not just geeks and early adopters.

- **Leo Zhang - Smart Contract Developer**

  Leo is a coding enthusiast who spends nearly all his time working with smart contracts, having experience with Rust, Motoko, and Solidity. He is responsible for the development and optimization of smart contracts, focusing on liquidity management, cross-chain interactions, and trade matching to ensure the security and scalability of ICPEx's core protocol.

- **Sophia Lin - Trading Strategy / Data Analysis**

  Sophia has a background in on-chain data analysis and is deeply interested in trading patterns and arbitrage strategies. At ICPEx, she handles data analysis and trading strategy optimization, studying how to leverage AI agents to optimize trade paths, enhance liquidity utilization, and provide a better trading experience for ordinary users.

- **Daniel Wu - Community & Operations**

  Daniel is an early Web3 user with experience in various DeFi and NFT projects, making him highly familiar with community ecosystems. At ICPEx, he manages community operations and marketing, aiming to optimize the product through genuine user feedback rather than relying on PPT presentations and hollow slogans.

- **Alice Tang - Frontend Developer**

  Alice is responsible for the frontend development of ICPEx's web platform, specializing in React and Web3.js. She aims to simplify complex on-chain trading logic into an easy-to-use interface, enabling users to execute trades with a single click without needing to learn intricate on-chain operations.

- **Eric Zhou - Designer**

  Eric is a minimalist designer who has worked on UI/UX design for several Web3 projects. He believes that a great DeFi product should not just be a trading tool but should provide users with real freedom and convenience. At ICPEx, Eric is in charge of interface design and user interaction optimization, ensuring that the product is not only functional but also intuitive and user-friendly.

### 7.2 What We're Building

ICPEx is not a one-off project but a continuously evolving product. We’re not here to create a hype-driven DEX; instead, we aim to make DeFi trading more efficient, more intelligent, and more aligned with actual user needs.

Currently, we are focusing on:

- **Improving Transaction Speed:** Ensuring faster on-chain transaction execution while maintaining security.
- **AI Trading Agents:** Enabling ordinary users to leverage smart trading strategies instead of performing manual operations.
- **Cross-Chain Compatibility:** Enabling liquidity across ICP and other public blockchains, removing liquidity constraints.

ICPEx is still under constant development, with many features still in the works. However, we are focused on long-term value rather than short-term hype. If you're interested in DeFi, smart contracts, or cross-chain liquidity, feel free to join us in exploring more efficient Web3 trading methods.

### 7.3 Vision

Over the next three years, ICPEx will focus on optimizing transaction speed, integrating AI trading agents, and achieving cross-chain liquidity. Our ultimate goal is to build a high-performance, intelligent, and seamlessly connected decentralized trading network that provides DeFi users with a superior trading experience.
