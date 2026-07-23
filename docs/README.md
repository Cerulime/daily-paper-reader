<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-23
- 运行时间：2026-07-23 21:46:29 UTC
- 运行状态：成功
- 本次总论文数：5
- 精读区：1
- 速读区：4

### 今日简报（AI）
今天扫描了 5 篇安全论文，核心发现来自共享存储页缓存的跨容器与虚拟机隔离失效攻击。  
最值得关注：共享存储泄露可绕过沙箱窃取敏感数据，以及模型扫描器被隐蔽的 Pickle 反序列化攻击绕过。  
建议普通读者优先理解第一类风险：即使容器/虚拟化隔离，共享文件缓存也可能暴露密码、密钥等内存残留。
- 详情：[/202607/23/README](/202607/23/README)

### 精读区论文标签
1. [Isolation Failure From Shared Storage: Characterizing and Exploiting Page-Cache SCA Leakage Across Containers and VMs](/202607/23/2607.17518v2-isolation-failure-from-shared-storage-characterizing-and-exploiting-page-cache-sca-leakage-across-containers-and-vms)  
   标签：评分：9.0/10、query:sys-security
   evidence：特征化并利用跨容器/虚拟机的页缓存侧信道，揭示共享存储中的隔离失效

### 速读区论文标签
1. [From Neural Intent to Cryptographic Authorization: Governing Agentic Workflows](/202607/23/2607.15596v1-from-neural-intent-to-cryptographic-authorization-governing-agentic-workflows)  
   标签：评分：6.0/10、query:sys-security
   evidence：神经符号密码授权防止LLM代理遭受提示注入劫持
2. [ShadowPickle: Evading Machine Learning Model Scanners via Stealthy Pickle Deserialization Attacks](/202607/23/2607.17503v1-shadowpickle-evading-machine-learning-model-scanners-via-stealthy-pickle-deserialization-attacks)  
   标签：评分：6.0/10、query:sys-security
   evidence：隐蔽的pickle反序列化攻击规避机器学习模型扫描器
3. [Trusted Credentials, Untrusted Behavior: Benchmarking LLM-Agent Security in High-Performance Computing](/202607/23/2607.18485v1-trusted-credentials-untrusted-behavior-benchmarking-llm-agent-security-in-high-performance-computing)  
   标签：评分：6.0/10、query:sys-security
   evidence：在高性能计算环境中，LLM代理被劫持的安全威胁
4. [Integrity of peer-to-peer distributed LLM inference under malicious nodes](/202607/23/2607.19490v1-integrity-of-peer-to-peer-distributed-llm-inference-under-malicious-nodes)  
   标签：评分：6.0/10、query:sys-security
   evidence：利用可信硬件在分布式LLM推理中检测恶意节点的完整性校验


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
