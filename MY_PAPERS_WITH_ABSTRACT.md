# 🎯 智能合约安全论文精选 (2024-2026) - 含摘要与翻译

> 专注近三年顶会论文，含摘要、中文翻译、作者与单位
> 整理自 [VTZ-Aether/Academic_Smart_Contract_Papers](https://github.com/VTZ-Aether/Academic_Smart_Contract_Papers)
> 最后更新: 2026-03-15

---

## 📌 快速索引

- [🔒 S&P 2024-2026](#-ieee-sp-2024-2026)
- [🔒 USENIX Security 2024-2026](#-usenix-security-2024-2026)
- [🔒 CCS 2024-2026](#-acm-ccs-2024-2026)
- [🔒 NDSS 2024-2026](#-ndss-2024-2026)
- [🛠 软件工程 2024-2026](#-软件工程-2024-2026)

---

## 🔒 IEEE S&P 2024-2026

### 2025 (12篇)

#### 1. Permissionless Verifiable Information Dispersal (Data Availability for Bitcoin Rollups)
- **作者**: Arthur Lazzaretti, Zeyu Liu, Lei Yang
- **单位**: Yale University, MIT
- **摘要**: Rollups are special applications on distributed state machines for which the underlying state machine only logs, but does not execute transactions. Rollups have become a popular way to scale applications on Ethereum and there is now growing interest in running rollups on Bitcoin. This paper constructs a VID system that is secure under the same model as Bitcoin, with one minimal additional requirement on the existence of reliable participants.
- **中文摘要**: 本文研究了如何在无需许可的情况下实现数据可用性，为比特币Rollups提供安全高效的数据分发方案。研究团队构建了一个在比特币相同模型下安全的VID系统，只需一个最小的额外要求即可实现。该系统使用状态机复制协议作为黑盒，具有向后兼容性。分析表明，该系统将通信成本降低了1000倍以上，延迟降低了10倍以上。

#### 2. Peer2PIR: Private Queries for IPFS
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. An Attack on TON's ADNL Secure Channel Protocol
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. Decentralization of Ethereum's Builder Market
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. Asymmetric Mempool DoS Security: Formal Definitions and Provable Secure Designs
- **作者**: Wanning Ding 等
- **单位**: 
- **摘要**: The mempool plays a crucial role in blockchain systems as a buffer zone for pending transactions before they are executed and included in a block. However, existing works primarily focus on mitigating defenses against already identified real-world attacks. This paper introduces secure blockchain-mempool designs capable of defending against any form of asymmetric eviction DoS attacks.
- **中文摘要**: 内存池在区块链系统中扮演着关键角色，作为待处理交易在执行和打包入区块之前的缓冲区。然而，现有研究主要关注对已识别现实攻击的防御。本文介绍了能够防御任何形式不对称驱逐DoS攻击的安全区块链内存池设计。

#### 6. Zero-Knowledge Location Privacy via Accurate Floating-Point SNARKs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. Phecda: Post-Quantum Transparent zkSNARKs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. Security Perceptions of Users in Stablecoins
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 9. P2C2T: Preserving the Privacy of Cross-Chain Transfer
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2024 (17篇) ⭐ 重点

#### 1. NURGLE: Exacerbating Resource Consumption in Blockchain State Storage via MPT Manipulation
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. SoK: Security and Privacy of Blockchain Interoperability
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. Pianist: Scalable zkRollups via Fully Distributed Zero-Knowledge Proofs
- **作者**: Tianyi Liu, Tiancheng Xie, Jiaheng Zhang, Dawn Song, Yupeng Zhang
- **单位**: UC Berkeley, UIUC
- **摘要**: In the past decade, blockchains have seen various financial and technological innovations. However, scalability is one of the key issues hindering the deployment of blockchains. To improve the throughput of the transactions, zkRollups and zkEVM techniques using zero-knowledge proofs have been proposed. In this work, we improve the scalability of these techniques by proposing new schemes of fully distributed ZKPs.
- **中文摘要**: 过去十年，区块链经历了各种金融和技术创新。然而，可扩展性是阻碍区块链部署的关键问题之一。为了提高交易吞吐量，使用零知识证明的zkRollups和zkEVM技术已被提出。本工作通过提出全新的全分布式零知识证明方案来提高这些技术的可扩展性。

#### 4. Large-Scale Study of Vulnerability Scanners ⭐⭐⭐
- **作者**: Christoph Sendner 等
- **单位**: 德国慕尼黑工业大学 (TUM)
- **摘要**: Ethereum smart contracts, which are autonomous decentralized applications on the blockchain that manage assets often exceeding millions of dollars, have become primary targets for cyberattacks. In 2023 alone, such vulnerabilities led to substantial financial losses exceeding a billion of US dollars. Our study investigates the gap between the effectiveness of existing security scanners and the vulnerabilities that still persist in practice.
- **中文摘要**: 以太坊智能合约是管理数百万美元资产的自主去中心化应用，已成为网络攻击的主要目标。仅在2023年，这类漏洞就造成了超过10亿美元的巨额资金损失。本研究调查了现有安全扫描器的有效性与实践中仍然存在的漏洞之间的差距。

#### 5. POMABuster: Detecting Price Oracle Manipulation ⭐⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. Certifying Zero-Knowledge Circuits with Refinement Types
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. SMARTINV: Multimodal Learning for Invariant Inference ⭐⭐⭐
- **作者**: Sally Junsong Wang 等
- **单位**: 新加坡国立大学 (NUS)
- **摘要**: Smart contracts are software programs that enable diverse business activities on the blockchain. Recent research has identified new classes of "machine un-auditable" bugs that arise from both transactional contexts and source code. To automate the detection of "machine un-auditable" bugs, we present SmartInv, an accurate and fast smart contract invariant inference framework.
- **中文摘要**: 智能合约是支持区块链上各种商业活动的软件程序。最近的研究发现了新的"机器无法审计"漏洞类别，这些漏洞源于交易上下文和源代码。为了自动检测"机器无法审计"的漏洞，我们提出了SmartInv，这是一个精确且快速的智能合约不变量推理框架。

#### 8. Nyx: Detecting Exploitable Front-Running ⭐⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 9. Chronos: Finding Timeout Bugs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 10. Specular: Secure Optimistic Blockchain Execution
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 11. Towards Smart Contract Fuzzing on GPUs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 12. Non-Atomic Arbitrage in DeFi
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 13. Conning the Crypto Conman: End-to-End Analysis of Cryptocurrency-based Technical Support Scams
- **作者**: Bhupendra Acharya 等
- **单位**: 
- **摘要**: The mainstream adoption of cryptocurrencies has led to a surge in wallet-related issues reported by ordinary users on social media platforms. In parallel, there is an increase in an emerging fraud trend called cryptocurrency-based technical support scam, in which fraudsters offer fake wallet recovery services and target users experiencing wallet-related issues.
- **中文摘要**: 主流采用加密货币导致社交媒体平台上普通用户报告的钱包相关问题激增。与此同时，一种名为加密货币技术支持诈骗的新兴欺诈趋势也在增加，欺诈者提供虚假钱包恢复服务并针对遇到钱包相关问题的用户。

#### 14. Routing Attacks on Cryptocurrency Mining Pools
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2023 (5篇)

#### 1. SoK: DeFi Attacks ⭐⭐⭐
- **作者**: Liyi Zhou 等
- **单位**: 伦敦大学学院 (UCL)
- **摘要**: Within just four years, the blockchain-based Decentralized Finance (DeFi) ecosystem has accumulated a peak total value locked (TVL) of more than 253 billion USD. This surge in DeFi's popularity has, unfortunately, been accompanied by many impactful incidents. According to our data, users, liquidity providers, speculators, and protocol operators suffered a total loss of at least 3.24 billion USD from Apr 30, 2018 to Apr 30, 2022.
- **中文摘要**: 仅在四年内，基于区块链的去中心化金融（DeFi）生态系统已积累了超过2530亿美元的峰值总锁仓量（TVL）。不幸的是，DeFi的流行伴随着许多重大事件。根据我们的数据，从2018年4月30日到2022年4月30日，用户、流动性提供者、投机者和协议操作员遭受的总损失至少为32.4亿美元。

#### 2. Clockwork Finance: Automated Analysis of Economic Security ⭐
- **作者**: Kushal Babel, Philip Daian, Mahimna Kelkar, Ari Juels
- **单位**: Cornell Tech
- **摘要**: We introduce the Clockwork Finance Framework (CFF), a general purpose, formal verification framework for mechanized reasoning about the economic security properties of composed decentralized-finance (DeFi) smart contracts. CFF features three key properties: contract complete, asymptotically constant model overhead, and attack-exhaustive by construction.
- **中文摘要**: 我们引入了Clockwork Finance Framework (CFF)，这是一个通用的形式化验证框架，用于机械推理组合去中心化金融（DeFi）智能合约的经济安全属性。CFF具有三个关键属性：合约完备性、渐近常数模型开销，以及按构造攻击穷举。

#### 3. Tyr: Consensus Failure Bugs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. WeRLman: To Tackle Whale with RL
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. Three Birds with One Stone
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2022 (2篇)

#### 1. Quantifying Blockchain Extractable Value
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. SAILFISH
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2021 (5篇)

#### 1. SmartPulse
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. sGUARD
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. On the Just-In-Time Discovery of Profit-Generating Transactions
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. Compositional Security for Reentrant Applications
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. High-Frequency Trading on Decentralized On-Chain Exchanges
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2020 经典 (4篇)

#### 1. Flash Boys 2.0: Frontrunning, MEV ⭐⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. VerX: Safety Verification of Smart Contracts
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. VeriSmart: Highly Precise Safety Verifier
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. Executable Operational Semantics of Solidity
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🔒 USENIX Security 2024-2026

### 2026 (1篇)

#### 1. Lost in Blockchain Address Misuse
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2025 (15篇)

#### 1. Auspex: Transaction Fee Mechanism Bugs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. Deanonymizing Ethereum Validators
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. SoK: Understanding zk-SNARKs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. Surviving in Dark Forest
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. Available Attestation
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. Voting-Bloc Entropy
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. Following Devils' Footstep
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. COLLISIONREPAIR
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 9. BEAT-MEV
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 10. Ghost Clusters
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 11. Does Finality Gadget Finalize Your Block?
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 12. Blockchain Address Poisoning
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 13. Automated Soundness and Completeness Vetting of Polygon
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2024 (11篇) ⭐

#### 1. SoK: Security Vulnerabilities in SNARKs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. Sprints: Intermittent PoW Mining
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. Max Attestation Matters
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. zkCross: Cross-Chain Privacy-Preserving Auditing
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. Understanding Ethereum Mempool Security under Asymmetric DoS
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. All Your Tokens are Belong to Us: Address Verification Vulnerabilities ⭐⭐
- **作者**: 
- **摘要**: In Ethereum, the practice of verifying the validity of the passed addresses is a common practice, which is a crucial step to ensure the secure execution of smart contracts. Vulnerabilities in the process of address verification can lead to great security issues.
- **中文摘要**: 在以太坊，验证传入地址有效性的做法是一种常见做法，是确保智能合约安全执行的关键步骤。地址验证过程中的漏洞可能导致重大安全问题。

#### 7. Speculative DoS Attacks in Ethereum ⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. Using My Functions Should Follow My Checks
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 9. Practical Security Analysis of ZK Proof Circuits
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 10. Pixel+: Forward-Secure Multi-Signatures
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 11. GuideEnricher: Protecting Anonymity of Ethereum Mixing Service Users
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2023 (14篇)

#### 1. Confusum Contractum: Confused Deputy Vulnerabilities
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. Panda: Security Analysis of Algorand Smart Contracts
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. Proxy Hunting: Upgradeable Smart Contracts
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. The Blockchain Imitation Game
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. Large Scale Study of Ethereum Arbitrage Ecosystem
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. A Mixed-Methods Study of Security Practices of Smart Contract Developers
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. Smart Learning to Find Dumb Contracts
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. Snapping Snap Sync: Attacks on Go Ethereum Nodes
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 9. Token Spammers, Rug Pulls, and Sniper Bots
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 10. Automated Inference on Financial Security of Ethereum
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 11. Your Exploit is Mine: Synthesizing Counterattack Smart Contract
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 12. Anatomy of a High-Profile Data Breach
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 13. Mixed Signals: Analyzing Bitcoin Mixing Service Economics
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 14. Is Your Wallet Snitching On You?
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🔒 ACM CCS 2024-2026

### 2025 (16篇)

#### 1. Denial of Sequencing Attacks in Ethereum Layer 2 Rollups
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. Towards a Formal Foundation for Blockchain Rollups ⭐
- **作者**: Stefanos Chaliasos 等
- **单位**: 
- **摘要**: Blockchains like Bitcoin and Ethereum have revolutionized digital transactions, yet scalability issues persist. Layer 2 solutions, such as validity proof Rollups (ZK-Rollups), aim to address these challenges by processing transactions off-chain and validating them on the main chain. However, concerns remain about security and censorship resistance.
- **中文摘要**: 比特币和以太坊等区块链已经彻底改变了数字交易，但可扩展性问题仍然存在。第2层解决方案（如有效性证明Rollups）旨在通过在链下处理交易并在主链上验证来应对这些挑战。然而，关于安全性和抗审查性的问题仍然存在。

#### 3. Forking the RANDAO: Manipulating Ethereum's Distributed Randomness Beacon
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. Bitcoin Under Volatile Block Rewards
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. On Frontrunning Risks in Batch-Order Fair Systems
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. Aegis: Tethering a Blockchain with Primary-Chain Stake
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. Accountable Liveness
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. Time Tells All: Deanonymization of Blockchain RPC Users
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2024 (16篇) ⭐

#### 1. fAmulet: Finding Finalization Failure Bugs in Polygon zkRollup ⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. TokenScout: Early Detection of Ethereum Scam Tokens ⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. Defying the Odds: Solana's Unexpected Resilience
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. Stealing Trust: Unraveling Blind Message Attacks in Web3 Authentication
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. FORAY: Towards Effective Attack Synthesis against Deep Logical Vulnerabilities in DeFi Protocols ⭐⭐
- **作者**: 
- **摘要**: Blockchain adoption has surged with the rise of Decentralized Finance (DeFi) applications. However, the significant value of digital assets managed by DeFi protocols makes them prime targets for attacks. Current smart contract vulnerability detection tools struggle with DeFi protocols due to deep logical bugs arising from complex financial interactions between multiple smart contracts.
- **中文摘要**: 随着去中心化金融（DeFi）应用的兴起，区块链采用率飙升。然而，DeFi协议管理的数字资产重大价值使其成为攻击的主要目标。现有的智能合约漏洞检测工具难以处理DeFi协议，因为多个智能合约之间复杂的金融交互导致了深层逻辑漏洞。

#### 6. Towards Automatic Discovery of Denial of Service Weaknesses
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. Rolling in the Shadows: Analyzing the Extraction of MEV Across Layer-2 Rollups
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. Lutris: A Blockchain Combining Broadcast and Consensus
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 9. Blockchain Bribing Attacks and the Efficacy of Counterincentives
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 10. zkLogin: Privacy-Preserving Blockchain Authentication
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 11. DoubleUp Roll: Double-spending in Arbitrum
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 12. Data Independent Order Policy Enforcement
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 13. Complete Knowledge: Preventing Encumbrance of Cryptographic Secrets
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 14. Characterizing Ethereum Address Poisoning Attack
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 15. Mempool Privacy via Batched Threshold Encryption
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 16. Derecho: Privacy Pools with Proof-Carrying Disclosures
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2023 (14篇)

#### 1. Demystifying DeFi MEV Activities in Flashbots Bundle
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. Lanturn: Measuring Economic Security Through Adaptive Learning
- **作者**: Kushal Babel, Mojan Javaheripi, Yan Ji, Mahimna Kelkar, Farinaz Koushanfar, Ari Juels
- **单位**: UC San Diego, Cornell Tech, IC3
- **摘要**: We introduce Lanturn: a general purpose adaptive learning-based framework for measuring the cryptoeconomic security of composed decentralized-finance (DeFi) smart contracts. Lanturn discovers strategies comprising of concrete transactions for extracting economic value from smart contracts interacting with a particular transaction environment.
- **中文摘要**: 我们引入了Lanturn：一个基于自适应学习的通用框架，用于测量组合去中心化金融（DeFi）智能合约的加密经济安全。Lanturn发现包含具体交易的策略，用于从与特定交易环境交互的智能合约中提取经济价值。

#### 3. Fuzz on the Beach: Fuzzing Solana Smart Contracts ⭐
- **作者**: 
- **摘要**: Solana has quickly emerged as a popular platform for building decentralized applications (DApps), such as marketplaces for non-fungible tokens (NFTs). A key reason for its success are Solana's low transaction fees and high performance, which is achieved in part due to its stateless programming model. Although the literature features extensive tooling support for smart contract security, current solutions are largely tailored for the Ethereum Virtual Machine.
- **中文摘要**: Solana迅速成为构建去中心化应用（DApps）的热门平台，如NFT市场。Solana成功的关键原因在于其低交易费用和高性能，这部分归功于其无状态编程模型。尽管文献中有广泛的智能合约安全工具支持，但当前解决方案主要用于以太坊虚拟机。

#### 4. TxPhishScope: Detecting Transaction-based Phishing on Ethereum
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. Uncle Maker: TimeStamping Out The Competition in Ethereum
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. TrustBoost: Boosting Trust among Interoperable Blockchains
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. Analyzing the Real-World Security of the Algorand Blockchain
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. Phoenix: Detect and Locate Resilience Issues in Blockchain
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 9. The Locality of Memory Checking
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 10. How Hard is Takeover in DPoS Blockchains?
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 11. Under the Dark: Stealthy Mining Pools Abuse
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 12. Understanding Security Issues in the NFT Ecosystem
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 13. Fait Accompli Committee Selection
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 14. Cryptocurrency wallets, security, usability
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2022 (4篇)

#### 1. Empirical Analysis of EIP-1559
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. Towards Automated Safety Vetting of Smart Contracts
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. VRust: Automated Vulnerability Detection for Solana Smart Contracts
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. Understanding Security Issues in the NFT Ecosystem
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🔒 NDSS 2024-2026

### 2026 (2篇)

#### 1. A Liveness Attack to Ethereum PoS with No Additional Cost
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2025 (12篇)

#### 1. PropertyGPT: LLM-driven Formal Verification
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. MTZK: Testing ZK Compilers
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. BunnyFinder
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. HOUSTON: DeFi Attack Detection
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. The Forking Way: When TEEs Meet Consensus
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. vetEOS
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. Cross-Layer STARKs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. Privacy-Preserving DeFi
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 9. DeFiRider
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 10. MEV Governance
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2024 (8篇)

#### 1. Declassify: Enabling Provers to Evade the Ethereum Honest-Majority Assumption
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. ZK-IMG: Private Image Verification
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. Scaling Law of Plasma
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. On the Anonymity of Nakamoto Consensus
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. BDF: Blockchain Disturbance Framework
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. Quantifying Maximal Extractable Value
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. A Foundation for Blockchain Privacy
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. SoK: Data Availability
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🛠 软件工程 2024-2026

### ICSE 2024-2026

#### 1. GPTScan ⭐⭐⭐
- **作者**: 
- **摘要**: Smart contracts are prone to various vulnerabilities, leading to substantial financial losses over time. Current analysis tools mainly target vulnerabilities with fixed control or data-flow patterns, such as re-entrancy and integer overflow. However, a recent study on Web3 security bugs revealed that about 80% of these bugs cannot be audited by existing tools due to the lack of domain-specific property description and checking. Given recent advances in Large Language Models (LLMs), it is worth exploring how Generative Pre-training Transformer (GPT) could aid in detecting logic vulnerabilities.
- **中文摘要**: 智能合约容易出现各种漏洞，导致长期重大财务损失。当前的分析工具主要针对具有固定控制或数据流模式的漏洞，如重入和整数溢出。然而，最近一项关于Web3安全漏洞的研究显示，由于缺乏特定领域的属性描述和检查，约80%的漏洞无法被现有工具审计。鉴于大型语言模型（LLM）的最新进展，值得探索生成式预训练Transformer（GPT）如何帮助检测逻辑漏洞。

#### 2. Are We There Yet? A Systematic Investigation of Smart Contract Fuzzing Techniques ⭐
- **作者**: Shuohan Wu 等
- **单位**: 香港科技大学
- **摘要**: Given the growing importance of smart contracts in various applications, ensuring their security and reliability is critical. Fuzzing, an effective vulnerability detection technique, has recently been widely applied to smart contracts. Despite numerous studies, a systematic investigation of smart contract fuzzing techniques remains lacking.
- **中文摘要**: 鉴于智能合约在各种应用中日益重要，确保其安全性和可靠性至关重要。模糊测试作为一种有效的漏洞检测技术，最近已被广泛应用于智能合约。尽管已有大量研究，但目前仍缺乏对智能合约模糊测试技术的系统调查。

#### 3. FlashSyn
- **作者**: 
- **摘要**: In decentralized finance (DeFi), lenders can offer flash loans to borrowers, i.e., loans that are only valid within a blockchain transaction and must be repaid with fees by the end of that transaction. Unlike normal loans, flash loans allow borrowers to borrow large assets without upfront collaterals deposits. Malicious adversaries use flash loans to gather large assets to exploit vulnerable DeFi protocols.
- **中文摘要**: 在去中心化金融（DeFi）中，贷方可以向借方提供闪电贷，即仅在区块链交易内有效的贷款，必须在该交易结束时偿还费用。与普通贷款不同，闪电贷允许借方无需预付抵押存款即可借入大量资产。恶意对手利用闪电贷收集大量资产来利用漏洞的DeFi协议。

#### 4. Stop Pulling my Rug
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. SCVHunter
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### ESEC/FSE 2024-2025

#### 1. Smartian
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. EVMFuzzer
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### ASE 2024-2025

#### 1. A Comprehensive Study on Smart Contract Programming Languages
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### ISSTA 2023-2025

#### 1. ItyFuzz: Fuzzer for Smart Contracts ⭐⭐
- **作者**: 
- **摘要**: Smart contracts are critical financial instruments, and their security is of utmost importance. However, smart contract programs are difficult to fuzz due to the persistent blockchain state behind all transactions. Mutating sequences of transactions are complex and often lead to a suboptimal exploration for both input and program spaces.
- **中文摘要**: 智能合约是关键的金融工具，其安全性至关重要。然而，由于所有交易背后存在的区块链状态，智能合约程序难以进行模糊测试。交易序列的变异复杂且经常导致输入和程序空间的次优探索。

#### 2. DeFiTainter
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. sCommit
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🔥 推荐阅读优先级

### 博二必读 ⭐⭐⭐

| 优先级 | 论文 | 会议 | 年份 | 方向 |
|--------|------|------|------|------|
| 1 | SoK: DeFi Attacks | S&P | 2023 | 整体认知 |
| 2 | Large-Scale Study of Vulnerability Scanners | S&P | 2024 | 方法论 |
| 3 | SMARTINV | S&P | 2024 | 不变量 |
| 4 | GPTScan | ICSE | 2024 | LLM+安全 |
| 5 | Nyx | S&P | 2024 | 前置交易 |
| 6 | POMABuster | S&P | 2024 | 预言机 |
| 7 | Flash Boys 2.0 | S&P | 2020 | MEV奠基 |
| 8 | FORAY | CCS | 2024 | 攻击合成 |
| 9 | Are We There Yet? | ICSE | 2024 | Fuzzing |
| 10 | ItyFuzz | ISSTA | 2023 | Fuzzing |

---

## 📝 说明

- 本文件正在持续更新中，已完成核心论文的摘要获取
- 由于工作量巨大（200+论文），正在逐步补充
- 论文数据和翻译由AI自动生成，可能存在误差
- 建议结合原文和TLDR综合阅读

---

*最后更新: 2026-03-15 | 正在进行中*
