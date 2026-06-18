# Awesome Agentic AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources about Agentic AI: papers, frameworks, tools, use cases, and legal considerations

Agentic AI refers to AI systems that can autonomously plan, make decisions, and take actions to achieve goals. This list collects the best resources for understanding and building agentic systems.

## Contents

- [Papers](#papers)
  - [Foundational](#foundational)
  - [Agent Architectures](#agent-architectures)
  - [Multi-Agent Systems](#multi-agent-systems)
  - [Legal & Ethics](#legal--ethics)
- [Frameworks & Tools](#frameworks--tools)
  - [Agent Frameworks](#agent-frameworks)
  - [LLM Orchestration](#llm-orchestration)
  - [Development Tools](#development-tools)
- [Use Cases & Applications](#use-cases--applications)
  - [Enterprise](#enterprise)
  - [Research](#research)
  - [Healthcare](#healthcare)
  - [Legal Tech](#legal-tech)
- [Videos & Courses](#videos--courses)
  - [Tutorials](#tutorials)
  - [Conference Talks](#conference-talks)
  - [Online Courses](#online-courses)
- [Legal & Regulatory](#legal--regulatory)
  - [EU Regulations](#eu-regulations)
  - [Liability & Accountability](#liability--accountability)
  - [Data Protection](#data-protection)
  - [Guidelines & Standards](#guidelines--standards)
- [Communities & Resources](#communities--resources)

## Papers

### Foundational

- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) - Yao et al., 2022
- [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) - Shinn et al., 2023
- [Cognitive Architectures for Language Agents](https://arxiv.org/abs/2309.02427) - Sumers et al., 2023
- [The Rise and Potential of Large Language Model Based Agents](https://arxiv.org/abs/2309.07864) - Xi et al., 2023
- [A Survey on Large Language Model based Autonomous Agents](https://arxiv.org/abs/2308.11432) - Wang et al., 2023
- [Language Models as Agent Models](https://arxiv.org/abs/2212.01681) - Andreas, 2022
- [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601) - Yao et al., 2023
- [Foundation Models for Decision Making](https://arxiv.org/abs/2303.04129) - Yang et al., 2023

### Agent Architectures

- [AutoGPT: An Autonomous GPT-4 Experiment](https://github.com/Significant-Gravitas/AutoGPT)
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) - Park et al., 2023
- [ToolFormer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) - Schick et al., 2023
- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903) - Wei et al., 2022
- [MRKL Systems: A modular, neuro-symbolic architecture](https://arxiv.org/abs/2205.00445) - Karpas et al., 2022
- [HuggingGPT: Solving AI Tasks with ChatGPT and Hugging Face](https://arxiv.org/abs/2303.17580) - Shen et al., 2023
- [Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/abs/2303.17651) - Madaan et al., 2023
- [Graph of Thoughts: Solving Elaborate Problems with LLMs](https://arxiv.org/abs/2308.09687) - Besta et al., 2023
- [Agents: An Open-source Framework for Autonomous LLM Agents](https://arxiv.org/abs/2309.07870) - Zhou et al., 2023

### Multi-Agent Systems

- [Communicative Agents for Software Development](https://arxiv.org/abs/2307.07924) - Qian et al., 2023
- [MetaGPT: Meta Programming for Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352) - Hong et al., 2023
- [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155) - Wu et al., 2023
- [Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents](https://arxiv.org/abs/2306.03314) - Chen et al., 2023
- [Examining Inter-Consistency of Large Language Models Collaboration](https://arxiv.org/abs/2305.11595) - Talebirad & Nadiri, 2023
- [AgentVerse: Facilitating Multi-Agent Collaboration](https://arxiv.org/abs/2308.10848) - Chen et al., 2023
- [Dynamic LLM-Agent Network](https://arxiv.org/abs/2310.02170) - Wang et al., 2023

### Legal & Ethics

- [Legal Liability for Autonomous AI Agents](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4556327) - Discussion on legal frameworks
- [Accountability in AI: From Principles to Practice](https://arxiv.org/abs/2103.00091) - Raji et al., 2021
- [AI Agents and Legal Personhood](https://ieeexplore.ieee.org/document/9426845) - Discussing legal status of AI agents
- [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?](https://dl.acm.org/doi/10.1145/3442188.3445922) - Bender et al., 2021
- [Ethical and Social Risks of Harm from Language Models](https://arxiv.org/abs/2112.04359) - Weidinger et al., 2021
- [Toward Trustworthy AI Development: Mechanisms for Supporting Verifiable Claims](https://arxiv.org/abs/2004.07213) - Brundage et al., 2020
- [AI Deception: A Survey of Examples, Risks, and Potential Solutions](https://arxiv.org/abs/2308.14752) - Park et al., 2023
- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073) - Bai et al., 2022

## Frameworks & Tools

### Agent Frameworks

- [LangChain](https://github.com/langchain-ai/langchain) - Framework for developing applications powered by language models with agent capabilities
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's framework for building multi-agent AI systems
- [CrewAI](https://github.com/joaomdmoura/crewAI) - Framework for orchestrating role-playing, autonomous AI agents
- [LlamaIndex Agents](https://github.com/run-llama/llama_index) - Data framework with agent capabilities
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for integrating LLMs with conventional programming
- [Haystack](https://github.com/deepset-ai/haystack) - Framework for building NLP applications with agent pipelines
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Autonomous AI agents in your browser
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - AI-powered task management system
- [Langroid](https://github.com/langroid/langroid) - Python framework for building LLM applications with multi-agent capabilities
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - Framework for building, managing and running autonomous AI agents
- [AI Legion](https://github.com/eumemic/ai-legion) - Platform for building and orchestrating multi-agent systems
- [OpenAgents](https://github.com/xlang-ai/OpenAgents) - Open platform for using and hosting language agents
- [Agents](https://github.com/aiwaves-cn/agents) - Library for building multi-agent systems with language models
- [PydanticAI](https://github.com/pydantic/pydantic-ai) - Agent framework built on Pydantic for type-safe agent development
- [Swarm](https://github.com/openai/swarm) - Educational framework exploring ergonomic, lightweight multi-agent orchestration
- [Agency Swarm](https://github.com/VRSEN/agency-swarm) - Framework for creating AI agent swarms that collaborate on tasks

### LLM Orchestration

- [LangGraph](https://github.com/langchain-ai/langgraph) - Library for building stateful, multi-actor applications with LLMs
- [Promptflow](https://github.com/microsoft/promptflow) - Microsoft's tool for orchestrating LLM workflows
- [DSPy](https://github.com/stanfordnlp/dspy) - Framework for algorithmically optimizing LM prompts and weights
- [Flowise](https://github.com/FlowiseAI/Flowise) - Drag & drop UI to build customized LLM flows
- [LangFlow](https://github.com/logspace-ai/langflow) - UI for LangChain with drag-and-drop components
- [Chain Forge](https://github.com/ianarawjo/ChainForge) - Visual programming environment for prompt engineering

### Development Tools

- [AgentOps](https://github.com/AgentOps-AI/agentops) - Observability and dev tools for AI agents
- [LangSmith](https://www.langchain.com/langsmith) - Platform for debugging, testing, and monitoring LLM applications
- [Weights & Biases Prompts](https://wandb.ai/site/prompts) - Tools for tracking and versioning prompts
- [Phoenix](https://github.com/Arize-ai/phoenix) - ML observability for LLMs, agents, and RAG systems
- [Langfuse](https://github.com/langfuse/langfuse) - Open source LLM engineering platform for debugging, analytics, and monitoring
- [PromptLayer](https://promptlayer.com/) - Platform for prompt engineering and LLM observability
- [Helicone](https://github.com/Helicone/helicone) - Open-source observability platform for LLMs
- [LangWatch](https://langwatch.ai/) - Analytics and monitoring for LLM applications
- [Future AGI](https://github.com/future-agi/future-agi) - Open-source platform for agent simulation, evaluating, tracing, guarding, and auto-improving AI agents.
## Use Cases & Applications

### Enterprise

- **Customer Support Agents** - Autonomous systems for handling customer inquiries
- **Data Analysis Assistants** - Agents that can query, analyze, and visualize data
- **Code Generation & Review** - AI agents for software development assistance
- **Content Creation Pipelines** - Multi-agent systems for content generation and editing

### Research

- **Scientific Literature Review** - Agents that can search, summarize, and synthesize research papers
- **Hypothesis Generation** - AI systems for suggesting research directions
- **Experiment Design** - Agents that help design and plan experiments

### Healthcare

- **Clinical Decision Support** - Agents assisting with diagnosis and treatment planning
- **Medical Documentation** - Automated clinical note generation and summarization
- **Patient Triage** - AI agents for initial patient assessment

### Legal Tech

- **Contract Analysis** - Agents for reviewing and analyzing legal documents
- **Legal Research** - Automated case law and statute research
- **Due Diligence** - AI-powered document review for M&A
- **Compliance Monitoring** - Agents for regulatory compliance checking

## Videos & Courses

### Tutorials

- [LangChain Agents - Official Tutorial](https://python.langchain.com/docs/modules/agents/) - Comprehensive guide to building agents
- [AutoGPT Tutorial for Beginners](https://www.youtube.com/watch?v=jn8n212l3PQ) - Getting started with autonomous agents
- [Building AI Agents with LangGraph](https://www.youtube.com/watch?v=o-NYlFC7FlI) - Step-by-step tutorial on stateful agents
- [Multi-Agent Systems with AutoGen](https://www.youtube.com/watch?v=RLwyXRVvlNk) - Microsoft's framework explained
- [CrewAI Tutorial - Building Agent Teams](https://www.youtube.com/watch?v=tnejrr-0a94) - Creating collaborative AI agents

### Conference Talks

- [Andrew Ng - Agentic AI Design Patterns](https://www.youtube.com/watch?v=sal78ACtGTc) - Overview of key agent patterns
- [Shunyu Yao - ReAct: Synergizing Reasoning and Acting](https://www.youtube.com/watch?v=5fKT2qxRVAo) - Original ReAct paper presentation
- [Building with LLM Agents - Harrison Chase](https://www.youtube.com/watch?v=DWUdGhRrv2c) - LangChain creator on agent development
- [The Future of Programming and AI Agents - Stanford Seminar](https://www.youtube.com/watch?v=4ZYJvFNRWeY) - Academic perspective
- [Multi-Agent Systems for Complex Problem Solving](https://www.youtube.com/watch?v=aV3HqA_5KXE) - Research overview

### Online Courses

- [DeepLearning.AI - AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)
- [DeepLearning.AI - Multi AI Agent Systems with CrewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)
- [Building Autonomous Agents - Stanford CS224N](https://web.stanford.edu/class/cs224n/)

## Legal & Regulatory

### EU Regulations

- [EU AI Act](https://artificialintelligenceact.eu/) - Comprehensive regulation on AI systems including autonomous agents
- [GDPR Compliance for AI Agents](https://gdpr.eu/) - Data protection considerations for AI systems
- [EU Digital Services Act](https://digital-strategy.ec.europa.eu/en/policies/digital-services-act-package) - Regulations affecting AI-powered services

### Liability & Accountability

- **Product Liability** - Who is responsible when an AI agent causes harm?
- **Professional Liability** - Liability for AI agents providing professional services (legal, medical, financial advice)
- **Contract Law** - Can AI agents form binding contracts?
- **Tort Liability** - Civil liability for damages caused by autonomous agents

#### Key Resources

- [OECD AI Principles](https://oecd.ai/en/ai-principles) - International standards for AI development
- [IEEE Ethically Aligned Design](https://standards.ieee.org/industry-connections/ec/autonomous-systems/) - Ethics guidelines for autonomous systems
- [Partnership on AI](https://partnershiponai.org/) - Multi-stakeholder organization addressing AI challenges

### Data Protection

- **Data Minimization** - Principles for agent data collection
- **Right to Explanation** - GDPR requirements for automated decision-making
- **Data Retention** - Policies for agent memory and data storage
- **Cross-border Data Transfers** - Regulations affecting multi-jurisdictional AI agents

### Guidelines & Standards

- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) - US standards for AI risk management
- [ISO/IEC 42001:2023](https://www.iso.org/standard/81230.html) - AI management system standard
- [IEEE 7000 Series](https://standards.ieee.org/industry-connections/ec/autonomous-systems/) - Standards for autonomous and intelligent systems

## Communities & Resources

- [r/AI_Agents](https://www.reddit.com/r/AI_Agents/) - Reddit community for AI agents
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) - Community for running LLMs and agents locally
- [LangChain Discord](https://discord.gg/langchain) - Active community for LangChain developers
- [AI Alignment Forum](https://www.alignmentforum.org/) - Discussions on AI safety and alignment
- [Hugging Face Agents](https://huggingface.co/docs/transformers/transformers_agents) - Community and documentation
- [AutoGPT Discord](https://discord.gg/autogpt) - Community for AutoGPT developers
- [LlamaIndex Discord](https://discord.gg/dGcwcsnxhU) - Community for LlamaIndex and agent development
- [AI Agents Hub](https://www.aiagentshub.com/) - News and resources about AI agents

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE) for details.
