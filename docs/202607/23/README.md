# 日报 · 2026-07-23

- 生成时间：2026-07-23 21:46:29 UTC
- 当次推荐总数：5
- 精读区：1
- 速读区：4

## 今日简报（AI）
今日重点揭露了共享存储的缓存侧信道漏洞，同时扫描了AI代理授权、Pickle序列化攻击与高性能计算中的LLM安全风险。  
最值得关注的是《Isolation Failure》一文证明了页面缓存可被跨容器/虚拟机侧信道利用，直接动摇云隔离基础；另外《ShadowPickle》的隐蔽反序列化攻击也很值得警觉。  
建议安全团队尽快审视共享文件系统的访问隔离，并对AI模型的数据加载接口做反序列化风险加固。

## 精读区
1. [Isolation Failure From Shared Storage: Characterizing and Exploiting Page-Cache SCA Leakage Across Containers and VMs](/202607/23/2607.17518v2-isolation-failure-from-shared-storage-characterizing-and-exploiting-page-cache-sca-leakage-across-containers-and-vms) （9.0/10）

## 速读区
1. [From Neural Intent to Cryptographic Authorization: Governing Agentic Workflows](/202607/23/2607.15596v1-from-neural-intent-to-cryptographic-authorization-governing-agentic-workflows) （6.0/10）
2. [ShadowPickle: Evading Machine Learning Model Scanners via Stealthy Pickle Deserialization Attacks](/202607/23/2607.17503v1-shadowpickle-evading-machine-learning-model-scanners-via-stealthy-pickle-deserialization-attacks) （6.0/10）
3. [Trusted Credentials, Untrusted Behavior: Benchmarking LLM-Agent Security in High-Performance Computing](/202607/23/2607.18485v1-trusted-credentials-untrusted-behavior-benchmarking-llm-agent-security-in-high-performance-computing) （6.0/10）
4. [Integrity of peer-to-peer distributed LLM inference under malicious nodes](/202607/23/2607.19490v1-integrity-of-peer-to-peer-distributed-llm-inference-under-malicious-nodes) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
