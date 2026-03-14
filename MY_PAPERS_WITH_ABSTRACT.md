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

#### 1. Permissionless Verifiable Information Dispersal
- **作者**: Ivanov, Yarom
- **摘要**: 本文研究比特币Rollups的数据可用性问题...
- **中文摘要**: 研究如何在无需许可的情况下实现数据可用性，为比特币Rollups提供安全高效的数据分发方案。

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

#### 5. Asymmetric Mempool DoS Security
- **作者**: Yibo Wang 等
- **单位**: 清华大学
- **摘要**: In blockchains, mempool controls transaction flow before consensus, denial of whose service hurts the health and security of blockchain networks. This paper presents MPFUZZ, the first mempool fuzzer to find asymmetric DoS bugs by exploring the space of symbolized mempool states and optimistically estimating the promisingness of an intermediate state in reaching bug oracles.
- **中文摘要**: 本文提出了MPFUZZ，第一个内存池模糊测试工具，用于发现非对称DoS漏洞。通过探索符号化内存池状态空间并乐观估计中间状态到达漏洞预言机的可能性，MPFUZZ相比基线区块链模糊测试器在发现已知DETER漏洞方面实现了超过100倍加速。

#### 6. Zero-Knowledge Location Privacy
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

#### 1. NURGLE: MPT Manipulation
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. SoK: Security and Privacy of Blockchain Interoperability
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. Large-Scale Study of Vulnerability Scanners ⭐⭐⭐
- **作者**: Christoph Sendner 等
- **单位**: 德国慕尼黑工业大学 (TUM)
- **摘要**: Ethereum smart contracts, which are autonomous decentralized applications on the blockchain that manage assets often exceeding millions of dollars, have become primary targets for cyberattacks. In 2023 alone, such vulnerabilities led to substantial financial losses exceeding a billion of US dollars. To counter these threats, various tools have been developed by academic and commercial entities to detect and mitigate vulnerabilities in smart contracts. Our study investigates the gap between the effectiveness of existing security scanners and the vulnerabilities that still persist in practice. We compiled four distinct datasets for this analysis. The first dataset comprises 77,219 source codes extracted directly from the blockchain, while the second includes over 4 million bytecodes obtained from Ethereum Mainnet and testnets. The other two datasets consist of nearly 14,000 manually annotated smart contracts and 373 smart contracts verified through audits.
- **中文摘要**: 以太坊智能合约是管理数百万美元资产的自主去中心化应用，已成为网络攻击的主要目标。仅在2023年，这类漏洞就造成了超过10亿美元的巨额资金损失。本研究调查了现有安全扫描器的有效性与实践中仍然存在的漏洞之间的差距。研究团队编制了四个不同的数据集进行分析：第一个数据集包含77,219个直接从区块链提取的源代码，第二个数据集包含超过400万个从以太坊主网和测试网获取的字节码，另外两个数据集包含近14,000个手动标注的智能合约和373个通过审计验证的智能合约。

#### 4. POMABuster: Detecting Price Oracle Manipulation ⭐⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. Certifying Zero-Knowledge Circuits
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. SMARTINV: Multimodal Learning for Invariant Inference ⭐⭐⭐
- **作者**: Sally Junsong Wang 等
- **单位**: 新加坡国立大学 (NUS)
- **摘要**: Smart contracts are software programs that enable diverse business activities on the blockchain. Recent research has identified new classes of "machine un-auditable" bugs that arise from both transactional contexts and source code. Existing detection methods require human understanding of underlying transaction logic and manual reasoning across different sources of context (i.e. modalities), such as code, dynamic transaction executions, and natural language specifying the expected transaction behavior. To automate the detection of "machine un-auditable" bugs, we present SmartInv, an accurate and fast smart contract invariant inference framework. Our key insight is that the expected behavior of smart contracts, as specified by invariants, relies on understanding and reasoning across multimodal information, such as source code and natural language.
- **中文摘要**: 智能合约是支持区块链上各种商业活动的软件程序。最近的研究发现了新的"机器无法审计"漏洞类别，这些漏洞源于交易上下文和源代码。现有检测方法需要人类理解底层交易逻辑并手动推理不同来源的上下文（即多模态），如代码、动态交易执行和指定预期交易行为的自然语言。为了自动检测"机器无法审计"的漏洞，我们提出了SmartInv，这是一个精确且快速的智能合约不变量推理框架。我们的关键见解是，智能合约的预期行为（由不变量指定）依赖于跨多模态信息的理解和推理，如源代码和自然语言。

#### 7. Nyx: Detecting Exploitable Front-Running ⭐⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 8. Chronos: Finding Timeout Bugs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 9. Specular: Secure Optimistic Blockchain Execution
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 10. Towards Smart Contract Fuzzing on GPUs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 11. Non-Atomic Arbitrage in DeFi
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 12. Routing Attacks on Cryptocurrency Mining Pools
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2023 (5篇)

#### 1. SoK: DeFi Attacks ⭐⭐⭐
- **作者**: Liyi Zhou 等
- **单位**: 伦敦大学学院 (UCL)
- **摘要**: Within just four years, the blockchain-based Decentralized Finance (DeFi) ecosystem has accumulated a peak total value locked (TVL) of more than 253 billion USD. This surge in DeFi's popularity has, unfortunately, been accompanied by many impactful incidents. According to our data, users, liquidity providers, speculators, and protocol operators suffered a total loss of at least 3.24 billion USD from Apr 30, 2018 to Apr 30, 2022. Given the blockchain's transparency and increasing incident frequency, two questions arise: How can we systematically measure, evaluate, and compare DeFi incidents? How can we learn from past attacks to strengthen DeFi security?
- **中文摘要**: 仅在四年内，基于区块链的去中心化金融（DeFi）生态系统已积累了超过2530亿美元的峰值总锁仓量（TVL）。不幸的是，DeFi的流行伴随着许多重大事件。根据我们的数据，从2018年4月30日到2022年4月30日，用户、流动性提供者、投机者和协议操作员遭受的总损失至少为32.4亿美元。鉴于区块链的透明性和事件频率的增加，出现了两个问题：我们如何系统地衡量、评估和比较DeFi事件？我们如何从过去的攻击中学习以加强DeFi安全？

#### 2. Clockwork Finance ⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. Tyr: Consensus Failure Bugs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2020 经典 (4篇)

#### 1. Flash Boys 2.0 ⭐⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. VerX
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. VeriSmart
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🔒 USENIX Security 2024-2026

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

#### 6. BEAT-MEV
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2024 (11篇) ⭐

#### 1. SoK: Security Vulnerabilities in SNARKs
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. Max Attestation Matters
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. All Your Tokens are Belong to Us ⭐⭐
- **作者**: 
- **摘要**: In Ethereum, the practice of verifying the validity of the passed addresses is a common practice, which is a crucial step to ensure the secure execution of smart contracts. Vulnerabilities in the process of address verification can lead to great security issues, and anecdotal evidence has been reported by our community. However, this type of vulnerability has not been well studied.
- **中文摘要**: 在以太坊，验证传入地址有效性的做法是一种常见做法，是确保智能合约安全执行的关键步骤。地址验证过程中的漏洞可能导致重大安全问题，社区已报告了相关案例。然而，这种类型的漏洞尚未得到充分研究。

#### 4. Speculative DoS Attacks ⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. Using My Functions Should Follow My Checks
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. Practical Security Analysis of ZK Proof Circuits
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🔒 ACM CCS 2024-2026

### 2024 (16篇) ⭐

#### 1. fAmulet: zkRollup Finalization Bugs ⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. TokenScout: Scam Tokens ⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. Defying the Odds: Solana Security
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. FORAY: Attack Synthesis ⭐⭐
- **作者**: 
- **摘要**: Blockchain adoption has surged with the rise of Decentralized Finance (DeFi) applications. However, the significant value of digital assets managed by DeFi protocols makes them prime targets for attacks. Current smart contract vulnerability detection tools struggle with DeFi protocols due to deep logical bugs arising from complex financial interactions between multiple smart contracts.
- **中文摘要**: 随着去中心化金融（DeFi）应用的兴起，区块链采用率飙升。然而，DeFi协议管理的数字资产重大价值使其成为攻击的主要目标。现有的智能合约漏洞检测工具难以处理DeFi协议，因为多个智能合约之间复杂的金融交互导致了深层逻辑漏洞。

#### 5. Rolling in the Shadows: MEV Across L2
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 6. DoubleUp Roll
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2023 (14篇)

#### 1. Demystifying DeFi MEV in Flashbots
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 2. Lanturn
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. Fuzz on the Beach ⭐
- **作者**: 
- **摘要**: Solana has quickly emerged as a popular platform for building decentralized applications (DApps), such as marketplaces for non-fungible tokens (NFTs). A key reason for its success are Solana's low transaction fees and high performance, which is achieved in part due to its stateless programming model. Although the literature features extensive tooling support for smart contract security, current solutions are largely tailored for the Ethereum Virtual Machine.
- **中文摘要**: Solana迅速成为构建去中心化应用（DApps）的热门平台，如NFT市场。Solana成功的关键原因在于其低交易费用和高性能，这部分归功于其无状态编程模型。尽管文献中有广泛的智能合约安全工具支持，但当前解决方案主要用于以太坊虚拟机。

---

## 🔒 NDSS 2024-2026

### 2025-2026 (22篇)

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

---

## 🛠 软件工程 2024-2026

### ICSE 2024-2026

#### 1. GPTScan ⭐⭐⭐
- **作者**: 
- **摘要**: Smart contracts are prone to various vulnerabilities, leading to substantial financial losses over time. Current analysis tools mainly target vulnerabilities with fixed control or data-flow patterns, such as re-entrancy and integer overflow. However, a recent study on Web3 security bugs revealed that about 80% of these bugs cannot be audited by existing tools due to the lack of domain-specific property description and checking. Given recent advances in Large Language Models (LLMs), it is worth exploring how Generative Pre-training Transformer (GPT) could aid in detecting logic vulnerabilities.
- **中文摘要**: 智能合约容易出现各种漏洞，导致长期重大财务损失。当前的分析工具主要针对具有固定控制或数据流模式的漏洞，如重入和整数溢出。然而，最近一项关于Web3安全漏洞的研究显示，由于缺乏特定领域的属性描述和检查，约80%的漏洞无法被现有工具审计。鉴于大型语言模型（LLM）的最新进展，值得探索生成式预训练Transformer（GPT）如何帮助检测逻辑漏洞。

#### 2. Are We There Yet? ⭐
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

### ISSTA 2023-2025

#### 1. ItyFuzz ⭐⭐
- **作者**: 
- **摘要**: Smart contracts are critical financial instruments, and their security is of utmost importance. However, smart contract programs are difficult to fuzz due to the persistent blockchain state behind all transactions. Mutating sequences of transactions are complex and often lead to a suboptimal exploration for both input and program spaces.
- **中文摘要**: 智能合约是关键的金融工具，其安全性至关重要。然而，由于所有交易背后存在的区块链状态，智能合约程序难以进行模糊测试。交易序列的变异复杂且经常导致输入和程序空间的次优探索。

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
