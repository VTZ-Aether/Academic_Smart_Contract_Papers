# 🎯 智能合约安全论文精选 (2024-2026)

> 专注近三年顶会论文，按研究领域分类，方便快速定位
> 整理自 [VTZ-Aether/Academic_Smart_Contract_Papers](https://github.com/VTZ-Aether/Academic_Smart_Contract_Papers)

---

## 📌 快速索引

- [🔒 网络安全 / 密码学](#-网络安全--密码学)
- [🛠 软件工程](#-软件工程)
- [🌐 其他（分布式系统/网络/数据库）](#-其他分布式系统网络数据库)
- [🔥 推荐阅读优先级](#-推荐阅读优先级)

---

## 🔒 网络安全 / 密码学

> 涵盖：漏洞检测、形式化验证、攻击分析、隐私保护、密码学应用
> 来源会议：IEEE S&P, USENIX Security, ACM CCS, NDSS, IEEE DSN

### IEEE S&P (Oakland) 2024-2026 ⭐

#### 2026
- [security] [A Liveness Attack to Ethereum PoS with No Additional Cost]()

#### 2025 ⭐
- [security] [Asymmetric Mempool DoS Security: Formal Definitions and Provable Secure Designs](https://arxiv.org/pdf/2407.03543)
- [security] [Zero-Knowledge Location Privacy via Accurate Floating-Point SNARKs](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a057/21B7R3HsGK4)
- [security] [Volatile and Persistent Memory for zkSNARKs via Algebraic Interactive Proofs](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a054/21B7R0YQXtK)
- [security] [Phecda: Post-Quantum Transparent zkSNARKs](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a055/21B7R1Oem1q)
- [security] [Security Perceptions of Users in Stablecoins](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a042/21B7QvjJ9Ty)
- [security] [P2C2T: Preserving the Privacy of Cross-Chain Transfer](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a051/21B7QYE5x8Q)
- [security] [Permissionless Verifiable Information Dispersal](https://eprint.iacr.org/2024/1299.pdf)
- [security] [An Attack on TON's ADNL Secure Channel Protocol](https://eprint.iacr.org/2025/818.pdf)
- [security] [Decentralization of Ethereum's Builder Market](https://arxiv.org/pdf/2405.01329)

#### 2024 ⭐ 重点
- [security] [NURGLE: Exacerbating Resource Consumption in Blockchain State Storage via MPT Manipulation](https://github.com/hzysvilla/Nurgle_Oakland24/blob/main/Nurgle_oakland24.pdf)
- [security] [SoK: Security and Privacy of Blockchain Interoperability](https://www.techrxiv.org/doi/pdf/10.36227/techrxiv.24595764)
- [security] [Large-Scale Study of Vulnerability Scanners for Ethereum Smart Contracts](https://arxiv.org/abs/2312.16533) | **[TLDR](TLDR.md#24_5_20)**
- [security] [POMABuster: Detecting Price Oracle Manipulation Attacks in DeFi](https://www.dropbox.com/scl/fi/ye9ij7m782bbr2lckt20e/IEEES_P24-camera-ready.pdf) | **[TLDR](TLDR.md#24_5_22)** ⭐
- [security] [SMARTINV: Multimodal Learning for Smart Contract Invariant Inference](https://arxiv.org/abs/2411.09217) | **[TLDR](TLDR.md#24_2_22)**
- [security] [Nyx: Detecting Exploitable Front-Running Vulnerabilities in Smart Contracts](papers/sp24_Nyx.pdf) | **[TLDR](TLDR.md#24_2_12)** ⭐
- [security] [Towards Smart Contract Fuzzing on GPUs](https://chapering.github.io/pubs/sp24weimin.pdf)
- [security] [Certifying Zero-Knowledge Circuits with Refinement Types](https://eprint.iacr.org/2023/547.pdf)
- [security] [Specular: Towards Secure, Trust-minimized Optimistic Blockchain Execution](https://arxiv.org/pdf/2212.05219.pdf)
- [security] [Chronos: Finding Timeout Bugs in Distributed Systems](http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/paper_from_24/Chronos_sp24.pdf)
- [security] [Non-Atomic Arbitrage in DeFi](https://scholar.google.com/scholar?q=Non-Atomic+Arbitrage+in+Decentralized+Finance)

#### 2023
- [security] [SoK: Decentralized Finance (DeFi) Attacks](https://arxiv.org/pdf/2208.13035.pdf) | **[TLDR](TLDR.md#sp23_CF)** ⭐⭐⭐
- [security] [Clockwork Finance: Automated Analysis of Economic Security in Smart Contracts](https://eprint.iacr.org/2021/1147.pdf) | **[TLDR](TLDR.md#sp23_CF)** ⭐
- [security] [Tyr: Finding Consensus Failure Bugs in Blockchain System](https://csdl-downloads.ieeecomputer.org/proceedings/sp/2023/9336/00/933600b186.pdf)
- [security] [WeRLman: To Tackle Whale (Transactions), Go Deep (RL)](https://roibarzur.github.io/assets/pdfs/werlman-systor-poster-2022.pdf)

#### 2022
- [security] [Quantifying Blockchain Extractable Value: How dark is the forest?](https://arxiv.org/pdf/2101.05511.pdf) | **[TLDR](TLDR.md#23_8_28)**
- [security] [SAILFISH: Vetting Smart Contract State-Inconsistency Bugs in Seconds](https://arxiv.org/pdf/2104.08638.pdf)

#### 2021
- [security] [SmartPulse: Automated Checking of Temporal Properties in Smart Contracts](https://www.microsoft.com/en-us/research/uploads/prod/2021/02/SmartPulse-Oakland21-preprint.pdf)
- [security] [sGUARD: Towards Fixing Vulnerable Smart Contracts Automatically](https://arxiv.org/abs/2101.01917)
- [security] [Compositional Security for Reentrant Applications](https://arxiv.org/abs/2103.08577) | **[TLDR](TLDR.md#23_10_24)**

#### 2020 经典
- [security] [Flash Boys 2.0: Frontrunning in Decentralized Exchanges, MEV](https://par.nsf.gov/servlets/purl/10159474) ⭐⭐⭐ 必读
- [security] [VerX: Safety Verification of Smart Contracts](https://files.sri.inf.ethz.ch/website/papers/sp20-verx.pdf)
- [security] [VeriSmart: A Highly Precise Safety Verifier for Ethereum Smart Contracts](https://arxiv.org/pdf/1908.11227.pdf)
- [security] [Executable Operational Semantics of Solidity](https://arxiv.org/pdf/1804.01295.pdf)

---

### USENIX Security 2024-2026

#### 2026
- [security] [Lost in Blockchain Address Misuse: Cross-Platform Security Impact](https://baolingfeng.github.io/papers/sec26cycle1-final911.pdf)

#### 2025 ⭐
- [security] [Auspex: Transaction Fee Mechanism Bugs](https://www.usenix.org/system/files/usenixsecurity25-he-zheyuan.pdf)
- [security] [Deanonymizing Ethereum Validators: P2P Privacy Issues](https://arxiv.org/pdf/2409.04366)
- [security] [SoK: Understanding zk-SNARKs: Research vs Practice](https://eprint.iacr.org/2025/172.pdf)
- [security] [Surviving in Dark Forest: Evading Front-Running Bots](https://www.usenix.org/system/files/conference/usenixsecurity25/sec25cycle1-prepub-1302-ma-zuchao.pdf)
- [security] [Available Attestation: Reorg-Resilient Solution for Ethereum PoS](https://eprint.iacr.org/2025/097.pdf)
- [security] [Following Devils' Footprint: Price Manipulation Detection](https://www.usenix.org/system/files/conference/usenixsecurity25/sec25cycle1-prepub-750-zhang-bosi.pdf)
- [security] [BEAT-MEV: Batched Threshold Encryption for MEV Prevention](https://eprint.iacr.org/2024/1533.pdf)
- [security] [COLLISIONREPAIR: Storage Collision Vulnerabilities Patching]()

#### 2024 ⭐
- [security] [SoK: Security Vulnerabilities in SNARKs](https://www.usenix.org/system/files/usenixsecurity24-chaliasos.pdf)
- [security] [Speculative Denial-of-Service Attacks in Ethereum](https://www.usenix.org/system/files/sec24summer-prepub-32-yaish.pdf) | **[TLDR](TLDR.md#24_11_1)** ⭐
- [security] [Max Attestation Matters: Ethereum PoS Incentives](https://www.usenix.org/system/files/usenixsecurity24-zhang-mingfei.pdf) | **[TLDR](TLDR.md#24_11_1)**
- [security] [All Your Tokens are Belong to Us: Address Verification Vulnerabilities](https://arxiv.org/pdf/2405.20561)
- [security] [Using My Functions Should Follow My Checks: Insecure OpenZeppelin Code](https://www.usenix.org/system/files/usenixsecurity24-liu-han.pdf)
- [security] [Practical Security Analysis of Zero-Knowledge Proof Circuits](https://eprint.iacr.org/2023/190.pdf)
- [security] [Understanding Ethereum Mempool Security under Asymmetric DoS](https://arxiv.org/pdf/2312.02642)

#### 2023
- [security] [Confusum Contractum: Confused Deputy Vulnerabilities in Ethereum](https://www.usenix.org/system/files/usenixsecurity23-gritti.pdf)
- [security] [Panda: Security Analysis of Algorand Smart Contracts](https://arxiv.org/pdf/2009.02663)
- [security] [Proxy Hunting: Upgradeable Smart Contracts](https://yueduan.github.io/pub/uschunt_usenix23.pdf)
- [security] [The Blockchain Imitation Game](https://www.usenix.org/system/files/sec23fall-prepub-331-qin.pdf)
- [security] [Large Scale Study of Ethereum Arbitrage Ecosystem](https://www.usenix.org/system/files/sec23fall-prepub-515-mclaughlin.pdf) | **[TLDR](TLDR.md#23_8_29)**
- [security] [Smart Learning to Find Dumb Contracts](https://www.usenix.org/system/files/usenixsecurity23-abdelaziz.pdf) | **[TLDR](TLDR.md#23_9_4)**
- [security] [Token Spammers, Rug Pulls, and Sniper Bots](https://arxiv.org/pdf/2206.08202.pdf) | **[TLDR](TLDR.md#23_9_7)**
- [security] [Your Exploit is Mine: Synthesizing Counterattack Smart Contract](https://www.usenix.org/system/files/usenixsecurity23-zhang-zhuo-exploit.pdf) | **[TLDR](TLDR.md#23_9_18)**

#### 2022
- [security] [How to Peel a Million: Validating and Expanding Bitcoin Clusters](https://www.usenix.org/system/files/sec22-kappos.pdf)
- [security] [Total Eclipse of the Heart: Disrupting IPFS](https://www.usenix.org/system/files/sec22-prunster.pdf)

#### 2021
- [security] [EOSAFE: Security Analysis of EOSIO Smart Contracts](http://sei.pku.edu.cn/~yaoguo/papers/He-Security-21.pdf)
- [security] [SmarTest: Hunting Vulnerable Transaction Sequences via Language Model-Guided Symbolic Execution](http://prl.korea.ac.kr/~ssb920/papers/sec21.pdf)
- [security] [EVMPatch: Timely and Automated Patching of Ethereum Smart Contracts](https://www.usenix.org/system/files/sec21summer_rodler.pdf)

#### 2020 经典
- [security] [ETHBMC: A Bounded Model Checker for Smart Contracts](https://www.usenix.org/system/files/sec20-frank.pdf)
- [security] [TXSPECTOR: Uncovering Attacks in Ethereum from Transactions](https://www.usenix.org/system/files/sec20-zhang-mengya.pdf)
- [security] [BlockSci: Design and applications of a blockchain analysis platform](https://www.usenix.org/system/files/sec20-kalodner.pdf)

---

### ACM CCS 2024-2026

#### 2025 ⭐
- [security] [Denial of Sequencing Attacks in Ethereum Layer 2 Rollups]()
- [security] [Towards a Formal Foundation for Blockchain Rollups](https://arxiv.org/pdf/2406.16219)
- [security] [Forking the RANDAO: Manipulating Ethereum's Randomness]()
- [security] [Time Tells All: Deanonymization of Blockchain RPC Users]()

#### 2024 ⭐ 重点
- [security] [fAmulet: Finding Finalization Failure Bugs in Polygon zkRollup](https://arxiv.org/pdf/2410.12210) | **[TLDR](TLDR.md#24_12_15)**
- [security] [TokenScout: Early Detection of Ethereum Scam Tokens](https://cactilab.github.io/assets/pdf/3658644.3690234.pdf) | **[TLDR](TLDR.md#24_9_18)**
- [security] [Defying the Odds: Solana's Security Challenges](https://arxiv.org/pdf/2406.13599)
- [security] [Stealing Trust: Blind Message Attacks in Web3 Authentication](https://diaowenrui.github.io/paper/ccs24-yan.pdf)
- [security] [FORAY: Attack Synthesis against DeFi Logical Vulnerabilities](https://www.arxiv.org/pdf/2407.06348)
- [security] [Towards Automatic Discovery of DoS Weaknesses in Blockchain](https://ffeng-luo.github.io/papers/ccs24.pdf)
- [MEV] [Rolling in the Shadows: MEV Across Layer-2 Rollups](https://ben-weintraub.com/files/rolling-in-the-shadows.pdf)
- [security] [DoubleUp Roll: Double-spending in Arbitrum](https://0xzhiyuan.github.io/files/DoubleUp_Roll__Final_Version_.pdf) | **[TLDR](TLDR.md#25_2_14)**
- [security] [Characterizing Ethereum Address Poisoning Attack]()

#### 2023
- [security] [Demystifying DeFi MEV Activities in Flashbots Bundle](https://zzzihao-li.github.io/papers/CCS23_Bundle_MEV_full_version.pdf) | **[TLDR](TLDR.md#23_9_25)**
- [security] [Lanturn: Economic Security of Smart Contracts via Adaptive Learning](https://eprint.iacr.org/2023/1338) | **[TLDR](TLDR.md#23_12_6)**
- [security] [TxPhishScope: Transaction-based Phishing on Ethereum](https://yajin.org/papers/ccs23_phishing.pdf) | **[TLDR](TLDR.md#23_11_25)**
- [security] [Uncle Maker: (Time)Stamping Out The Competition in Ethereum](https://eprint.iacr.org/2022/1020.pdf) | **[TLDR](TLDR.md#24_3_19)**
- [security] [Phoenix: Detect Resilience Issues in Blockchain](http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/CCS23.pdf) | **[TLDR](TLDR.md#23_10_18)**
- [security] [Fuzz on the Beach: Fuzzing Solana Smart Contracts](https://arxiv.org/pdf/2309.03006.pdf) | **[TLDR](TLDR.md#23_9_28)**

#### 2022
- [security] [Empirical Analysis of EIP-1559](https://arxiv.org/pdf/2201.05574.pdf)
- [security] [Towards Automated Safety Vetting of Smart Contracts in DApps](https://yueduan.github.io/pub/smart_contracts_analysis__ccs22.pdf) | **[TLDR](TLDR.md#23_9_2)**
- [security] [VRust: Automated Vulnerability Detection for Solana](https://dl.acm.org/doi/pdf/10.1145/3548606.3560552) | **[TLDR](TLDR.md#ccs22_vrust)**

#### 经典
- [security] [Securify: Practical Security Analysis of Smart Contracts](https://dl.acm.org/doi/pdf/10.1145/3243734.3243780) (CCS 2018)
- [security] [Making Smart Contracts Smarter](https://dl.acm.org/doi/pdf/10.1145/2976749.2978309) (CCS 2016)

---

### NDSS 2024-2026

#### 2026 ⭐
- [security] [BunnyFinder: Finding Incentive Flaws for Ethereum Consensus]()
- [security] [HOUSTON: Real-Time Anomaly Detection of DeFi Attacks]()
- [security] [MEVisor: High-Throughput MEV Discovery in DEXs with GPU]()
- [security] [Validity Is Not Enough: Security Pitfall in Chainlink's OCR]()
- [security] [Phishing in Wonderland: Ethereum Phishing Detection]()

#### 2025
- [security] [Alba: The Dawn of Scalable Bridges for Blockchains](https://eprint.iacr.org/2024/197.pdf)

*(更多 NDSS 论文待补充)*

---

## 🛠 软件工程

> 涵盖：程序分析、代码生成、测试、Fuzzing、程序语言理论
> 来源会议：ICSE, ESEC/FSE, ASE, ISSTA, OOPSLA, PLDI, POPL

### ICSE (软件工程国际会议)

#### 2024
- [待补充]()

#### 2023
- [待补充]()

---

### ESEC/FSE (软件工程基础原理)

#### 2024
- [待补充]()

#### 2023
- [待补充]()

---

### ASE (自动化软件工程)

#### 2024
- [待补充]()

---

### ISSTA (软件测试与分析)

#### 2024
- [待补充]()

---

### PLDI / OOPSLA / POPL (编程语言)

#### 2024-2026
- [待补充 - 欢迎PR补充]()

---

## 🌐 其他（分布式系统/网络/数据库）

> 涵盖：共识协议、存储系统、网络、性能优化
> 来源会议：SOSP, OSDI, EuroSys, ICDCS, SIGMETRICS, VLDB, SIGMOD, INFOCOM, WWW

### SOSP / OSDI (操作系统)

#### 2024-2026
- [待补充]()

---

### EuroSys

#### 2024-2026
- [待补充]()

---

### IEEE ICDCS

#### 2024-2026
- [待补充]()

---

### SIGMETRICS / VLDB / SIGMOD

#### 2024-2026
- [待补充]()

---

### WWW (Web)

#### 2024-2026
- [待补充]()

---

## 🔥 推荐阅读优先级

### 博二必读 ⭐⭐⭐
| 论文 | 会议 | 年份 | 方向 |
|------|------|------|------|
| SoK: DeFi Attacks | S&P | 2023 | 整体认知 |
| Flash Boys 2.0 | S&P | 2020 | MEV 奠基 |
| Nyx: Detecting Front-Running | S&P | 2024 | 漏洞检测 |
| SMARTINV: Invariant Inference | S&P | 2024 | 不变量推断 |
| Large-Scale Study of Vulnerability Scanners | S&P | 2024 | 方法论 |
| Speculative DoS Attacks | USENIX Sec | 2024 | DoS 攻击 |

### 深入方向 ⭐⭐
| 论文 | 会议 | 年份 | 方向 |
|------|------|------|------|
| POMABuster | S&P | 2024 | 预言机操纵 |
| Clockwork Finance | S&P | 2023 | 经济安全 |
| fAmulet | CCS | 2024 | zkRollup |
| TokenScout | CCS | 2024 | 诈骗检测 |
| FORAY | CCS | 2024 | 攻击合成 |
| VeriSmart | S&P | 2020 | 形式化验证 |
| VerX | S&P | 2020 | 形式化验证 |

### 基础背景 ⭐
| 论文 | 会议 | 年份 |
|------|------|------|
| Securify | CCS | 2018 |
| teEther | USENIX Sec | 2018 |
| SmartPool | USENIX Sec | 2017 |

---

## 📝 我的笔记

> 在此记录你的阅读笔记、想法、复现计划等

### 2024-XX-XX
- 

### 
- 

---

*最后更新: 2026-03-15*
