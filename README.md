# Awesome AI4SE
Research papers and publications related to the development and evaluation of AI systems for software engineering

Criteria for inclusion:
1. The work is related to AI systems for software engineering (AI4SE). For this list, "AI" tends to mean language models (LMs).
2. The work is released as a research paper, preprint, or academic publication.
3. The work includes open source code and artifacts.

> [!NOTE]  
> The focus of this list more on research and academic contributions. Products and open source tools evaluated on SWE-bench are out of scope, but are welcome as submissions to the [SWE-bench leaderboard](https://github.com/swe-bench/experiments).

### 🧪 Evaluation
Benchmarks and tasks that evaluate AI systems on software engineering related tasks.

* [SWE-bench: Can Language Models Resolve Real-world Github Issues?](https://arxiv.org/abs/2310.06770) [[Code](https://github.com/SWE-bench/SWE-bench)]
* [SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?](https://arxiv.org/abs/2410.03859) [[Code](https://github.com/SWE-bench/SWE-bench)]
* [SWT-Bench: Testing and Validating Real-World Bug-Fixes with Code Agents](https://arxiv.org/abs/2406.12952) [[Code](https://github.com/logic-star-ai/swt-bench)]
* [Commit0: Library Generation from Scratch](https://arxiv.org/abs/2412.01769) [[Code](https://github.com/commit-0/commit0)]
* [Multi-SWE-bench: A Multilingual Benchmark for Issue Resolving](https://arxiv.org/abs/2504.02605) [[Code](https://github.com/multi-swe-bench/multi-swe-bench)]
* [SWE-bench Goes Live!](https://www.arxiv.org/abs/2505.23419) [[Code](https://github.com/SWE-bench-Live)]

### 🤖 Agent(-less)
Systems and inference scaffolds that enable AI systems to perform software engineering tasks, such as SWE-bench.

*SWE-agent's*
* [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793) [[Code](https://github.com/SWE-agent/SWE-agent)]
* [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/abs/2407.16741) [[Code](https://github.com/All-Hands-AI/OpenHands)]
* [SWE-Search: Enhancing Software Agents with Monte Carlo Tree Search and Iterative Refinement](https://arxiv.org/abs/2410.20285) [[Code](https://github.com/a-antoniades/swe-search)]
* [Diversity Empowers Intelligence: Integrating Expertise of Software Engineering Agents](https://arxiv.org/abs/2408.07060) [[Code](https://github.com/SalesforceAIResearch/swecomm)]
* [OrcaLoca: An LLM Agent Framework for Software Issue Localization](https://arxiv.org/abs/2502.00350) [[Code](https://github.com/fishmingyu/OrcaLoca)]

*Workflow Based*
* [Agentless: Demystifying LLM-based Software Engineering Agents](https://arxiv.org/abs/2407.01489) [[Code](https://github.com/OpenAutoCoder/Agentless?tab=readme-ov-file)]
* [AutoCodeRover: Autonomous Program Improvement](https://arxiv.org/abs/2404.05427) [[Code](https://github.com/AutoCodeRoverSG/auto-code-rover)]

### 🔨 Training
Datasets, techniques, and infrastructure to train better LMs and AI systems for software engineering.

*Datasets*
* [SWE-smith: Scaling Data for Software Engineering Agents](https://arxiv.org/abs/2504.21798) [[Code](https://github.com/SWE-bench/SWE-smith)]
* [Training Software Engineering Agents and Verifiers with SWE-Gym](https://arxiv.org/abs/2412.21139) [[Code](https://github.com/SWE-Gym/SWE-Gym)]
* [R2E-Gym: Procedural Environments and Hybrid Verifiers for Scaling Open-Weights SWE Agents](https://arxiv.org/abs/2504.07164) [[Code](https://github.com/R2E-Gym/R2E-Gym)]

*Training Techniques*
* [SWE-RL: Advancing LLM Reasoning via Reinforcement Learning on Open Software Evolution](https://arxiv.org/abs/2502.18449) [[Code](https://github.com/facebookresearch/swe-rl/)]
* [SWE-Fixer: Training Open-Source LLMs for Effective and Efficient GitHub Issue Resolution](https://arxiv.org/abs/2501.05040) [[Code](https://github.com/InternLM/SWE-Fixer)]

*Infrastructure*
* [SkyRL: A Modular Full-stack RL Library for LLMs](https://novasky-ai.notion.site/skyrl-v0) [[Code](https://github.com/NovaSky-AI/SkyRL)]