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
- **作者**: Ben Fisch, Arthur Lazzaretti, Zeyu Liu, Lei Yang
- **单位**: 耶鲁大学, MIT
- **摘要**: Rollups是分布式状态机器上的特殊应用，底层状态机只记录日志但不执行交易。Rollups已成为在以太坊上扩展应用的流行方式，目前在比特币上运行Rollups的兴趣日益增长。本文研究了如何在无需许可的情况下实现数据可用性，构建了一个在比特币相同模型下安全的VID系统，使用状态机复制协议作为黑盒，具有向后兼容性。在比特币核心上实现了该系统，分析表明通信成本降低了1000倍以上，延迟降低了10倍以上。
- **中文摘要**: 研究如何在无需许可的情况下实现数据可用性，为比特币Rollups提供安全高效的数据分发方案。

#### 2. Asymmetric Mempool DoS Security
- **作者**: Wanning Ding, Yibo Wang 等
- **单位**: 清华大学
- **摘要**: In blockchains, mempool controls transaction flow before consensus, denial of whose service hurts the health and security of blockchain networks. This paper presents MPFUZZ, the first mempool fuzzer to find asymmetric DoS bugs by exploring the space of symbolized mempool states and optimistically estimating the promisingness of an intermediate state in reaching bug oracles.
- **中文摘要**: 本文提出了MPFUZZ，第一个内存池模糊测试工具，用于发现非对称DoS漏洞。通过探索符号化内存池状态空间并乐观估计中间状态到达漏洞预言机的可能性，MPFUZZ相比基线区块链模糊测试器在发现已知DETER漏洞方面实现了超过100倍加速。

---

### 2024 (17篇) ⭐ 重点

#### 1. Large-Scale Study of Vulnerability Scanners ⭐⭐⭐
- **作者**: Christoph Sendner 等
- **单位**: 德国慕尼黑工业大学 (TUM)
- **摘要**: Ethereum smart contracts, which are autonomous decentralized applications on the blockchain that manage assets often exceeding millions of dollars, have become primary targets for cyberattacks. In 2023 alone, such vulnerabilities led to substantial financial losses exceeding a billion of US dollars. To counter these threats, various tools have been developed by academic and commercial entities to detect and mitigate vulnerabilities in smart contracts. Our study investigates the gap between the effectiveness of existing security scanners and the vulnerabilities that still persist in practice.
- **中文摘要**: 以太坊智能合约是管理数百万美元资产的自主去中心化应用，已成为网络攻击的主要目标。仅在2023年，这类漏洞就造成了超过10亿美元的巨额资金损失。本研究调查了现有安全扫描器的有效性与实践中仍然存在的漏洞之间的差距。研究团队编制了四个不同的数据集进行分析：77,219个源代码、400万个字节码、近14,000个手动标注的智能合约和373个通过审计验证的智能合约。

#### 2. SMARTINV: Multimodal Learning for Invariant Inference ⭐⭐⭐
- **作者**: Sally Junsong Wang 等
- **单位**: 新加坡国立大学 (NUS)
- **摘要**: Smart contracts are software programs that enable diverse business activities on the blockchain. Recent research has identified new classes of "machine un-auditable" bugs that arise from both transactional contexts and source code. Existing detection methods require human understanding of underlying transaction logic and manual reasoning across different sources of context. To automate the detection of "machine un-auditable" bugs, we present SmartInv, an accurate and fast smart contract invariant inference framework.
- **中文摘要**: 智能合约是支持区块链上各种商业活动的软件程序。最近的研究发现了新的"机器无法审计"漏洞类别，这些漏洞源于交易上下文和源代码。SmartInv是一个精确且快速的智能合约不变量推理框架，能够跨多模态信息理解和推理，自动检测"机器无法审计"的漏洞。实验表明，SmartInv在89,621个真实合约中发现119个零日漏洞，其中5个被开发者确认为"高严重性"。

#### 3. SoK: Security and Privacy of Blockchain Interoperability
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 4. POMABuster: Detecting Price Oracle Manipulation ⭐⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 5. Pianist: Scalable zkRollups via Fully Distributed Zero-Knowledge Proofs
- **作者**: Tianyi Liu, Tiancheng Xie, Jiaheng Zhang, Dawn Song, Yupeng Zhang
- **单位**: UC Berkeley, UIUC
- **摘要**: In the past decade, blockchains have seen various financial and technological innovations. However, scalability is one of the key issues. zkRollups and zkEVM techniques using zero-knowledge proofs (ZKPs) have been proposed. However, proof generation of the ZKP is the bottleneck. We improve scalability by proposing new schemes of fully distributed ZKPs. With our schemes, the ZKP generation can be distributed to multiple participants in a model similar to mining pools.
- **中文摘要**: 本文提出了Pianist，一个完全分布式的ZKP系统。对于M个大小为T的子电路，使用M台机器， prover时间为O(T log T + M log M)，而原始Plonk在单台机器上为O(MT log(MT))。Pianist可以在64台机器上在313秒内生成8192笔交易的证明，扩展性提升64倍。

#### 6. Nyx: Detecting Exploitable Front-Running ⭐⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 7. Conning the Crypto Conman
- **作者**: Bhupendra Acharya 等
- **单位**: 
- **摘要**: The mainstream adoption of cryptocurrencies has led to a surge in wallet-related issues reported by ordinary users on social media platforms. In parallel, there is an increase in an emerging fraud trend called cryptocurrency-based technical support scam, in which fraudsters offer fake wallet recovery services and target users experiencing wallet-related issues.
- **中文摘要**: 主流加密货币的采用导致社交媒体平台上与钱包相关的问题激增。本文提出了一个名为HoneyTweet的分析框架，通过发布25000条虚假钱包支持推文来吸引超过9000名骗子，跟踪骗子在Twitter、Email、Instagram或Telegram等渠道的诈骗活动，并分析了他们的支付方式和诈骗模式。

---

### 2023 (5篇)

#### 1. SoK: DeFi Attacks ⭐⭐⭐
- **作者**: Liyi Zhou 等
- **单位**: 伦敦大学学院 (UCL)
- **摘要**: Within just four years, the blockchain-based Decentralized Finance (DeFi) ecosystem has accumulated a peak total value locked (TVL) of more than 253 billion USD. This surge in DeFi's popularity has, unfortunately, been accompanied by many impactful incidents. According to our data, users, liquidity providers, speculators, and protocol operators suffered a total loss of at least 3.24 billion USD from Apr 30, 2018 to Apr 30, 2022.
- **中文摘要**: 仅在四年内，DeFi生态系统积累了超过2530亿美元的峰值TVL。从2018年4月30日到2022年4月30日，用户遭受的总损失至少为32.4亿美元。本文调查了77篇学术论文、30份审计报告和181个真实事件，发现学术界与实践者社区之间存在若干差距。

#### 2. Clockwork Finance ⭐
- **作者**: Kushal Babel, Philip Daian, Mahimna Kelkar, Ari Juels
- **单位**: Cornell Tech
- **摘要**: We introduce the Clockwork Finance Framework (CFF), a general purpose, formal verification framework for mechanized reasoning about the economic security properties of composed decentralized-finance (DeFi) smart contracts. CFF features three key properties: contract complete, asymptotically constant model overhead, and attack-exhaustive by construction.
- **中文摘要**: 本文介绍了Clockwork Finance Framework (CFF)，一个用于推理组合DeFi智能合约经济安全属性的通用形式化验证框架。CFF能够自动提取所有可能的经济攻击，在无需任何明确编程攻击策略的情况下，平均每月发现5600万美元的可提取价值。

---

### 2022 (2篇)

#### 1. Quantifying Blockchain Extractable Value (How dark is the forest?) ⭐⭐⭐
- **作者**: Kaihua Qin 等
- **单位**: 
- **摘要**: Permissionless blockchains such as Bitcoin have excelled at financial services. Yet, opportunistic traders extract monetary value from the mesh of decentralized finance (DeFi) smart contracts through so-called blockchain extractable value (BEV). We estimate that over 32 months, BEV yielded 540.54M USD in profit, divided among 11,289 addresses. The highest BEV instance we find amounts to 4.1M USD, 616.6x the Ethereum block reward.
- **中文摘要**: 机会主义交易者通过区块链可提取价值(BEV)从DeFi智能合约中获取 monetary value。据估计，在32个月内，BEV产生了5.4054亿美元的利润，分给11289个地址。发现的最高BEV实例达到410万美元，相当于以太坊区块奖励的616.6倍。

---

### 2020 经典 (4篇)

#### 1. Flash Boys 2.0 ⭐⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🔒 USENIX Security 2024-2026

### 2024 (11篇) ⭐

#### 1. All Your Tokens are Belong to Us: Address Verification Vulnerabilities ⭐⭐
- **作者**: 
- **摘要**: In Ethereum, the practice of verifying the validity of the passed addresses is a common practice, which is a crucial step to ensure the secure execution of smart contracts. Vulnerabilities in the process of address verification can lead to great security issues, and anecdotal evidence has been reported by our community. However, this type of vulnerability has not been well studied.
- **中文摘要**: 在以太坊，验证传入地址有效性的做法是一种常见做法，是确保智能合约安全执行的关键步骤。地址验证过程中的漏洞可能导致重大安全问题，社区已报告了相关案例。然而，这种类型的漏洞尚未得到充分研究。

#### 2. Speculative Denial-of-Service Attacks in Ethereum ⭐⭐
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2023 (14篇)

#### 1. Large Scale Study of Ethereum Arbitrage Ecosystem
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🔒 ACM CCS 2024-2026

### 2024 (16篇) ⭐

#### 1. FORAY: Attack Synthesis ⭐⭐
- **作者**: 
- **摘要**: Blockchain adoption has surged with the rise of Decentralized Finance (DeFi) applications. However, the significant value of digital assets managed by DeFi protocols makes them prime targets for attacks. Current smart contract vulnerability detection tools struggle with DeFi protocols due to deep logical bugs arising from complex financial interactions between multiple smart contracts.
- **中文摘要**: 随着DeFi应用的兴起，区块链采用率飙升。然而，DeFi协议管理的数字资产重大价值使其成为攻击的主要目标。现有的智能合约漏洞检测工具难以处理DeFi协议，因为多个智能合约之间复杂的金融交互导致了深层逻辑漏洞。

#### 2. TokenScout: Early Detection of Ethereum Scam Tokens
- **作者**: 
- **摘要**: 
- **中文摘要**: 

#### 3. DoubleUp Roll: Double-spending in Arbitrum
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

### 2023 (14篇)

#### 1. Lanturn: Measuring Economic Security of Smart Contracts
- **作者**: Kushal Babel, Mojan Javaheripi, Yan Ji, Mahimna Kelkar, Farinaz Koushanfar, Ari Juels
- **单位**: UC San Diego, Cornell Tech, IC3
- **摘要**: We introduce Lanturn: a general purpose adaptive learning-based framework for measuring the cryptoeconomic security of composed DeFi smart contracts. Lanturn discovers strategies comprising concrete transactions for extracting economic value from smart contracts. We formulate the strategy discovery as a black-box optimization problem and leverage a novel adaptive learning-based algorithm.
- **中文摘要**: 本文提出了Lanturn，一个基于自适应学习的通用框架，用于测量组合DeFi智能合约的加密经济安全。Lanturn能够发现从智能合约中提取经济价值的具体交易策略，在Sushiswap、UniswapV2、UniswapV3和AaveV2的历史数据上进行评估，不仅重新发现了现有的已知策略，还发现了之前未记录的新策略。

#### 2. Fuzz on the Beach: Fuzzing Solana Smart Contracts ⭐
- **作者**: Jens-Rene Giesen 等
- **摘要**: Solana has quickly emerged as a popular platform for building decentralized applications (DApps). A key reason for its success are Solana's low transaction fees and high performance, which is achieved in part due to its stateless programming model. Although the literature features extensive tooling support for smart contract security, current solutions are largely tailored for the Ethereum Virtual Machine.
- **中文摘要**: Solana迅速成为构建DApps的热门平台，如NFT市场。成功的关键原因在于低交易费用和高性能，这部分归功于其无状态编程模型。本文提出了FuzzDelSol，这是第一个针对Solana智能合约的二进制覆盖率引导模糊测试架构。

#### 3. TxPhishScope: Transaction-based Phishing on Ethereum
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🔒 NDSS 2024-2026

### 2025-2026 (22篇)

#### 1. The Forking Way: When TEEs Meet Consensus
- **作者**: 
- **摘要**: 
- **中文摘要**: 

---

## 🛠 软件工程 2024-2026

### ICSE 2024-2026

#### 1. GPTScan ⭐⭐⭐
- **作者**: 
- **摘要**: Smart contracts are prone to various vulnerabilities, leading to substantial financial losses over time. Current analysis tools mainly target vulnerabilities with fixed control or data-flow patterns, such as re-entrancy and integer overflow. However, a recent study on Web3 security bugs revealed that about 80% of these bugs cannot be audited by existing tools due to the lack of domain-specific property description and checking. Given recent advances in Large Language Models (LLMs), it is worth exploring how Generative Pre-training Transformer (GPT) could aid in detecting logic vulnerabilities.
- **中文摘要**: 智能合约容易出现各种漏洞，导致长期重大财务损失。当前的分析工具主要针对具有固定控制或数据流模式的漏洞。然而，最近一项关于Web3安全漏洞的研究显示，约80%的漏洞无法被现有工具审计。鉴于大型语言模型(LLM)的最新进展，值得探索GPT如何帮助检测逻辑漏洞。

#### 2. Are We There Yet? ⭐
- **作者**: Shuohan Wu 等
- **单位**: 香港科技大学
- **摘要**: Given the growing importance of smart contracts in various applications, ensuring their security and reliability is critical. Fuzzing, an effective vulnerability detection technique, has recently been widely applied to smart contracts. Despite numerous studies, a systematic investigation of smart contract fuzzing techniques remains lacking.
- **中文摘要**: 鉴于智能合约在各种应用中日益重要，确保其安全性和可靠性至关重要。模糊测试作为一种有效的漏洞检测技术，最近已被广泛应用于智能合约。尽管已有大量研究，但目前仍缺乏对智能合约模糊测试技术的系统调查。

#### 3. FlashSyn: Flash Loan Attack Synthesis
- **作者**: 
- **摘要**: In decentralized finance (DeFi), lenders can offer flash loans to borrowers, i.e., loans that are only valid within a blockchain transaction and must be repaid with fees by the end of that transaction. Unlike normal loans, flash loans allow borrowers to borrow large assets without upfront collaterals deposits. Malicious adversaries use flash loans to gather large assets to exploit vulnerable DeFi protocols.
- **中文摘要**: 在DeFi中，贷方可以向借方提供闪电贷，即仅在区块链交易内有效的贷款。恶意对手利用闪电贷收集大量资产来利用漏洞的DeFi协议。

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
| 8 | Quantifying BEV | S&P | 2022 | MEV |
| 9 | FORAY | CCS | 2024 | 攻击合成 |
| 10 | Are We There Yet? | ICSE | 2024 | Fuzzing |
| 11 | ItyFuzz | ISSTA | 2023 | Fuzzing |
| 12 | Lanturn | CCS | 2023 | 经济安全 |
| 13 | Clockwork Finance | S&P | 2023 | 经济安全 |
| 14 | Pianist | S&P | 2024 | zkRollup |
| 15 | Conning the Crypto Conman | S&P | 2024 | 诈骗分析 |

---

## 📝 说明

- 本文件正在持续更新中，已完成核心论文的摘要获取
- 由于工作量巨大（200+论文），正在逐步补充
- 论文数据和翻译由AI自动生成，可能存在误差
- 建议结合原文和TLDR综合阅读

---

*最后更新: 2026-03-15 | 正在进行中*
