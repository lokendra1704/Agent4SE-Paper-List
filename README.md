# Agent4SE Paper List

<p>
<a href="http://arxiv.org/pdf/2409.02977"><img src='https://img.shields.io/badge/ArXiv-Paper-purple'/></a> 
</p>
The recent advance in Large Language Models (LLMs) has shaped a new paradigm of AI agents, i.e., LLM-based agents. Compared to standalone LLMs, LLM-based agents substantially extend the versatility and expertise of LLMs by enhancing LLMs with the capabilities of perceiving and utilizing external resources and tools. To date, LLM-based agents have been applied and shown remarkable effectiveness in Software Engineering (SE). The synergy between multiple agents and human interaction brings further promise in tackling complex real-world SE problems. In this work, we present a comprehensive and systematic survey on LLM-based agents for SE. We collect 106 papers and categorize them from two perspectives, i.e., the SE and agent perspectives. In addition, we discuss open challenges and future directions in this critical domain.

:round_pushpin: **We systematically summarized the progress of Agent4SE from the perspectives of both *Software Engineering* tasks and *Agent Architecture*.**

:page_facing_up: Paper Link: [Large Language Model-Based Agents for Software Engineering: A Survey](http://arxiv.org/pdf/2409.02977)

<br/>



## :newspaper: News

* **[2024/09/04]**  We released the first version of our survey on arXiv.

<br/>

## 🏎️Coming Soon

⬜ Complete the list of all papers from Agent Perspectives.

⬜ Provide an Interactive table.

<br/>


## Table of Contents

* 🖥️ [SE Perspectives](#%EF%B8%8F-se-perspectives)
  * [Requirement Engineering](#requirement-engineering)
  * [Code Generation](#code-generation)
  * [Static Code Checking](#static-checking)
    * [Static Bug Detection](#static-bug-detection)
    * [Code Review](#code-review)
  * [Testing](#testing)
    * [Unit Testing](#unit-testing)
    * [System Testing](#system-testing)
  * [Debugging](#debugging)
    * [Fault Localization](#fault-localization)
    * [Program Repair](#program-repair)
    * [Unified Debugging](#unified-debugging)
  * [End-to-end Software Development](#end-to-end-software-development)
  * [End-to-end Software Maintenance](#end-to-end-software-maintenance)
* 🤖[Agent Perspectives](#-agent-perspectives)
  * [Agent Framework](#agent-framework)
    * [Planning](#planning)
    * [Memory](#memory)
    * [Perception](#perception)
    * [Action](#action)
  * [Multi-agent System](#multi-agent-system)
  * [Human-Agent Collaboration](#human-agent-collaboration)
* 📝 [Citation](#-citation)
* 👨🏻‍💻 [Maintainers](#-maintainers)
* 📬 [Contact Us](#-contact-us)
* 🌟 [Star History](#-star-history)

<br/>

## 🖥️ SE Perspectives

### Requirement Engineering

* [2024/05] **MARE: Multi-Agents Collaboration Framework for Requirements Engineering.** *Jin et al. arXiv.* [[paper](https://arxiv.org/pdf/2405.03256)]
* [2024/04] **Elicitron: An LLM Agent-Based Simulation Framework for Design Requirements Elicitation.** *Ataei et al. arXiv.* [[paper](https://arxiv.org/pdf/2404.16045)]
* [2024/01] **SpecGen: Automated Generation of Formal
Program Specifications via Large Language Models.** *Ma et al. arXiv.* [[paper](https://arxiv.org/pdf/2401.08807)]
* [2023/10] **Advancing Requirements Engineering through Generative AI: Assessing the Role of LLMs.** *Arora et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.13976)]

<br/>

### Code Generation

* [2024/05] **Class-Level Code Generation from Natural Language Using Iterative, Tool-Enhanced Reasoning over Repository.** *Deshpande et al. arXiv.* [[paper](https://arxiv.org/pdf/2405.01573)]
* [2024/05] **MapCoder: Multi-Agent Code Generation for Competitive Problem Solving.** *Islam et al. arXiv.* [[paper](https://arxiv.org/pdf/2405.11403)]
* [2024/05] **AutoCoder: Enhancing Code Large Language Model with AIEV-INSTRUCT.** *Lei et al. arXiv.* [[paper](https://arxiv.org/pdf/2405.14906)]
* [2024/04] **Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra Large-Scale Code Generation and Optimization.** *Ishibashi et al. arXiv.* [[paper](https://arxiv.org/pdf/2404.02183)]
* [2024/03] **CONLINE: Complex Code Generation and Refinement with Online Searching and Correctness Testing.** *He et al. arXiv.* [[paper](https://arxiv.org/pdf/2403.13583)]
* [2024/02] **Executable Code Actions Elicit Better LLM Agents.** *Wang et al. arXiv.* [[paper](https://arxiv.org/pdf/2402.01030)] 
* [2024/02] **More Agents Is All You Need.** *Li et al. arXiv.* [[paper](https://arxiv.org/pdf/2402.05120)]
* [2024/02] **Test-Driven Development for Code Generation.** *Mathews et al. arXiv.* [[paper](https://arxiv.org/pdf/2402.13521)]   
* [2024/02] **LDB: A Large Language Model Debugger via Verifying Runtime Execution Step by Step.** *Zhong et al. arXiv.* [[paper](https://arxiv.org/pdf/2402.16906)]
* [2024/01] **CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges.** *Zhang et al. arXiv.* [[paper](https://arxiv.org/pdf/2401.07339)]
* [2024/01] **Teaching Code LLMs to Use Autocompletion Tools in Repository-Level Code Generation.** *Wang et al. arXiv.* [[paper](https://arxiv.org/pdf/2401.06391)]
* [2024/01] **Code Generation with AlphaCodium: From Prompt Engineering to Flow Engineering.** *Ridnik et al. arXiv.* [[paper](https://arxiv.org/pdf/2401.08500)]
* [2023/12] **AgentCoder: Multi-Agent-based Code Generation with Iterative Testing and Optimisation.** *Huang et al. arXiv.* [[paper](https://arxiv.org/pdf/2312.13010)]
* [2023/12] **LLM4TDD: Best Practices for Test Driven Development Using Large Language Models.** *Piya et al. arXiv.* [[paper](https://arxiv.org/pdf/2312.04687)]
* [2023/11] **INTERVENOR: Prompting the Coding Ability of Large Language Models with the Interactive Chain of Repair.** *Wang et al. arXiv.* [[paper](https://arxiv.org/pdf/2311.09868)]
* [2023/10] **Dynamic LLM-Agent Network: An LLM-agent Collaboration Framework with Agent Team Optimization.** *Liu et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.02170)]
* [2023/10] **Lemur: Harmonizing Natural Language and Code for Language Agents.** *Xu et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.06830)]
* [2023/10] **ClarifyGPT: Empowering LLM-based Code Generation with Intention Clarification.** *Mu et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.10996)]
* [2023/10] **CODECHAIN: TOWARDS MODULAR CODE GENERATION THROUGH CHAIN OF SELF-REVISIONS WITH REPRESENTATIVE SUB-MODULES.** *Le et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.08992)]
* [2023/10] **Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models.** *Zhou et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.04406v3)]
* [2023/09] **MINT: EVALUATING LLMS IN MULTI-TURN INTERACTION WITH TOOLS AND LANGUAGE FEEDBACK.** *Wang et al. arXiv.* [[paper](https://arxiv.org/pdf/2309.10691)]
* [2023/09] **Test-Case-Driven Programming Understanding in Large Language Models for Better Code Generation.** *Tian et al. arXiv.* [[paper](https://arxiv.org/pdf/2309.16120)]
* [2023/09] **CodePlan: Repository-level Coding using LLMs and Planning.** *Bairi et al. arXiv.* [[paper](https://arxiv.org/pdf/2309.12499)]
* [2023/09] **From Misuse to Mastery: Enhancing Code Generation with Knowledge-Driven AI Chaining.** *Ren et al. arXiv.* [[paper](https://arxiv.org/pdf/2309.15606)]
* [2023/09] **Parsel🐍: Algorithmic Reasoning with Language Models by Composing Decompositions.** *Zelikman et al. arXiv.* [[paper](https://openreview.net/pdf?id=qd9qcbVAwQ)]
* [2023/08] **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation.** *Wu et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.08155)]
* [2023/08] **Gentopia: A Collaborative Platform for Tool-Augmented LLMs.** *Xu et al. arXiv.* [[paper](https://arxiv.org/abs/2308.04030)]
* [2023/08] **Flows: Building Blocks of Reasoning and Collaborating AI.** *Josifoski et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.01285)]
* [2023/08] **CodeCoT: Tackling Code Syntax Errors in CoT Reasoning for Code Generation.** *Huang et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.08784)]
* [2023/06] **SELFEVOLVE: A Code Evolution Framework via Large Language Models.** *Jiang et al. arXiv.* [[paper](https://arxiv.org/pdf/2306.02907)]
* [2023/06] **InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback.** *Yang et al. arXiv.* [[paper](https://arxiv.org/pdf/2306.14898)]
* [2023/06] **IS SELF-REPAIR A SILVER BULLET FOR CODE GENERATION?.** *Olausson et al. arXiv.* [[paper](https://arxiv.org/pdf/2306.09896)]
* [2023/05] **ToolCoder: Teach Code Generation Models to use API search tools.** *Zhang et al. arXiv.* [[paper](https://arxiv.org/pdf/2305.04032)]
* [2023/04] **Teaching Large Language Models to Self-Debug.** *Chen et al. arXiv.* [[paper](https://arxiv.org/pdf/2304.05128)]     
* [2023/04] **Fully Autonomous Programming with Large Language Models.** *Liventsev et al. arXiv.* [[paper](https://dl.acm.org/doi/pdf/10.1145/3583131.3590481)]
* [2023/03] **CAMEL: Communicative Agents for “Mind” Exploration of Large Language Model Society.** *Li et al. arXiv.* [[paper](https://arxiv.org/pdf/2303.17760)]
* [2023/03] **Reflexion: Language Agents with Verbal Reinforcement Learning.** *Shinn et al. arXiv.* [[paper](https://arxiv.org/pdf/2303.11366)]
* [2023/03] **SELF-REFINE: Iterative Refinement with Self-Feedback.** *Madaan et al. arXiv.* [[paper](https://arxiv.org/pdf/2303.17651)]

<br/>

### Static Code Checking

#### Static Bug Detection

* [2024/05] **LLM-Assisted Static Analysis for Detecting Security Vulnerabilities.** *Li et al. arXiv.* [[paper](https://arxiv.org/pdf/2405.17238)]
* [2024/03] **Multi-role Consensus through LLMs Discussions for Vulnerability Detection.** *Mao et al. arXiv.* [[paper](https://arxiv.org/pdf/2403.14274)]
* [2024/01] **LLM4Vuln: A Unified Evaluation Framework for Decoupling and Enhancing LLMs' Vulnerability Reasoning.** *Sun et al. arXiv.* [[paper](https://arxiv.org/pdf/2401.16185)]
* [2023/12] **E&V: Prompting Large Language Models to Perform Static Analysis by Pseudo-code Execution and Verification.** *Hao et al. arXiv.* [[paper](https://arxiv.org/pdf/2312.08477)]
* [2023/10] **Large Language Model-Powered Smart Contract Vulnerability Detection: New Perspectives.** *Hu et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.01152)]
* [2023/10] **Static Code Analysis in the AI Era: An In-depth Exploration of the Concept, Function, and Potential of Intelligent Code Analysis.** *Fan et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.08837)]
* [2023/08] **The Hitchhiker's Guide to Program Analysis: A Journey with Large Language Models.** *Li et al. arXiv.* [[paper](https://arxiv.org/abs/2308.00245)]
* [2023/03] **ART: Automatic multi-step reasoning and tool-use for large language models.** *Paranjape et al. arXiv.* [[paper](https://arxiv.org/pdf/2303.09014)]

#### Code Review

* [2024/04] **AI-powered Code Review with LLMs: Early Results.** *Rasheed et al. arXiv.* [[paper](https://arxiv.org/pdf/2404.18496)]
* [2024/02] **CodeAgent: Collaborative Agents for Software Engineering.** *Tang et al. arXiv.* [[paper](https://arxiv.org/pdf/2402.02172.pdf)]
* [2023/10] **Static Code Analysis in the AI Era: An In-depth Exploration of the Concept, Function, and Potential of Intelligent Code Analysis.** *Fan et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.08837)]
* [2023/09] **CORE: Resolving Code Quality Issues using LLMs.** *Wadhwa et al. arXiv.* [[paper](https://arxiv.org/pdf/2309.12938)]

<br/>

### Testing

#### Unit Testing

* [2024/04] **Enhancing LLM-based Test Generation for Hard-to-Cover Branches via Program Analysis.** *Yang et al. arXiv.* [[paper](https://arxiv.org/pdf/2404.04966)]
* [2024/03] **COVERUP: Coverage-Guided LLM-Based Test Generation.** *Pizzorno et al. arXiv.* [[paper](https://arxiv.org/pdf/2403.16218)]
* [2023/08] **Effective Test Generation Using Pre-trained Large Language Models and Mutation Testing.** *Dakhel et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.16557)]
* [2023/05] **No More Manual Tests? Evaluating and Improving ChatGPT for Unit Test Generation.** *Yuan et al. arXiv.* [[paper](https://arxiv.org/pdf/2305.04207)]
* [2023/05] **ChatUniTest: A Framework for LLM-Based Test Generation.** *Chen et al. arXiv.* [[paper](https://arxiv.org/pdf/2305.04764)]
* [2023/02] **An Empirical Evaluation of Using Large Language Models for Automated Unit Test Generation.** *Schäfer et al. arXiv.* [[paper](https://arxiv.org/pdf/2302.06527)]

#### System Testing

* [2024/04] **LLM Agents can Autonomously Exploit One-day Vulnerabilities.** *Fang et al. arXiv.* [[paper](https://arxiv.org/pdf/2404.08144)]
* [2024/02] **You Can REST Now: Automated Specification Inference and Black-Box Testing of RESTful APIs with Large Language Models.** *Decrop et al. arXiv.* [[paper](https://arxiv.org/pdf/2402.05102)]
* [2024/01] **XUAT-Copilot: Multi-Agent Collaborative System for Automated User Acceptance Testing with Large Language Model.** *Wang et al. arXiv.* [[paper](https://arxiv.org/pdf/2401.02705)]
* [2024/01] **KernelGPT: Enhanced Kernel Fuzzing via Large Language Models.** *Yang et al. arXiv.* [[paper](https://arxiv.org/pdf/2401.00563)]
* [2023/11] **Autonomous Large Language Model Agents Enabling Intent-Driven Mobile GUI Testing.** *Yoon et al. arXiv.* [[paper](https://arxiv.org/pdf/2311.08649)]
* [2023/10] **Make LLM a Testing Expert: Bringing Human-like Interaction to Mobile GUI Testing via Functionality-aware Decisions.** *Liu et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.15780)]
* [2023/10] **AXNav: Replaying Accessibility Tests from Natural Language.** *Taeb et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.02424)]
* [2023/10] **White-box Compiler FuzzingEmpowered by Large Language Models.** *Yang et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.15991)]
* [2023/08] **PENTESTGPT: An LLM-empowered Automatic Penetration Testing Tool.** *Deng et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.06782)]
* [2023/08] **Fuzz4All: Universal Fuzzing with Large Language Models.** *Xia et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.04748)]
* [2023/07] **Isolating Compiler Bugs by Generating Effective Witness Programs with Large Language Models.** *Tu et al. arXiv.* [[paper](https://arxiv.org/pdf/2307.00593)]
* [2023/06] **Prompting Is All You Need: Automated Android Bug Replay with Large Language Models.** *Feng et al. arXiv.* [[paper](https://arxiv.org/pdf/2306.01987)]

<br/>

### Debugging

#### Fault Localization
* [2024/03] **AGENTFL: Scaling LLM-based Fault Localization to Project-Level Context.** *Qin et al. arXiv.* [[paper](https://arxiv.org/pdf/2403.16362)]
* [2023/10] **RCAgent: Cloud Root Cause Analysis by Autonomous Agents with Tool-Augmented Large Language Models.** *Wang et al. arXiv.* [[paper](https://arxiv.org/pdf/2310.16340)]
* [2023/08] **A Preliminary Evaluation of LLM-Based Fault Localization.** *Kang et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.05487)]

#### Program Repair
* [2024/04] **Flakiness Repair in the Era of Large Language Models.** *Chen et al. arXiv.* [[paper](https://dl.acm.org/doi/pdf/10.1145/3639478.3641227)]
* [2024/03] **RepairAgent: An Autonomous, LLM-Based Agent for Program Repair.** *Bouzenia et al. arXiv.* [[paper](https://arxiv.org/abs/2403.17134)]
* [2024/03] **ACFIX: Guiding LLMs with Mined Common
RBAC Practices for Context-Aware Repair of
Access Control Vulnerabilities in Smart Contracts.** *Zhang et al. arXiv.* [[paper](https://arxiv.org/pdf/2403.06838)]
* [2024/02] **CigaR: Cost-efficient Program Repair with LLMs.** *Hidvégi et al. arXiv.* [[paper](https://arxiv.org/pdf/2402.06598)]
* [2023/04] **Explainable Automated Debugging via Large Language Model-driven Scientific Debugging.** *Kang et al. arXiv.* [[paper](https://arxiv.org/pdf/2304.02195)]
* [2023/04] **Keep the Conversation Going: Fixing 162 out of 337 bugs for $0.42 each using ChatGPT.** *Xia et al. arXiv.* [[paper](https://arxiv.org/pdf/2304.00385)]
* [2023/01] **Conversational Automated Program Repair.** *Xia et al. arXiv.* [[paper](https://arxiv.org/pdf/2301.13246)]

#### Unified Debugging

* [2024/04] **A Unified Debugging Approach via LLM-Based Multi-Agent Synergy.** *Lee et al. arXiv.* [[paper](https://arxiv.org/pdf/2404.17153)]
* [2024/02] **LDB: A Large Language Model Debugger via Verifying Runtime Execution Step by Step.** *Zhong et al. arXiv.* [[paper](https://arxiv.org/pdf/2402.16906)]

<br/>

### End-to-end Software Development

* [2024/06] **Multi-Agent Software Development through Cross-Team Collaboration.** *Du et al. arXiv.* [[paper](https://arxiv.org/pdf/2406.08979)]
* [2024/06] **AgileCoder: Dynamic Collaborative Agents for Software Development based on Agile Methodology.** *Nguyen et al. arXiv.* [[paper](https://arxiv.org/pdf/2406.11912)]
* [2024/05] **Iterative Experience Refinement of Software-Developing Agents.** *Qian et al. arXiv.* [[paper](https://arxiv.org/pdf/2405.04219)]
* [2024/03] **When LLM-based Code Generation Meets the Software Development Process.** *Lin et al. arXiv.* [[paper](https://arxiv.org/pdf/2403.15852)]
* [2024/03] **CodeS: Natural Language to Code Repository via Multi-Layer Sketch.** *Zan et al. arXiv.* [[paper](https://arxiv.org/pdf/2403.16443)]
* [2024/02] **CodePori: Large Scale Model for Autonomous Software Development by Using Multi-Agents.** *Rasheed et al. arXiv.* [[paper](https://arxiv.org/pdf/2402.01411)]
* [2024/01] **Experimenting a New Programming Practice with LLMs.** *Zhang et al. arXiv.* [[paper](https://arxiv.org/pdf/2401.01062)]
* [2024/01] **LLM4PLC: Harnessing Large Language Models for Verifiable Programming of PLCs in Industrial Control Systems.** *Fakih et al. arXiv.* [[paper](https://arxiv.org/pdf/2401.05443)]
* [2023/12] **Experiential Co-Learning of Software-Developing Agents.** *Qian et al. arXiv.* [[paper](https://arxiv.org/pdf/2312.17025)]
* [2023/09] **AutoAgents: A Framework for Automatic Agent Generation.** *Chen et al. arXiv.* [[paper](https://arxiv.org/pdf/2309.17288)]
* [2023/08] **AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors.** *Chen et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.10848)]
* [2023/08] **METAGPT: META PROGRAMMING FOR A MULTI-AGENT COLLABORATIVE FRAMEWORK.** *Hong et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.00352)]
* [2023/07] **Communicative Agents for Software Development.** *Qian et al. arXiv.* [[paper](https://arxiv.org/pdf/2307.07924)]    
* [2023/06] **MULTI-AGENT COLLABORATION: HARNESSING THE POWER OF INTELLIGENT LLM AGENTS.** *Talebirad et al. arXiv.* [[paper](https://arxiv.org/pdf/2306.03314)]
* [2023/06] **Prompt Sapper: LLM-Empowered Software Engineering Infrastructure for AI-Native Services.** *Xing et al. arXiv.* [[paper](https://arxiv.org/pdf/2306.02230)]
* [2023/04] **Self-collaboration Code Generation via ChatGPT.** *Dong et al. arXiv.* [[paper](https://arxiv.org/pdf/2304.07590)]   
* [2023/04] **Low-code LLM: Visual Programming over LLMs.** *Cai et al. arXiv.* [[paper](https://arxiv.org/pdf/2304.08103v3)]

<br/>

### End-to-end Software Maintenance

* [2024/07] **Agentless: Demystifying LLM-based Software Engineering Agents.** *Xia et al. arXiv.* [[paper](https://arxiv.org/pdf/2407.01489)]
* [2024/06] **How to Understand Whole Software Repository?.** *Ma et al. arXiv.* [[paper](https://arxiv.org/pdf/2406.01422)]       
* [2024/06] **CODER: ISSUE RESOLVING WITH MULTI-AGENT AND
TASK GRAPHS.** *Chen et al. arXiv.* [[paper](https://arxiv.org/pdf/2406.01304)]
* [2024/06] **MASAI: Modular Architecture for Software-engineering AI Agents.** *Arora et al. arXiv.* [[paper](https://arxiv.org/abs/2406.11638)]
* [2024/05] **SWE-AGENT: AGENT-COMPUTER INTERFACES ENABLE AUTOMATED SOFTWARE ENGINEERING.** *Yang et al. arXiv.* [[paper](https://arxiv.org/pdf/2405.15793)]
* [2024/04] **AutoCodeRover: Autonomous Program Improvement.** *Zhang et al. arXiv.* [[paper](https://arxiv.org/pdf/2404.05427)]   
* [2024/03] **MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue ReSolution.** *Tao et al. arXiv.* [[paper](https://arxiv.org/pdf/2403.17927)]

<br/>

## 🤖 Agent Perspectives

To be completed soon.

<br/>


## 📝 Citation

```bibtex
@misc{Agent4SE,
      title={Large Language Model-Based Agents for Software Engineering: A Survey}, 
      author={Junwei Liu and Kaixin Wang and Yixuan Chen and Xin Peng and Zhenpeng Chen and Lingming Zhang and Yiling Lou},
      year={2024},
      eprint={2409.02977},
      archivePrefix={arXiv},
      primaryClass={cs.SE},
      url={https://arxiv.org/abs/2409.02977}, 
}
```

<br/>

## 👨🏻‍💻 Maintainers

- Junwei Liu @[To-D](https://github.com/To-D)
- Kaixin Wang @[wkx228](https://github.com/wkx228)
- Yixuan Chen @[FloridaSpidee](https://github.com/FloridaSpidee)

<br/>

## 📬 Contact Us

Feel free to ask any questions  or provide us with some suggestions via:

* Junwei Liu: jwliu24@m.fudan.edu.cn

<br/>

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=FudanSELab/Agent4SE-Paper-List&type=Date)](https://star-history.com/#FudanSELab/Agent4SE-Paper-List&Date)