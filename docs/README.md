<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-25
- 运行时间：2026-06-25 20:05:42 UTC
- 运行状态：成功
- 本次总论文数：23
- 精读区：12
- 速读区：11

### 今日简报（AI）
今日从23篇前沿研究中，重点精读2项满分突破：CHERI内存安全的高效对象标识与Blackwell GPU保密计算下的LLM服务性能恢复。
最值得关注的是CHERI-D在硬件层面以极低开销实现时序内存安全，以及串行化桥如何揭示并修复GPU可信执行环境中的大模型推理瓶颈。
建议深入这两篇系统设计，为安全硬件与AI推理栈的协同优化寻找落地灵感。
- 详情：[/202606/25/README](/202606/25/README)

### 精读区论文标签
1. [CHERI-D: Secure and efficient inline object ID for CHERI temporal memory safety](/202606/25/2606.19055v1-cheri-d-secure-and-efficient-inline-object-id-for-cheri-temporal-memory-safety)  
   标签：评分：10.0/10、query:sys-security
   evidence：CHERI体系结构扩展以实现高效时序内存安全
2. [The Serialized Bridge: Understanding and Recovering LLM Serving Performance under Blackwell GPU Confidential Computing](/202606/25/2606.23969v1-the-serialized-bridge-understanding-and-recovering-llm-serving-performance-under-blackwell-gpu-confidential-computing)  
   标签：评分：10.0/10、query:sys-security
   evidence：分析GPU机密计算下LLM服务吞吐量损失，确定VM-GPU桥为瓶颈，属于可信执行环境应用研究。
3. [OVIG: Optimistic Verification of AI Training Integrity via Gradient Signals](/202606/25/2606.21045v1-ovig-optimistic-verification-of-ai-training-integrity-via-gradient-signals)  
   标签：评分：9.0/10、query:sys-security
   evidence：验证异构加速器上的训练完整性以检测不可信提供者的恶意行为
4. [AgenticOS: An Intent-Oriented Secure Operating System Architecture for Autonomous AI Agents](/202606/25/2606.21129v1-agenticos-an-intent-oriented-secure-operating-system-architecture-for-autonomous-ai-agents)  
   标签：评分：9.0/10、query:sys-security
   evidence：提出意图导向的安全OS架构以防御代理入侵
5. [Guarded Equivalence Predicates for Scalable Formal Hardware Information-Flow Verification](/202606/25/2606.22063v1-guarded-equivalence-predicates-for-scalable-formal-hardware-information-flow-verification)  
   标签：评分：9.0/10、query:sys-security
   evidence：用于隔离的可扩展硬件信息流形式化验证
6. [2.5D Root of Trust: Securing the Chiplet Ecosystem](/202606/25/2606.22198v1-25d-root-of-trust-securing-the-chiplet-ecosystem)  
   标签：评分：9.0/10、query:sys-security
   evidence：针对异构2.5D芯片粒生态的安全策略，解决硬件木马和通信攻击
7. [Revelio: Cost-Efficient Agentic Memory Safety Vulnerability Detection For Repository-Scale Codebases](/202606/25/2606.22263v1-revelio-cost-efficient-agentic-memory-safety-vulnerability-detection-for-repository-scale-codebases)  
   标签：评分：9.0/10、query:sys-security
   evidence：基于智能体的内存安全漏洞检测框架，生成可执行漏洞证明
8. [Evidence-Bound Gateway-Path Provenance for Third-Party LLM Inference](/202606/25/2606.22560v1-evidence-bound-gateway-path-provenance-for-third-party-llm-inference)  
   标签：评分：9.0/10、query:sys-security
   evidence：引入基于TEE的测量网关运行时以实现可验证的LLM网关溯源
9. [From CVE to CWE: Syscall-Based HIDS Generalisation](/202606/25/2606.22581v1-from-cve-to-cwe-syscall-based-hids-generalisation)  
   标签：评分：9.0/10、query:sys-security
   evidence：基于系统调用序列的运行时主机入侵检测，实现跨CWE泛化，是一种动态分析防御。
10. [ColumnKeeper: Efficient Solutions to the ColumnDisturb Vulnerability in DRAM-based Systems](/202606/25/2606.22632v2-columnkeeper-efficient-solutions-to-the-columndisturb-vulnerability-in-dram-based-systems)  
   标签：评分：9.0/10、query:sys-security
   evidence：针对ColumnDisturb DRAM读干扰漏洞的缓解机制，保护内存隔离
11. [AutoPRAC: Automating Attack Discovery for PRAC-Based Rowhammer Defenses using Model Checkers](/202606/25/2606.23905v1-autoprac-automating-attack-discovery-for-prac-based-rowhammer-defenses-using-model-checkers)  
   标签：评分：9.0/10、query:sys-security
   evidence：使用模型检查自动化测试Rowhammer防御
12. [PowerFuzz: Power-Based Black-Box Firmware Fuzzing](/202606/25/2606.24692v1-powerfuzz-power-based-black-box-firmware-fuzzing)  
   标签：评分：9.0/10、query:sys-security
   evidence：利用功耗侧信道作为动态执行反馈，实现黑盒固件模糊测试以发现漏洞。

### 速读区论文标签
1. [Lifecycle-Aware Dynamic Analysis for Secure ML Model Execution](/202606/25/2606.19023v1-lifecycle-aware-dynamic-analysis-for-secure-ml-model-execution)  
   标签：评分：8.0/10、query:sys-security
   evidence：提出基于ML模型生命周期阶段的动态分析来检测恶意模型行为
2. [Compute-Budgeted Exploitability Evidence Graphs for Prospective Vulnerability Triage](/202606/25/2606.19076v1-compute-budgeted-exploitability-evidence-graphs-for-prospective-vulnerability-triage)  
   标签：评分：8.0/10、query:sys-security
   evidence：引入计算预算化的证据图用于前瞻性漏洞可利用性预测
3. [PUFFERDOS: Efficient and Effective Attack String Generation for Regular Expression Denial of Service Vulnerabilities](/202606/25/2606.19654v1-pufferdos-efficient-and-effective-attack-string-generation-for-regular-expression-denial-of-service-vulnerabilities)  
   标签：评分：8.0/10、query:sys-security
   evidence：提出针对ReDoS漏洞的攻击字符串生成方法，是一种软件漏洞检测技术
4. [Cross-Platform Software Birthmarking for Real-World Binaries via Intermediate Representation](/202606/25/2606.21988v1-cross-platform-software-birthmarking-for-real-world-binaries-via-intermediate-representation)  
   标签：评分：8.0/10、query:sys-security
   evidence：通过Ghidra P-code提出跨平台二进制胎记技术，用于软件剽窃检测，属于静态二进制安全分析应用。
5. [Representation Matters: An Empirical Study of Program Representations for LLM Vulnerability Reasoning](/202606/25/2606.25356v1-representation-matters-an-empirical-study-of-program-representations-for-llm-vulnerability-reasoning)  
   标签：评分：8.0/10、query:sys-security
   evidence：针对LLM漏洞推理的基于静态分析的程序表征实证研究
6. [A Predictive Neural Network Architecture for Early Detection of Low-Rate Cyberattacks](/202606/25/2606.18771v1-a-predictive-neural-network-architecture-for-early-detection-of-low-rate-cyberattacks)  
   标签：评分：7.0/10、query:sys-security
   evidence：动态分析QoS模式以早期检测LDoS攻击
7. [PYPILINE: Malicious PyPI Package Detection via Suspicious API Knowledge and Agent Workflow](/202606/25/2606.19063v2-pypiline-malicious-pypi-package-detection-via-suspicious-api-knowledge-and-agent-workflow)  
   标签：评分：7.0/10、query:sys-security
   evidence：利用静态与动态混合方法检测恶意PyPI包
8. [AutoTam: Specifying Secure Protocol Implementations with Tamarin Model Generation](/202606/25/2606.19937v1-autotam-specifying-secure-protocol-implementations-with-tamarin-model-generation)  
   标签：评分：7.0/10、query:sys-security
   evidence：使用Tamarin进行安全协议实现的形式化验证
9. [Agent-Assisted Side-Channel Attacks on Non-Prefix KV Cache in RAG](/202606/25/2606.21842v1-agent-assisted-side-channel-attacks-on-non-prefix-kv-cache-in-rag)  
   标签：评分：7.0/10、query:sys-security
   evidence：利用LLM服务中内存调度的侧信道攻击，涉及GPU异构系统安全
10. [PuDGhost: Experimental Analysis of Computation Result Corruption in Processing-using-DRAM Operations on Real DRAM Chips and Implications for Future Systems](/202606/25/2606.19119v1-pudghost-experimental-analysis-of-computation-result-corruption-in-processing-using-dram-operations-on-real-dram-chips-and-implications-for-future-systems)  
   标签：评分：6.0/10、query:sys-security
   evidence：分析DRAM内处理中的计算结果损坏现象，揭示一种新的干扰现象及其安全隐患
11. [Information flow security on persistent memory](/202606/25/2606.25422v1-information-flow-security-on-persistent-memory)  
   标签：评分：6.0/10、query:sys-security
   evidence：提出面向持久内存上汇编代码的信息流逻辑，可应用于二进制安全分析


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
