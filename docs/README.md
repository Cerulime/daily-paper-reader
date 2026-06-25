<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-27 ~ 2026-06-25
- 运行时间：2026-06-25 08:05:09 UTC
- 运行状态：成功
- 本次总论文数：42
- 精读区：0
- 速读区：42

### 今日简报（AI）
今日速读42篇前沿论文，聚焦二进制分析与系统安全，三篇满分研究点亮核心突破。  
从动态代码的符号库解析到内核级数据流精准提取，再到加密虚拟化的形式化验证，展示自动化与可信计算的新高度。  
建议安全工程师重点关注LLVM插桩的实战方法，利用数据流边界技术提升模糊测试效率。
- 详情：[/20260527-20260625/README](/20260527-20260625/README)

### 精读区论文标签
- 本次无精读推荐。

### 速读区论文标签
1. [Control Flow Graph Recovery for Dynamically Loaded Code via Symbolic Library Resolution](/20260527-20260625/2605.29620v1-control-flow-graph-recovery-for-dynamically-loaded-code-via-symbolic-library-resolution)  
   标签：评分：10.0/10、query:sys-security
   evidence：通过符号库解析恢复二进制的控制流图
2. [Beyond Edge Coverage: Per-Task Data-Flow Extraction at Kernel Function Boundaries via LLVM](/20260527-20260625/2606.00455v1-beyond-edge-coverage-per-task-data-flow-extraction-at-kernel-function-boundaries-via-llvm)  
   标签：评分：10.0/10、query:sys-security
   evidence：通过LLVM插桩扩展内核模糊测试的数据流提取
3. [Formal Verification of Secure Encrypted Virtualization](/20260527-20260625/2606.01381v1-formal-verification-of-secure-encrypted-virtualization)  
   标签：评分：10.0/10、query:sys-security
   evidence：对AMD SEV进行形式化验证以确保机密计算安全
4. [DIST-FL: Enhancing Security for TEE-based Aggregation in Federated Learning](/20260527-20260625/2606.04899v2-dist-fl-enhancing-security-for-tee-based-aggregation-in-federated-learning)  
   标签：评分：10.0/10、query:sys-security
   evidence：提出基于TEE的分布式系统对抗回滚和I/O操纵攻击，改进TEE设计
5. [TeeDAO: A Decentralized Autonomous Organization for Heterogeneous TEEs](/20260527-20260625/2606.04912v1-teedao-a-decentralized-autonomous-organization-for-heterogeneous-tees)  
   标签：评分：10.0/10、query:sys-security
   evidence：TeeDAO框架组织多个异构TEE实例,提供统一接口,确保长期可用性、完整性和机密性
6. [Chimera: Protocol-Aware Recovery for Confidential BFT Consensus](/20260527-20260625/2606.09101v2-chimera-protocol-aware-recovery-for-confidential-bft-consensus)  
   标签：评分：10.0/10、query:sys-security
   evidence：为基于TEE的机密BFT共识设计协议感知恢复，直接推进TEE机密计算
7. [Two-Way Confidential VMs (2cVM): Collaborative Confidential Computing for Mutually Distrustful Parties](/20260527-20260625/2606.10615v1-two-way-confidential-vms-2cvm-collaborative-confidential-computing-for-mutually-distrustful-parties)  
   标签：评分：10.0/10、query:sys-security
   evidence：结合硬件TEE与负载内隔离的双层架构实现双向隔离
8. [Partitioned Tags, Shared Data: Reconciling Strict Cache Isolation with Write-Shared Coherence](/20260527-20260625/2606.12259v1-partitioned-tags-shared-data-reconciling-strict-cache-isolation-with-write-shared-coherence)  
   标签：评分：10.0/10、query:sys-security
   evidence：提出SCP,通过分离缓存标签实现严格驱逐隔离并支持写共享一致性
9. [Bifrost: Hybrid TEE-FHE Inference for Privacy-Preserving Transformer and LLM Serving](/20260527-20260625/2606.17421v1-bifrost-hybrid-tee-fhe-inference-for-privacy-preserving-transformer-and-llm-serving)  
   标签：评分：10.0/10、query:sys-security
   evidence：Bifrost将CPU TEE用于非线性算子,结合加速器全同态加密,定义混合TEE-FHE服务架构实现机密LLM推理
10. [OpenAnt: LLM-Powered Vulnerability Discovery Through Code Decomposition, Adversarial Verification, and Dynamic Testing](/20260527-20260625/2606.19149v2-openant-llm-powered-vulnerability-discovery-through-code-decomposition-adversarial-verification-and-dynamic-testing)  
   标签：评分：10.0/10、query:sys-security
   evidence：融合静态分析、LLM推理与动态测试的漏洞发现，推进检测技术
11. [FlexServe: A Fast and Secure LLM Serving System for Mobile Devices with Flexible Resource Isolation](/20260527-20260625/2606.23370v1-flexserve-a-fast-and-secure-llm-serving-system-for-mobile-devices-with-flexible-resource-isolation)  
   标签：评分：10.0/10、query:sys-security
   evidence：利用ARM TrustZone实现基于TEE的LLM推理保护，抵御操作系统内核攻击
12. [Automated Detection of Configuration-Specific Security Vulnerabilities via Patch Analysis](/20260527-20260625/2606.25863v1-automated-detection-of-configuration-specific-security-vulnerabilities-via-patch-analysis)  
   标签：评分：10.0/10、query:sys-security
   evidence：通过静态补丁分析检测Linux内核中配置特定的安全漏洞
13. [One (Thread) Can Keep a (PRNG) Secret, but not Two](/20260527-20260625/2606.00918v2-one-thread-can-keep-a-prng-secret-but-not-two)  
   标签：评分：9.0/10、query:sys-security
   evidence：利用XNU内核PRNG的竞态条件漏洞，预测IPv6分片ID，实施分片欺骗攻击
14. [Needles at Scale: LLM-Assisted Target Selection for Windows Vulnerability Research](/20260527-20260625/2606.01364v1-needles-at-scale-llm-assisted-target-selection-for-windows-vulnerability-research)  
   标签：评分：9.0/10、query:sys-security
   evidence：静态二进制分析管道，用于优先排序操作系统函数以进行漏洞研究。
15. [PyFEX: Uncovering Evasive Python-based Threats via Resilient and Exhaustive Path Exploration](/20260527-20260625/2606.02196v1-pyfex-uncovering-evasive-python-based-threats-via-resilient-and-exhaustive-path-exploration)  
   标签：评分：9.0/10、query:sys-security
   evidence：用于动态分析逃避型Python威胁的强制执行引擎。
16. [The Role of Domain-Specific Features in Malware Detection: A macOS Case Study](/20260527-20260625/2606.03218v1-the-role-of-domain-specific-features-in-malware-detection-a-macos-case-study)  
   标签：评分：9.0/10、query:sys-security
   evidence：基于领域特定特征的macOS二进制静态分析恶意软件检测
17. [PS-UIE: Privilege-Separated Integrity Enforcement for User-Space Executable Objects in Confidential VMs](/20260527-20260625/2606.04549v1-ps-uie-privilege-separated-integrity-enforcement-for-user-space-executable-objects-in-confidential-vms)  
   标签：评分：9.0/10、query:sys-security
   evidence：通过权限分离在机密虚拟机中对用户空间可执行对象实施完整性保护。
18. [DIST-FL: Enhancing Security for TEE-based Aggregation in Federated Learning](/20260527-20260625/2606.04899v1-dist-fl-enhancing-security-for-tee-based-aggregation-in-federated-learning)  
   标签：评分：9.0/10、query:sys-security
   evidence：利用TEE保障联邦学习聚合安全
19. [Policy-Compliant Cloud Storage Systems](/20260527-20260625/2606.05423v1-policy-compliant-cloud-storage-systems)  
   标签：评分：9.0/10、query:sys-security
   evidence：利用机密虚拟机实现可信中间件，为云键值存储强制执行GDPR合规，应用可信执行环境。
20. [AgileOS: A GPU Operating System Layer for Protected CUDA Services](/20260527-20260625/2606.06697v1-agileos-a-gpu-operating-system-layer-for-protected-cuda-services)  
   标签：评分：9.0/10、query:sys-security
   evidence：设计 GPU 操作系统层以提供受保护的 CUDA 服务，解决异构计算中的安全挑战
21. [Verifiable and Confidential DNN Inference on Low-End Edge Devices](/20260527-20260625/2606.07470v1-verifiable-and-confidential-dnn-inference-on-low-end-edge-devices)  
   标签：评分：9.0/10、query:sys-security
   evidence：利用TrustZone-M可信执行环境实现DNN推理的机密性与可验证性
22. [Chimera: Protocol-Aware Recovery for Confidential BFT Consensus](/20260527-20260625/2606.09101v1-chimera-protocol-aware-recovery-for-confidential-bft-consensus)  
   标签：评分：9.0/10、query:sys-security
   evidence：通过协议感知恢复应对基于TEE的BFT共识中的回滚攻击
23. [EnclaveScale: Hardware-Assisted Edge-DP for Secure Data Centre Power Telemetry](/20260527-20260625/2606.09163v1-enclavescale-hardware-assisted-edge-dp-for-secure-data-centre-power-telemetry)  
   标签：评分：9.0/10、query:sys-security
   evidence：使用DCAP远程证明和机密虚拟机(TEE)实现安全遥测，结合差分隐私
24. [Two-Way Confidential VMs (2cVM): Collaborative Confidential Computing for Mutually Distrustful Parties](/20260527-20260625/2606.10615v2-two-way-confidential-vms-2cvm-collaborative-confidential-computing-for-mutually-distrustful-parties)  
   标签：评分：9.0/10、query:sys-security
   evidence：基于硬件TEE和工作负载内隔离的双层架构实现机密计算
25. [Investigating Metamorphic Fuzz Oracle Enhancement via Large Language Models](/20260527-20260625/2606.14164v1-investigating-metamorphic-fuzz-oracle-enhancement-via-large-language-models)  
   标签：评分：9.0/10、query:sys-security
   evidence：提出 MetaFOE，利用 LLM 自动生成增变预言机以增强模糊测试，属于运行时动态分析技术
26. [FuseChain: Runtime Evidence Reconstruction for Software Supply-Chain Attacks](/20260527-20260625/2606.15811v1-fusechain-runtime-evidence-reconstruction-for-software-supply-chain-attacks)  
   标签：评分：9.0/10、query:sys-security
   evidence：使用溯源图谱的运行时检测框架，用于供应链攻击证据重建。
27. [obliv-clang: Real-World Oblivious Programming in C++](/20260527-20260625/2606.16187v1-obliv-clang-real-world-oblivious-programming-in-c)  
   标签：评分：9.0/10、query:sys-security
   evidence：obliv-clang是编译时静态检查C++程序遗忘性的工具,防止侧信道泄露
28. [MIPSBLEED: Uncovering Microarchitectural Timing Leaks in Pervasive Embedded Processors](/20260527-20260625/2606.16372v2-mipsbleed-uncovering-microarchitectural-timing-leaks-in-pervasive-embedded-processors)  
   标签：评分：9.0/10、query:sys-security
   evidence：通过汇编级探针和运行时实验揭示MIPS处理器的微架构时序泄露
29. [OTRO: Oblivious Tokenization Path with Square-Root ORAM](/20260527-20260625/2606.17358v1-otro-oblivious-tokenization-path-with-square-root-oram)  
   标签：评分：9.0/10、query:sys-security
   evidence：遗忘分词缓解CPU-GPU TEE中侧信道泄露
30. [OTRO: Oblivious Tokenization Path with Square-Root ORAM](/20260527-20260625/2606.17358v2-otro-oblivious-tokenization-path-with-square-root-oram)  
   标签：评分：9.0/10、query:sys-security
   evidence：解决 CPU-GPU 可信执行环境中 LLM 分词器的侧信道泄露问题，设计面向机密计算的 oblivious 分词路径
31. [Code-Augur: Agentic Vulnerability Detection via Specification Inference](/20260527-20260625/2606.18619v1-code-augur-agentic-vulnerability-detection-via-specification-inference)  
   标签：评分：9.0/10、query:sys-security
   evidence：基于规格推断的智能体漏洞检测直接推动软件漏洞发现
32. [OpenAnt: LLM-Powered Vulnerability Discovery Through Code Decomposition, Adversarial Verification, and Dynamic Testing](/20260527-20260625/2606.19149v1-openant-llm-powered-vulnerability-discovery-through-code-decomposition-adversarial-verification-and-dynamic-testing)  
   标签：评分：9.0/10、query:sys-security
   evidence：LLM驱动的漏洞发现，结合静态分析与动态测试
33. [Calibration Without Comprehension: Diagnosing the Limits of Fine-Tuning LLMs for Vulnerability Detection in Systems Software](/20260527-20260625/2606.20502v1-calibration-without-comprehension-diagnosing-the-limits-of-fine-tuning-llms-for-vulnerability-detection-in-systems-software)  
   标签：评分：9.0/10、query:sys-security
   evidence：基于大语言模型的Linux内核漏洞检测框架，包含诊断指标
34. ["What Happens Locally, Leaks Globally": Detecting Privacy Leakage Risks in MCP Servers](/20260527-20260625/2606.21338v1-what-happens-locally-leaks-globally-detecting-privacy-leakage-risks-in-mcp-servers)  
   标签：评分：9.0/10、query:sys-security
   evidence：静态分析MCP服务器中的隐私泄漏检测，防止未授权数据暴露
35. [Detecting and Understanding Vulnerabilities in Fully Homomorphic Encryption Frameworks](/20260527-20260625/2606.22519v1-detecting-and-understanding-vulnerabilities-in-fully-homomorphic-encryption-frameworks)  
   标签：评分：9.0/10、query:sys-security
   evidence：检测全同态加密框架中的逻辑缺陷以防止利用
36. [RAVEN: Agentic RAG for Automated Vulnerability Repair](/20260527-20260625/2606.22647v1-raven-agentic-rag-for-automated-vulnerability-repair)  
   标签：评分：9.0/10、query:sys-security
   evidence：代理式检索增强生成框架用于自动化漏洞修复
37. [What You See Is Not What You Execute: Memory-Based Runtime SBOM Generation for Supply Chain Security](/20260527-20260625/2606.22827v1-what-you-see-is-not-what-you-execute-memory-based-runtime-sbom-generation-for-supply-chain-security)  
   标签：评分：9.0/10、query:sys-security
   evidence：基于内存的运行时SBOM生成属于运行时动态分析技术
38. [BipBipCache: Pipeline-Aware Integration of Low-Latency Tweakable Encryption in an Embedded Cache Controller](/20260527-20260625/2606.23941v1-bipbipcache-pipeline-aware-integration-of-low-latency-tweakable-encryption-in-an-embedded-cache-controller)  
   标签：评分：9.0/10、query:sys-security
   evidence：BipBipCache将可调加密集成到缓存控制器中,通过加密保护数据和标签免受物理攻击,实现密码存储隔离
39. [SHIELDS: Automating OS Hardening with Iterative Multi-Agent Remediation](/20260527-20260625/2606.05476v1-shields-automating-os-hardening-with-iterative-multi-agent-remediation)  
   标签：评分：8.0/10、query:sys-security
   evidence：基于LLM多智能体反馈的自动化操作系统加固
40. [VIPIR: A Versatile GPU Framework for Integrating Private Information Retrieval Protocols](/20260527-20260625/2606.11536v1-vipir-a-versatile-gpu-framework-for-integrating-private-information-retrieval-protocols)  
   标签：评分：8.0/10、query:sys-security
   evidence：在异构系统中为私有信息检索协议提供GPU加速。
41. [DISARM: Target Electronic Device Informed Mitigation of Software Runtime Side-Channel Vulnerabilities](/20260527-20260625/2606.19807v1-disarm-target-electronic-device-informed-mitigation-of-software-runtime-side-channel-vulnerabilities)  
   标签：评分：8.0/10、query:sys-security
   evidence：结合硬件信息的运行时侧信道漏洞防御，可防止利用。
42. [FirmCure:Towards Autonomous and Adaptive Rehosting of Linux-Based Firmware](/20260527-20260625/2606.24549v1-firmcuretowards-autonomous-and-adaptive-rehosting-of-linux-based-firmware)  
   标签：评分：8.0/10、query:sys-security
   evidence：LLM驱动的全系统重托管框架，用于Linux固件，实现运行时安全分析


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
