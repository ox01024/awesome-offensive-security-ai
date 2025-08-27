# 优秀的进攻性安全AI

精选的优秀进攻性安全AI工作、论文、组织、库和基准。

## 基准与评估

### CTFTiny (Shao et al.)

一个包含50个不同类别挑战的轻量级CTF基准。(提交日期: 2025年8月5日)

- [Towards Effective Offensive Security LLM Agents 论文](https://arxiv.org/abs/2508.05674)
- [CTFTiny (Shao et al.) GitHub](https://github.com/NYU-LLM-CTF/CTFTiny)

### 网络众包启发

通过众包启发评估AI网络能力。 (发布日期: 2025年7月8日)

- [网络众包启发博客文章](https://palisaderesearch.org/blog/cyber-crowdsourced-elicitation)

### CVE-Bench

CVE-Bench: 一个用于评估AI代理利用真实世界网络漏洞能力的基准。（提交日期：2025年3月17日）

- [CVE-Bench GitHub](https://github.com/uiuc-kang-lab/cve-bench)
- [CVE-Bench 论文](https://arxiv.org/abs/2503.17332)

### QHackBench

QHackBench: 使用 PennyLane Hackathon 挑战基准测试用于量子代码生成的大型语言模型。（提交日期：2025年6月24日）

- [QHackBench 论文](https://arxiv.org/abs/2506.20008)

### Bountybench

一个捕捉不断发展的真实世界系统中攻防网络能力的框架。（提交日期：2025年5月21日）

- [Bountybench 网站](https://bountybench.github.io/)
- [Bountybench GitHub](https://github.com/bountybench/bountybench)
- [Bountybench 论文](https://arxiv.org/abs/2505.15216)

### nyuctf_agents

nyuctf_agents: NYU CTF 基准的基线 LLM 代理。（最新发布：2025年2月6日）

- [nyuctf_agents GitHub](https://github.com/NYU-LLM-CTF/nyuctf_agents)
- [NYU_CTF_BenchMark](https://github.com/NYU-LLM-CTF/NYU_CTF_Bench)

### InterCode-CTF

InterCode-CTF: 一个用于评估 LLM 在夺旗挑战中表现的基准。（提交日期：2024年12月3日）

- [InterCode-CTF 博客文章](https://palisaderesearch.org/blog/intercode-ctf)
- [论文: Hacking CTFs with Plain Agents](https://arxiv.org/abs/2412.02776)
- [intercode GitHub](https://github.com/palisaderesearch/intercode)

### Cybench

Cybench: 一个评估语言模型网络安全能力和风险的框架。（提交日期：2024年8月15日）

- [Cybench 网站](https://cybench.github.io/)
- [Cybench GitHub](https://github.com/andyzorigin/cybench)
- [Cybench 论文](https://arxiv.org/abs/2408.08926)
- [ICLR 2025 大会议题](https://iclr.cc/virtual/2025/oral/31753)

### CYBERSECEVAL 3

CYBERSECEVAL 3: 推进大型语言模型网络安全风险和能力的评估。（提交日期：2024年8月）

- [CYBERSECEVAL 3 论文](https://arxiv.org/abs/2408.10627)

### CyberMetric

CyberMetric: 一个基于检索增强生成的基准数据集，用于评估LLM在网络安全知识方面的能力。（提交日期：2024年7月）

- [CyberMetric 论文](https://arxiv.org/abs/2407.08CyberMetric)
- [CyberMetric 数据集](https://huggingface.co/datasets/norbert-tihanyi/CyberMetric)

### SEvenLLM

SEvenLLM: 一个旨在引出和提高LLM在安全事件中进行网络安全事件分析和响应能力的基准。（提交日期：2024年5月）

- [SEvenLLM 论文](https://arxiv.org/abs/2405.18354)
- [SEvenLLM GitHub](https://github.com/7evenllm/SEvenLLM)

### CyberSecEval_2

CYBERSECEVAL 2: 一个广泛的网络安全评估套件，用于大型语言模型。（提交日期：2024年4月）

- [CyberSecEval 2 论文](https://arxiv.org/abs/2404.07920)
- [CyberSecEval 2 GitHub](https://github.com/meta-llama/cyberseceval)

### GDM Dangerous Capabilities

GDM Dangerous Capabilities: 夺旗挑战。（提交日期：2024年3月）

- [GDM Dangerous Capabilities 论文](https://arxiv.org/abs/2403.13793)
- [GDM Dangerous Capabilities GitHub](https://github.com/google-deepmind/evals/tree/main/dangerous_capabilities)

### LLM_CTF

LLM 解决进攻性安全挑战的实证评估。（提交日期：2024年2月19日）

- [LLM_CTF GitHub](https://github.com/NickNameInvalid/LLM_CTF)
- [LLM_CTF 论文](https://arxiv.org/abs/2402.11814)

### SecQA

SecQA: 一个简洁的问答数据集，用于评估大型语言模型在计算机安全方面的能力。（提交日期：2023年12月）

- [SecQA 论文](https://arxiv.org/abs/2312.07344)
- [SecQA 数据集](https://huggingface.co/datasets/secqa/secqa-v2)

## LLM 代理与框架

### Towards Effective Offensive Security LLM Agents (迈向高效的进攻性安全LLM代理)

迈向高效的进攻性安全LLM代理：超参数调整、LLM作为裁判以及轻量级CTF基准。(提交日期: 2025年8月5日)

- [Towards Effective Offensive Security LLM Agents 论文](https://arxiv.org/abs/2508.05674)
- [CTFTiny GitHub](https://github.com/NYU-LLM-CTF/CTFTiny)

### Incalmo

一个高级抽象层，允许LLM指定一般性动作，然后由专家代理将其转换为具体命令。(提交日期: 2025年1月28日)

- [关于使用LLM自主执行多主机攻击的可行性 论文](https://arxiv.org/abs/2501.16466)

#### CRAKEN

CRAKEN: 具有基于知识执行的网络安全 LLM 代理。（提交日期：2025年5月21日）

- [CRAKEN GitHub](https://github.com/NYU-LLM-CTF/nyuctf_agents_craken)
- [CRAKEN 论文](https://arxiv.org/abs/2505.17107)

### RedTeamLLM

RedTeamLLM: 一个用于进攻性安全的Agentic AI框架。（提交日期：2025年5月11日）

- [RedTeamLLM 论文](https://arxiv.org/abs/2505.06913)
- [RedTeamLLM GitHub](https://github.com/lre-security-systems-team/redteamllm)

### HackSynth-GRPO

HackSynth-GRPO: 一个利用引导式强化提示优化 (GRPO) 来增强 LLM 代理解决密码学 CTF 挑战的框架。（发布日期：2025年4月）

- [HackSynth-GRPO 论文](https://arxiv.org/html/2506.02048)
- [HackSynth-GRPO GitHub](https://github.com/aielte-research/HackSynth-GRPO)

### CAI

一个轻量级、符合人体工程学的框架，用于构建可用于漏洞赏金的AI网络安全（CAI）。（论文发布：2025年4月）

- [CAI 网站](https://aliasrobotics.github.io/cai/)
- [CAI GitHub](https://github.com/aliasrobotics/cai)

#### D-CIPHER

D-CIPHER: 进攻性安全的动态协作智能多代理系统。（提交日期：2025年2月15日）

- [D-CIPHER 论文](https://arxiv.org/abs/2502.10931)

### CTFTiny

CTFTINY: 用于大型语言模型网络攻击技能的轻量级基准测试。（提交日期：2025年2月11日）

- [CTFTiny GitHub](https://github.com/NYU-LLM-CTF/CTFTiny)

### PentestGPT

PentestGPT: 一个由 GPT 驱动的渗透测试工具。（发布日期：2024年8月12日）

- [PentestGPT GitHub](https://github.com/GreyDGL/PentestGPT)
- [PentestGPT 论文](https://www.usenix.org/conference/usenixsecurity24/presentation/deng)

### HackSynth

HackSynth: 用于自主渗透测试的 LLM 代理和评估框架。（提交日期：2024年12月2日）

- [HackSynth GitHub](https://github.com/aielte-research/HackSynth)
- [HackSynth 论文](https://arxiv.org/abs/2412.01778)

### EnIGMA

EnIGMA: 一种解决进攻性网络安全（夺旗）挑战的模式，在多个网络安全基准上取得了最先进的结果。（提交日期：2024年9月24日）

- [EnIGMA 网站](https://enigma-agent.com)
- [EnIGMA GitHub](https://github.com/SWE-agent)
- [EnIGMA 论文](https://arxiv.org/abs/2409.16165)
- [EnIGMA 基准](https://github.com/enigma-agent/benchmarks)

### XBOW(商业)

XBOW: 一个自主发现和利用潜在安全漏洞的系统。（首次提交：约10个月前）

- [XBOW 网站](https://xbow.com/)
- [XBOW 基准](https://github.com/xbow-engineering/validation-benchmarks)
- [XBOW 安全咨询致谢](https://github.com/advisories?query=credit%3Axbow-security)
- [AI Agents for OffSec with Zero False Positives (Black Hat 2025 幻灯片)](https://assets-global.website-files.com/658189b90f81ce5f1a7e6d63/66ac8e51655997008e75f733_XBOW%20-%20Black%20Hat%202025%20-%20AI%20Agents%20for%20Offsec%20with%20Zero%20False%20Positives.pdf)

### 从脚本到策略：Claude 4在进攻性安全中的高级方法

Pattern Labs和Anthropic对Claude 4在进攻性安全方面的能力进行的联合评估。(发布日期: 2025年8月20日)

- [从脚本到策略：Claude 4在进攻性安全中的高级方法 博客文章](https://patternlabs.co/blog/from-scripts-to-strategy-claude-4s-advanced-approach-to-offensive-security)



## 竞赛

### AI Cyber Challenge

AI Cyber Challenge: 一项旨在推进网络安全领域人工智能技术水平的竞赛。

- [AI Cyber Challenge 网站](https://aicyberchallenge.com/)

## LLM 安全研究与工具

### 教LLM如何XSS

教LLM如何XSS: 微调和强化学习的介绍（使用您自己的GPU）

- [幻灯片](https://docs.google.com/presentation/d/1feHRtOWdAKhZUQcfyzeDSgsx4Sn5QzqfgLFV1Tiskmo/edit)

### inspect_cyber

inspect_cyber: 由 UKGovernmentBEIS 开发的 Inspect 扩展，旨在用于代理网络评估。该项目旨在促进网络安全领域中 AI 代理的评估。

- [inspect_cyber 网站](https://inspect.cyber.aisi.org.uk/)
- [inspect_cyber GitHub](https://github.com/UKGovernmentBEIS/inspect_cyber)

## 如何贡献

欢迎贡献！如果您有适合此列表的项目、论文或资源，请随时提交拉取请求。请确保您的提交符合现有格式和类别。
