# Awesome Large Language Model/Large Multi-modal Model -based Multi-Agents
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)  [![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/ysymyth/awesome-language-agents/pulls)

![cover](assets/cover.png)

A compilation of LLM powered multiagent papers or projects. 
BibTex citation if you find our work useful:
```bibtex
@misc{llmma2023,
  author = {Andrew Zhao},
  title = {Awesome LLM-based Multi-Agents},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{[https://github.com/charlespwd/project-title](https://github.com/Andrewzh112/Awesome-LLM-based-MultiAgents)}}
}
```
**We welcome any contributions, discussions or feedbacks via PRs, issues, emails.**

## Table of Content (ToC)
- [Awesome Large Language Model/Large Multi-modal Model -based Multi-Agents](#awesome-large-language-modellarge-multi-modal-model--based-multi-agents)
  - [News](#news)
  - [Background](#background)
    - [Multi-Agent Systems/Multi-Agent Reinforcement Learning (Books)](#multi-agent-systemsmulti-agent-reinforcement-learning-books)
  - [Cooperative](#cooperative)
  - [Competitive](#competitive)
  - [Mixed](#mixed)
  - [Benchmarks](#benchmarks)
  - [Taxonomy/Cognitive Architectures](#taxonomycognitive-architectures)
  - [Theory of Mind](#theory-of-mind)
  - [Social/Simulation/Role-play](#socialsimulationrole-play)
  - [Tool-use](#tool-use)
  - [Alignment](#alignment)
  - [LLM Evaluation](#llm-evaluation)
  - [Self-play](#self-play)
  - [Debating/Discussion](#debatingdiscussion)
  - [Applications](#applications)
    - [Computer Tasks](#computer-tasks)
    - [Recommender System](#recommender-system)
    - [Chatbots/Dialogues](#chatbotsdialogues)
    - [Robotics](#robotics)
    - [Autonomous Driving](#autonomous-driving)
    - [Others](#others)
  - [Open-source Projects](#open-source-projects)
  - [Contacts](#contacts)
  - [Other LLM-based Agent Repositories](#other-llm-based-agent-repositories)
  - [TODOs](#todos)
  - [Star History](#star-history)

## News
- 🎉 [2023/12/28] Publicly released repo.

## Background
### Multi-Agent Systems/Multi-Agent Reinforcement Learning (Books)
- [2023] **Multi-Agent Reinforcement Learning: Foundations and Modern Approaches** *Massachusetts Institute of Technology.* [[Book](https://www.marl-book.com/)]
- [2008] **Multiagent systems: Algorithmic, game-theoretic, and logical foundations** *Cambridge University Press* [[Book](http://www.masfoundations.org/mas.pdf)]

## Cooperative
- [2023/12] **LLM-Powered Hierarchical Language Agent for Real-time Human-AI Coordination** *Jijia Liu et al. arXiv* [[Paper](https://arxiv.org/pdf/2312.15224)] *
- [2023/11] **Building the Future of Responsible AI: A Reference Architecture for Designing Large Language Model Based Agents** *Qinghua Lu et al. arXiv* [[Paper](https://arxiv.org/abs/2311.13148)] *
- [2023/11] **Controlling Large Language Model-based Agents for Large-Scale Decision-Making: An Actor-Critic Approach** *Bin Zhang et al. arXiv* [[Paper](https://arxiv.org/abs/2311.13884)] *
- [2023/11] **StrategyLLM: Large Language Models as Strategy Generators, Executors, Optimizers, and Evaluators for Problem Solving** *Chang Gao et al. arXiv* [[Paper](https://arxiv.org/abs/2311.08803)] * (pipeline)
- [2023/11] **Towards A Natural Language Interface for Flexible Multi-Agent Task Assignment** *Jake Brawer et al. arXiv* [[Paper](https://arxiv.org/abs/2311.00153)] #
- [2023/10] **Conversational Swarm Intelligence, a Pilot Study** *Louis Rosenberg et al. arXiv* [[Paper](https://arxiv.org/abs/2309.03220)] * (swarm)
- [2023/10] **Efficient Human-AI Coordination via Preparatory Language-based Convention** *ICLR 2024 Conference Submission3413 Authors* [[Paper](https://openreview.net/forum?id=RofU5v2BvZ)] * (communication)
- [2023/10] **Ask more, know better: Reinforce-Learned Prompt Questions for Decision Making with Large Language Models** *ICLR 2024 Conference Submission7085 Authors* [[Paper](https://openreview.net/forum?id=5COCYDObes)] * (communication)
- [2023/10] **AXNav: Replaying Accessibility Tests from Natural Language** *Maryam Taeb et al. arXiv* [[Paper](https://arxiv.org/abs/2310.02424)] #
- [2023/10] **Towards End-to-End Embodied Decision Making via Multi-modal Large Language Model: Explorations with GPT4-Vision and Beyond** *Liang Chen (PKU) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.02071)|[Code](https://github.com/pkunlp-icler/PCA-EVAL)] #
- [2023/10] **Adapting LLM Agents Through Communication** *Kuan Wan (GaTech) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.01444)] * (communication)
- [2023/10] **Dynamic LLM-Agent Network: An LLM-agent Collaboration Framework with Agent Team Optimization** *Zijun Liu (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.02170)|[Code](https://github.com/SALT-NLP/DyLAN)] #
- [2023/10] **OKR-Agent: An Object and Key Results Driven Agent System with Hierarchical Self-Collaboration and Self-Evaluation** *ICLR 2024 Conference Submission3430 Authors* [[Paper](https://openreview.net/forum?id=Mngdhgi711)] #
- [2023/10] **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation** *Qingyun Wu (Microsoft) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.08155)|[Project Page](https://microsoft.github.io/autogen/)|[Code](https://github.com/microsoft/autogen)] *
- [2023/10] **MetaAgents: Simulating Interactions of Human Behaviors for LLM-based Task-oriented Coordination via Collaborative Generative Agents** *Yuan Li (Cambridge) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.06500)] *
- [2023/10] **Large Language Model (LLM) as a System of Multiple Expert Agents: An Approach to solve the Abstraction and Reasoning Corpus (ARC) Challenge** *John Tan Chong Min (NUS) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.05146)] #
- [2023/10] **Evaluating Multi-Agent Coordination Abilities in Large Language Models** *Saaket Agashe (UC Santa Cruz) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.03903)] #
- [2023/09] **Discuss Before Moving: Visual Language Navigation via Multi-expert Discussions** *Yuxing Long (PKU) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.11382)] #
- [2023/09] **AutoAgents: The Automatic Agent Generation Framework** *Guangyao Chen (PKU) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.17288)|[Project Page](https://linksoul-autoagents.hf.space/#)|[Code](https://github.com/LinkSoul-AI/AutoAgents)] *
- [2023/09] **Scalable Multi-Robot Collaboration with Large Language Models: Centralized or Decentralized Systems?** *Yongchao Chen (MIT) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.15943)] *
- [2023/08] **GPT-in-the-Loop: Adaptive Decision-Making for Multiagent Systems** *Nathalia Nascimento (Waterloo) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.10435)] *
- [2023/08] **CGMI: Configurable General Multi-Agent Interaction Framework** *Jinxin Shi et al. arXiv* [[Paper](https://arxiv.org/abs/2308.12503)] *
- [2023/08] **InterAct: Exploring the Potentials of ChatGPT as a Cooperative Agent** *Po-Lin Chen et al. arXiv* [[Paper](https://arxiv.org/abs/2308.01552)] *
- [2023/08] **ProAgent: Building Proactive Cooperative AI with Large Language Models** *Ceyao Zhang (The Chinese University of Hong Kong) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.11339)|[Project Page](https://pku-proagent.github.io/)|[Code](https://github.com/PKU-Alignment/ProAgent)] *
- [2023/08] **BOLAA: Benchmarking and Orchestrating LLM-augmented Autonomous Agents** *Zhiwei Liu (Salesforce) et al. arXiv.* [[Paper](https://arxiv.org/abs/2308.05960)|[Code](https://github.com/salesforce/BOLAA/tree/main)] *
- [2023/07] **Building Cooperative Embodied Agents Modularly with Large Language Models** *Hongxin Zhang (University of Massachusetts Amherst) et al. arXiv* [[Paper](https://arxiv.org/abs/2307.02485)|[Project Page](https://vis-www.cs.umass.edu/Co-LLM-Agents/)|[Code](https://github.com/UMass-Foundation-Model/Co-LLM-Agents/)] *
- [2023/06] **Emergent Cooperation and Strategy Adaptation in Multi-Agent Systems: An Extended Coevolutionary Theory with LLMs** *I. de Zarzà et al. arXiv* [[Paper](https://www.mdpi.com/2079-9292/12/12/2722)] *
- [2023/06] **Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents** *Yashar Talebirad (University of Alberta) et al. Advances in Theories and Applications of Multi-Agent Systems* [[Paper](https://arxiv.org/abs/2306.03314)] *
- [2023/05] **SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks** *Bill Yuchen Lin (Allen Institute) et al. NeuRIPS 2023* [[Paper](https://arxiv.org/abs/2305.17390)|[Code](https://github.com/yuchenlin/SwiftSage)] *
- [2023/04] **Improving Grounded Language Understanding in a Collaborative Environment by Interacting with Agents Through Help Feedback** *Nikhil Mehta (Purdue) et al. arXiv* [[Paper](https://arxiv.org/abs/2304.10750)] #
- [2023/03] **DERA: Enhancing Large Language Model Completions with Dialog-Enabled Resolving Agents** *Varun Nai et al. arXiv* [[Paper](https://arxiv.org/abs/2303.17071)] #

## Competitive
- [2023/11] **SELF GENERATED WARGAME AI: DOUBLE LAYER AGENT TASK PLANNING BASED ON LARGE LANGUAGE MODEL** *Yuxiang Sun et al. arXiv* [[Paper](https://arxiv.org/abs/2312.01090)] #
- [2023/10] **CompeteAI: Understanding the Competition Behaviors in Large Language Model-based Agents** *Qinlin Zhao et al. arXiv* [[Paper](https://arxiv.org/abs/2310.17512)] #
- [2023/10] **Large Language Models As Rational Players In Competitive Economics Games** *ICLR 2024 Conference Submission2817 Authors* [[Paper](https://openreview.net/forum?id=NMPLBbjYFq)] #
- [2023/10] **Put Your Money Where Your Mouth Is: Evaluating Strategic Planning and Execution of LLM Agents in an Auction Arena** *Jiangjie Chen (Fudan) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.05746)|[Project Page](https://auction-arena.github.io/)|[Code](https://github.com/jiangjiechen/auction-arena)] #
- [2023/10] **Large Language Models as Gaming Agents** *ICLR 2024 Conference Submission5875 Authors* [[Paper](https://openreview.net/forum?id=iS3fQooCaa)] #
- [2023/08] **Are ChatGPT and GPT-4 Good Poker Players? -- A Pre-Flop Analysis** *Akshat Gupta (UC Berkeley) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.12466)] #
- [2023/05] **Playing repeated games with Large Language Models** *Elif Akata (University of Tübingen) et al. arXiv* [[Paper](https://arxiv.org/abs/2305.16867)] #

## Mixed
- [2023/11] **Deciphering Digital Detectives: Understanding LLM Behaviors and Capabilities in Multi-Agent Mystery Games** *Dekun Wu (MILA) et al. arXiv* [[Paper](https://arxiv.org/abs/2312.00746)] #
- [2023/11] **MAgIC: Investigation of Large Language Model Powered Multi-Agent in Cognition, Adaptability, Rationality and Collaboration** *Lin Xu (NUS) et al. arXiv* [[Paper](https://arxiv.org/abs/2311.08562)] #
- [2023/11] **ALYMPICS: Language Agents Meet Game Theory** *Shaoguang Mao (MSRA) et al. arXiv* [[Paper](https://arxiv.org/abs/2311.03220)] #
- [2023/10] **LLM-Based Agent Society Investigation: Collaboration and Confrontation in Avalon Gameplay** *Yihuai Lan (Hong Kong University of Science and Technology) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.14985)] #
- [2023/10] **Language Agents with Reinforcement Learning for Strategic Play in the Werewolf Game** *ICLR 2024 Conference Submission7720 Authors* [[Paper](https://openreview.net/forum?id=N1gmpVd4iE)] * (learning)
- [2023/10] **Leveraging Word Guessing Games to Assess the Intelligence of Large Language Models** *ICLR 2024 Conference Submission3201 Authors* [[Paper](https://openreview.net/forum?id=z01BwvD41e)] #
- [2023/10] **Exploring Collaboration Mechanisms for LLM Agents** *Jintian Zhang (Zhejiang University) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.02124)] *
- [2023/10] **Avalon's Game of Thoughts: Battle Against Deception through Recursive Contemplation** *Shenzhi Wang (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.01320)] * (ToM)
- [2023/10] **Suspicion-Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4** *Jiaxian Guo (University of Tokyo) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.17277)|[Demo](https://huggingface.co/spaces/cr7-gjx/Suspicion-Agent-Demo)|[Code](https://github.com/CR-Gjx/Suspicion-Agent)] * (ToM)
- [2023/09] **Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf** *Yuzhuang Xu (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.04658)] #
- [2023/08] **Hoodwinked: Deception and Cooperation in a Text-Based Game for Language Models** *Aidan O’Gara (USC) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.01404)|[Code](https://github.com/aogara-ds/hoodwinked)] #

## Benchmarks
- [2023/10] **SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents** *Xuhui Zhou (CMU) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.11667)|[Project Page](https://www.sotopia.world/)|[Code](https://github.com/sotopia-lab/sotopia)] #
- [2023/10] **CivRealm: A Learning and Reasoning Odyssey for Decision-Making Agents** *ICLR 2024 Conference Submission1285 Authors* [[Paper](https://openreview.net/forum?id=UBVNwD3hPN)] #
- [2023/10] **Welfare Diplomacy: Benchmarking Language Model Cooperation** *ICLR 2024 Conference Submission413 Authors* [[Paper](https://openreview.net/forum?id=AKJLnDgzkm)] #
- [2023/10] **DynaEval: A Dynamic Interaction-based Evaluation Framework for Assessing LLMs in Real-world Scenarios** *ICLR 2024 Conference Submission5534 Authors* [[Paper](https://openreview.net/forum?id=f7PmO5boQ9)] #
- [2023/10] **From Text to Tactic: Evaluating LLMs Playing the Game of Avalon** *Jonathan Light et al. arXiv* [[Paper](https://arxiv.org/abs/2310.05036)] #
- [2023/09] **MindAgent: Emerging Gaming Interaction** *Ran Gong (UCLA) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.09971)|[Project Page](https://mindagent.github.io/)] #
- [2023/08] **Flows: Building Blocks of Reasoning and Collaborating AI** *Martin Josifoski (EPFL) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.01285)|[Code](https://github.com/epfl-dlab/aiflows)] #
- [2023/08] **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation** *Jiaju Lin (PTA Studio) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.04026)|[Project Page](https://www.agentsims.com/)|[Code](https://github.com/py499372727/AgentSims/)] #
- [2023/07] **Tachikuma: Understading Complex Interactions with Multi-Character and Novel Objects by Large Language Models** *Yuanzhi Liang et al. arXiv* [[Paper](https://arxiv.org/abs/2307.12573)|[Code](https://github.com/akira-l/Tachikuma)] #

## Taxonomy/Cognitive Architectures
- [2023/10] **Balancing Autonomy and Alignment: A Multi-Dimensional Taxonomy for Autonomous LLM-powered Multi-Agent Architectures** *Thorsten Händler et al. arXiv* [[Paper](https://arxiv.org/abs/2310.03659)] *
- [2023/09] **Synergistic Integration of Large Language Models and Cognitive Architectures for Robust AI: An Exploratory Analysis** *Oscar J. Romero (CMU) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.09830)] *
  
## Theory of Mind
- [2023/10] **Theory of Mind for Multi-Agent Collaboration via Large Language Models** *Huao Li et al. arXiv* [[Paper](https://arxiv.org/abs/2310.10701)] * (ToM)
- [2023/10] **Violation of Expectation via Metacognitive Prompting Reduces Theory of Mind Prediction Error in Large Language Models** *Courtland Leer et al. arXiv* [[Paper](https://arxiv.org/abs/2310.06983)] * (ToM)
- [2023/10] **How FaR Are Large Language Models From Agents with Theory-of-Mind?** *Pei Zhou (Google) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.03051)] * (ToM)

## Social/Simulation/Role-play
- [2023/12] **The Challenge of Using LLMs to Simulate Human Behavior: A Causal Inference Perspective** *George Gui et al. arXiv* [[Paper](https://arxiv.org/abs/2312.15524)] #
- [2023/12] **Generative agent-based modeling with actions grounded in physical, social, or digital space using Concordia** *Alexander Sasha Vezhnevets (Google DeepMind) et al. arXiv* [[Paper](https://arxiv.org/abs/2312.03664)] #
- [2023/11] **How Far Can We Extract Diverse Perspectives from Large Language Models? Criteria-Based Diversity Prompting!** *Shirley Anugrah Hayati et al. arXiv* [[Paper](https://arxiv.org/abs/2311.09799)] #
- [2023/11] **Enhancing Understanding in Generative Agents through Active Inquiring** *Jiaxin Ge et al. NeurIPS IMOL Workshop* [[Paper](https://openreview.net/forum?id=HD18lHluSR)] *
- [2023/11] **Simulating Opinion Dynamics with Networks of LLM-based Agents** *Yun-Shiuan Chuang et al. arXiv* [[Paper](https://arxiv.org/abs/2311.09618)] *
- [2023/11] **Language Agents as Digital Representatives in Collective Decision-Making** *Daniel Jarrett et al. NeuRIPS Workshop in Foundation Models for Decision Making* [[Paper](https://nips.cc/virtual/2023/82757)] *
- [2023/11] **Mitigating Generative Agent Social Dilemmas** *Julian Yocum et al. NeuRIPS Workshop in Foundation Models for Decision Making* [[Paper](https://nips.cc/virtual/2023/82921)] *
- [2023/10] **Humanoid Agents: Platform for Simulating Human-like Generative Agents** *Zhilin Wang (University of Washington) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.05418)|[Project Page](https://github.com/HumanoidAgents/HumanoidAgents)|[Code](https://www.humanoidagents.com/)] #
- [2023/10] **Lyfe Agents: Generative agents for low-cost real-time social interactions** *Zhao Kaiya (MIT) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.02172)] *
- [2023/10] **S3: Social-network Simulation System with Large Language Model-Empowered Agents** *Chen Gao (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2307.14984)] #
- [2023/09] **Generative Agent-Based Modeling: Unveiling Social System Dynamics through Coupling Mechanistic Models with Generative Artificial Intelligence** *Navid Ghaffarzadegan (Virginia Tech) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.11456)] *
- [2023/08] **Exploring the Intersection of Large Language Models and Agent-Based Modeling via Prompt Engineering** *Edward Junprung et al. arXiv* [[Paper](https://arxiv.org/abs/2308.07411)] *
- [2023/08] **SAPIEN: Affective Virtual Agents Powered by Large Language Models** *Masum Hasan (University of Rochester) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.03022)] #
- [2023/08] **AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors** *Weize Chen (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.10848)|[Code](https://github.com/OpenBMB/AgentVerse)] #
- [2023/08] **Quantifying the Impact of Large Language Models on Collective Opinion Dynamics** *Chao Li et al. arXiv* [[Paper](https://arxiv.org/abs/2308.03313)] *
- [2023/07] **To Infinity and Beyond: SHOW-1 and Showrunner Agents in Multi-Agent Simulations** *Philipp Maas (Fable Studio) et al. arXiv* [[Paper](https://fablestudio.github.io/showrunner-agents/static/pdfs/To_Infinity_and_Beyond_SHOW-1_And_Showrunner_Agents_in_Multi_Agent_Simulations_v2.pdf)|[Project Page](https://fablestudio.github.io/showrunner-agents/)] #
- [2023/07] **Are you in a Masquerade? Exploring the Behavior and Impact of Large Language Model Driven Social Bots in Online Social Networks** *Siyu Li (Virginia Tech) et al. arXiv* [[Paper](https://arxiv.org/abs/2307.10337)] #
- [2023/07] **Epidemic Modeling with Generative Agents** *Ross Williams (Virginia Tech) et al. arXiv* [[Paper](https://arxiv.org/abs/2307.04986v1)|[Code](https://github.com/bear96/gabm-epidemic)] #
- [2023/05] **Role-Play with Large Language Models** *Murray Shanahan (Deepmind) et al. arXiv* [[Paper](https://arxiv.org/abs/2305.16367)] #
- [2023/05] **The Role of Summarization in Generative Agents: A Preliminary Perspective** *Xiachong Feng et al. arXiv* [[Paper](https://arxiv.org/abs/2305.01253)] *
- [2023/04] **Generative Agents: Interactive Simulacra of Human Behavior** *Joon Sung Park (Stanford) et al. arXiv* [[Paper](https://arxiv.org/abs/2304.03442)|[Code](https://github.com/joonspk-research/generative_agents)] *
- [2023/03] **CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society** *Guohao Li (KAUST) et al. NeuRIPS 2023* [[Paper](https://arxiv.org/abs/2303.17760)|[Project Page](https://www.camel-ai.org/)|[Code](https://github.com/camel-ai/camel)] *
- [2023/01] **Blind Judgement: Agent-Based Supreme Court Modelling With GPT** *Sil Hamilton (McGill) et al. arXiv* [[Paper](https://arxiv.org/abs/2301.05327)] #
- [2022/08] **Social Simulacra: Creating Populated Prototypes for Social Computing Systems** *Joon Sung Park (Stanford) et al. arXiv* [[Paper](https://arxiv.org/abs/2208.04024)|[Project Page](https://social-simulacra.herokuapp.com/)] #

## Tool-use
- [2023/10] **TPE: Towards Better Compositional Reasoning over Conceptual Tools with Multi-persona Collaboration** *Hongru Wang (The Chinese University of Hong Kong) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.16090)] #
- [2023/08] **Gentopia.AI: A Collaborative Platform for Tool-Augmented LLMs** *Binfeng Xu et al. arXiv* [[Paper](https://arxiv.org/abs/2308.04030)|[Project Page](https://gentopia-ai.github.io/Gentopia-AI-Homepage/)|[Code](https://github.com/Gentopia-AI/Gentopia)] #

## Alignment
- [2023/05] **Training Socially Aligned Language Models in Simulated Human Society** *Ruibo Liu (Dartmouth) et al. arXiv* [[Paper](https://github.com/agi-templar/Stable-Alignment)[Code](https://github.com/agi-templar/Stable-Alignment)] *

## LLM Evaluation
- [2023/09] **Evaluating Agents using Social Choice Theory** *Marc Lanctot et al. arXiv* [[Paper](https://arxiv.org/abs/2312.03121)] #
- [2023/09] **LLM-Deliberation: Evaluating LLMs with Interactive Multi-Agent Negotiation Games** *Sahar Abdelnabi et al. arXiv* [[Paper](https://arxiv.org/abs/2309.17234)|[Code](https://github.com/s-abdelnabi/llm-deliberation)] #
- [2023/08] **ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate** *Chi-Min Chan (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.07201)|[Code](https://github.com/thunlp/ChatEval)] #
- [2022/12] **Evaluating Human-Language Model Interaction** *Mina Lee (Stanford) et al. TMLR* [[Paper](https://arxiv.org/abs/2212.09746)] #

## Self-play
- [2023/05] **Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback** *Yao Fu (University of Edinburgh) et al. arXiv* [[Paper](https://arxiv.org/abs/2305.10142)|[Code](https://github.com/FranxYao/GPT-Bargaining)] * (learn)

## Debating/Discussion
- [2023/11] **Apollo’s Oracle: Retrieval-Augmented Reasoning in Multi-Agent Debates** *Haotian Wang et al. arXiv* [[Paper](https://arxiv.org/abs/2312.04854)] #
- [2023/11] **On the Discussion of Large Language Models: Symmetry of Agents and Interplay with Prompts** *Qineng Wang et al. arXiv* [[Paper](https://arxiv.org/abs/2311.07076)|[Code](https://github.com/FutureForMe/MADRA)] #
- [2023/11] **Towards Reasoning in Large Language Models via Multi-Agent Peer Review Collaboration** *Zhenran Xu et al. arXiv* [[Paper](https://arxiv.org/abs/2311.08152)] #
- [2023/11] **On the Discussion of Large Language Models: Symmetry of Agents and Interplay with Prompts** *Qineng Wang et al. arXiv* [[Paper](https://arxiv.org/abs/2311.07076)] #
- [2023/10] **SocioDojo: Building Lifelong Analytical Agents with Real-world Text and Time Series** *ICLR 2024 Conference Submission2968 Authors* [[Paper](https://openreview.net/forum?id=s9z0HzWJJp)] #
- [2023/10] **Corex: Pushing the Boundaries of Complex Reasoning through Multi-Model Collaboration** *Qiushi Sun (Shanghai AI Laboratory) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.00280)] #
- [2023/10] **ChoiceMates: Supporting Unfamiliar Online Decision-Making with Multi-Agent Conversational Interactions** *Jeongeon Park (KAIST) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.01331)] #
- [2023/10] **Let Models Speak Ciphers: Multiagent Debate through Embeddings** *Chau Pham (Boston University) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.06272)] #
- [2023/09] **Discuss Before Moving: Visual Language Navigation via Multi-expert Discussions** *Yuxing Long (PKU) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.11382)] #
- [2023/09] **ReConcile: Round-Table Conference Improves Reasoning via Consensus among Diverse LLMs** *Justin Chih-Yao Chen (University of North Carolina at Chapel Hill) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.13007)|[Code](https://github.com/dinobby/ReConcile)] #
- [2023/07] **PRD: Peer Rank and Discussion Improve Large Language Model based Evaluations** *Ruosen Li (The University of Texas at Dallas) et al. arXiv* [[Paper](https://arxiv.org/abs/2307.02762)|[Code](https://github.com/bcdnlp/PRD)] #
- [2023/07] **Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration** *Zhenhailong Wang (University of Illinois Urbana-Champaign) et al. arXiv* [[Paper](https://arxiv.org/abs/2307.05300)|[Code](https://github.com/MikeWangWZHL/Solo-Performance-Prompting)] #
- [2023/05] **Examining the Inter-Consistency of Large Language Models: An In-depth Analysis via Debate** *Kai Xiong et al. arXiv* [[Paper](https://arxiv.org/abs/2305.11595)] #
- [2023/05] **LM vs LM: Detecting Factual Errors via Cross Examination** *Roi Cohen (Tel Aviv University) et al. arXiv* [[Paper](https://arxiv.org/abs/2305.13281)] #
- [2023/05] **Mindstorms in Natural Language-Based Societies of Mind** *Mingchen Zhuge (KAUST) et al. arXiv* [[Paper](https://arxiv.org/abs/2305.17066)] #
- [2023/05] **Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate** *Tian Liang (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2305.19118)|[Code](https://github.com/Skytliang/Multi-Agents-Debate)] #
- [2023/05] **Improving Factuality and Reasoning in Language Models through Multiagent Debate** *Yilun Du (MIT) et al. arXiv* [[Paper](https://arxiv.org/abs/2305.14325)|[Project Page](https://composable-models.github.io/llm_debate/)|[Code](https://github.com/composable-models/llm_multiagent_debate)] #
- [2023/04] **ChatLLM Network: More brains, More intelligence** *Rui Hao (Beijing University of Posts and Telecommunications) et al. arXiv* [[Paper](https://arxiv.org/abs/2304.12998)] #
- [2022/04] **Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language** *Andy Zeng (Google) et al. ICLR 2023* [[Paper](https://arxiv.org/abs/2204.00598)|[Project Page](https://socraticmodels.github.io/)|[Code](https://github.com/google-research/google-research/tree/master/socraticmodels)] #

## Applications
### Computer Tasks
- [2023/12] **MAC-SQL: Multi-Agent Collaboration for Text-to-SQL** *Bing Wang (Beihang University) et al. arXiv* [[Paper](https://arxiv.org/abs/2312.11242)]
- [2023/10] **GameGPT: Multi-agent Collaborative Framework for Game Development** *Dake Chen et al. arXiv* [[Paper](https://arxiv.org/abs/2310.08067v1)]
- [2023/10] **Communicative Agents for Software Development** *Chen Qian (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2307.07924)|[Code](https://github.com/OpenBMB/ChatDev)]
- [2023/09] **MetaGPT: Meta Programming for Multi-Agent Collaborative Framework** *Sirui Hong (DeepWisdom) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.00352)|[Code](https://github.com/geekan/MetaGPT)]
- [2023/08] **LLM As DBA** *Xuanhe Zhou (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.05481)|[Code](https://github.com/TsinghuaDatabaseGroup/DB-GPT)]
- [2023/04] **Self-collaboration Code Generation via ChatGPT** *Yihong Dong et al. arXiv* [[Paper](https://arxiv.org/abs/2304.07590)]

### Recommender System
- [2023/10] **On Generative Agents in Recommendation** *An Zhang (National University of Singapore) et al. arxiv* [[Paper](https://arxiv.org/abs/2310.10108)]
- [2023/10] **AgentCF: Collaborative Learning with Autonomous Language Agents for Recommender Systems** *Junjie Zhang (Renmin University) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.09233)]
- [2023/08] **Recommender AI Agent: Integrating Large Language Models for Interactive Recommendations** *Yancheng Wang (Arizona State University) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.14296)]
- [2023/08] **RecMind: Large Language Model Powered Agent For Recommendation** *Xu Huang (University of Science and Technology of China) et al. arXiv* [[Paper](https://arxiv.org/abs/2308.16505)]

### Chatbots/Dialogues
- [2023/11] **A New Dialogue Response Generation Agent for Large Language Models by Asking Questions to Detect User’s Intentions** *Siwei Wu et al. arXiv* [[Paper](https://arxiv.org/abs/2310.03293)]
- [2023/09] **Rehearsal: Simulating Conflict to Teach Conflict Resolution** *Omar Shaikh (Stanford) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.12309)]
- [2023/07] **DialCoT Meets PPO: Decomposing and Exploring Reasoning Paths in Smaller Language Models** *Chengcheng Han et al. arXiv* [[Paper](https://arxiv.org/abs/2310.05074)]
- [2023/07] **DIALGEN: Collaborative Human-LM Generated Dialogues for Improved Understanding of Human-Human Conversations** *Bo-Ru Lu (University of Washington) et al. arXiv* [[Paper](https://arxiv.org/abs/2307.07047)]
- [2023/06] **Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models** *Jimmy Wei (Cornell) et al. arXiv* [[Paper](https://arxiv.org/abs/2304.13835)|[Project Page](https://parl.ai/projects/multilight/)]
- [2023/05] **Decision-Oriented Dialogue for Human-AI Collaboration** *Jessy Lin (UC Berkeley) et al. arXiv* [[Paper]([Decision-Oriented Dialogue for Human-AI Collaboration](https://arxiv.org/abs/2305.20076))|[Project Page](https://collaborative-dialogue.github.io/)|[Code](https://github.com/jlin816/dialop)]
- [2023/04] **Single or Multiple Conversational Agents?: An Interactional Coherence Comparison** *Ana Paula Chaves et al. Proceedings of the ACM on Human-Computer Interaction* [[Paper](https://dl.acm.org/doi/10.1145/3173574.3173765)]
- [2023/04] **CommunityBots: Creating and Evaluating A Multi-Agent Chatbot Platform for Public Input Elicitation** *Zhiqiu Jiang (University of Massachusetts Amherst) et al. Proceedings of the ACM on Human-Computer Interaction* [[Paper](https://dl.acm.org/doi/10.1145/3579469)]

### Robotics
- [2023/09] **Scalable Multi-Robot Collaboration with Large Language Models: Centralized or Decentralized Systems?** *Yongchao Chen (MIT) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.15943)|[Project Page](https://yongchao98.github.io/MIT-REALM-Multi-Robot/)|[Code](https://github.com/yongchao98/multi-agent-framework)]
- [2023/09] **SMART-LLM: Smart Multi-Agent Robot Task Planning using Large Language Models** *Shyam Sundar Kannan (Purdue) et al. arXiv* [[Paper](https://arxiv.org/abs/2309.10062)]
- [2023/07] **RoCo: Dialectic Multi-Robot Collaboration with Large Language Models** *Zhao Mandi (Columbia) et al. arXiv* [[Paper](https://arxiv.org/abs/2307.04738)|[Project Page](https://project-roco.github.io/)|[Code](https://github.com/MandiZhao/robot-collab)]

### Autonomous Driving
- [2023/12] **Large Language Models for Autonomous Driving: Real-World Experiments** *Can Cui et al. arXiv.* [[Paper](https://arxiv.org/abs/2312.09397)]
- [2023/11] **A Language Agent for Autonomous Driving** *Jiageng Mao et al. arXiv.* [[Paper](https://arxiv.org/abs/2311.10813)|[Project Page](https://usc-gvl.github.io/Agent-Driver/)|[Code](https://github.com/USC-GVL/Agent-Driver)]
- [2023/10] **Drive Anywhere: Generalizable End-to-end Autonomous Driving with Multi-modal Foundation Models** *Tsun-Hsuan Wang (MIT) et al. arXiv.* [[Paper](https://arxiv.org/abs/2310.17642)]
- [2023/10] **Receive, Reason, and React: Drive as You Say with Large Language Models in Autonomous Vehicles** *Can Cui (Purdue) et al. arXiv.* [[Paper](https://arxiv.org/abs/2310.08034)]
- [2023/10] **LanguageMPC: Large Language Models as Decision Makers for Autonomous Driving** *Hao Sha (Tsinghua) et al. arXiv.* [[Paper](https://arxiv.org/abs/2310.03026)]
- [2023/09] **SurrealDriver: Designing Generative Driver Agent Simulation Framework in Urban Contexts based on Large Language Model** *Ye Jin (Tsinghua) et al. arXiv.* [[Paper](https://arxiv.org/abs/2309.13193)]
- [2023/09] **DiLu: A Knowledge-Driven Approach to Autonomous Driving with Large Language Models** *Licheng Wen (Shanghai AI Laboratory) et al. arXiv.* [[Paper](https://arxiv.org/abs/2309.16292)]

### Others
- [2023/12] **Agent4Ranking: Semantic Robust Ranking via Personalized Query Rewriting Using Multi-agent LLM** *Xiaopeng Li et al. arXiv* [[Paper](https://arxiv.org/abs/2312.15450)]
- [2023/12] **AgentCoder: Multi-Agent-based Code Generation with Iterative Testing and Optimisation** *Dong Huang et al. arXiv* [[Paper](https://arxiv.org/abs/2312.13010)]
- [2023/12] **Large Language Models Play StarCraft II: Benchmarks and A Chain of Summarization Approach** *Weiyu Ma et al. arXiv* [[Paper](https://arxiv.org/abs/2312.11865)]
- [2023/12] **LLM as OS (llmao), Agents as Apps: Envisioning AIOS, Agents and the AIOS-Agent Ecosystem** *Yingqiang Ge et al. arXiv* [[Paper](https://arxiv.org/abs/2312.03815)]
- [2023/12] **Beyond Isolation: Multi-Agent Synergy for Improving Knowledge Graph Construction** *Hongbin Ye et al. arXiv* [[Paper](https://arxiv.org/abs/2312.03022)]
- [2023/11] **TrainerAgent: Customizable and Efficient Model Training through LLM-Powered Multi-Agent System** *Haoyuan Li et al. arXiv* [[Paper](https://arxiv.org/abs/2311.06622)]
- [2023/11] **War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars** *Wenyue Hua et al. arXiv* [[Paper](https://arxiv.org/abs/2311.17227)]
- [2023/11] **Evil Geniuses: Delving into the Safety of LLM-based Agents** *Yu Tian (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2311.11855)]
- [2023/11] **DesignGPT: Multi-Agent Collaboration in Design** *Shiying Ding et al. arXiv* [[Paper](https://arxiv.org/abs/2311.11591)]
- [2023/11] **MEDAGENTS: Large Language Models as Collaborators for Zero-shot Medical Reasoning** *Xiangru Tang (Yale) et al. arXiv* [[Paper](https://arxiv.org/abs/2311.10537)]
- [2023/11] **On Evaluating the Integration of Reasoning and Action in LLM Agents with Database Question Answering** *Linyong Nan et al. arXiv* [[Paper](https://arxiv.org/abs/2311.09721)]
- [2023/11] **MechAgents: Large language model multi-agent collaborations can solve mechanics problems, generate new data, and integrate knowledge** *Bo Ni et al. arXiv* [[Paper](https://arxiv.org/abs/2311.08166)]
- [2023/11] **Large Language Models are Zero Shot Hypothesis Proposers** *Biqing Qi (Tsinghua) et al. arXiv* [[Paper](https://arxiv.org/abs/2311.05965)]
- [2023/11] **Leveraging Large Language Models for Collective Decision-Making** *Marios Papachristou (Cornell) et al. arXiv* [[Paper](https://arxiv.org/abs/2311.04928)]
- [2023/11] **Large Language Models Illuminate a Progressive Pathway to Artificial Healthcare Assistant: A Review** *Mingze Yuan (PKU) et al. arXiv* [[Paper](https://arxiv.org/abs/2311.01918)|[Code](https://github.com/mingze-yuan/Awesome-LLM-Healthcare)]
- [2023/10] **3D-GPT: Procedural 3D Modeling with Large Language Models** *Chunyi Sun et al. arXiv* [[Paper](https://arxiv.org/abs/2310.12945)]
- [2023/10] **Stance Detection with Collaborative Role-Infused LLM-Based Agents** *Xiaochong Lan (Tsinghua University) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.10467)]
- [2023/10] **How AI Processing Delays Foster Creativity: Exploring Research Question Co-Creation with an LLM-based Agent** *Yiren Liu (University of Illinois Urbana-Champaign) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.06155)]
- [2023/10] **Large Language Models Can Design Game-Theoretic Objectives for Multi-Agent Planning** *ICLR 2024 Conference Submission8283 Authors* [[Paper](https://openreview.net/forum?id=DnkCvB8iXR)]
- [2023/10] **Chain-of-Experts: When LLMs Meet Complex Operations Research Problems** *ICLR 2024 Conference Submission5639 Authors* [[Paper](https://openreview.net/forum?id=HobyL1B9CZ)]
- [2023/10] **Empowering Psychotherapy with Large Language Models: Cognitive Distortion Detection through Diagnosis of Thought Prompting** *Zhiyu Chen (CMU) et al. arXiv* [[Paper](https://arxiv.org/abs/2310.07146)]
- [2023/10] **The Effect of Context-aware LLM-based NPC Conversations on Player Engagement in Role-playing Video Games** *Lajos Matyas Csepregi et al. arXiv* [[Paper](https://projekter.aau.dk/projekter/files/536738243/The_Effect_of_Context_aware_LLM_based_NPC_Dialogues_on_Player_Engagement_in_Role_playing_Video_Games.pdf)]
- [2023/09] **TradingGPT: Multi-Agent System with Layered Memory and Distinct Characters for Enhanced Financial Trading Performance** *Yang Li et al. arXiv* [[Paper](https://arxiv.org/abs/2309.03736)]
- [2023/09] **Wireless Multi-Agent Generative AI: From Connected Intelligence to Collective Intelligence** *Hang Zou et al. arXiv* [[Paper](https://arxiv.org/abs/2307.02757)]
- [2023/05] **ChatGPT as your Personal Data Scientist** *Md Mahadi Hassan (Auburn) et al. arXiv* [[Paper](https://arxiv.org/abs/2305.13657)]

## Open-source Projects
- **GPTeam: Collaborative AI Agents** [[Code](https://github.com/101dotxyz/GPTeam)]

---

## Contacts
- Andrew Zhao [Email: zqc21@mails.tsinghua.edu.cn|[Personal Page](https://andrewzh112.github.io/)]

## Other LLM-based Agent Repositories
- [🐨CoALA: Awesome Language Agents](https://github.com/ysymyth/awesome-language-agents)
- [The Rise and Potential of Large Language Model Based Agents: A Survey](https://github.com/WooooDyy/LLM-Agent-Paper-List)
- [A Survey on LLM-based Autonomous Agents](https://github.com/Paitesanshi/LLM-Agent-Survey)

## TODOs
- [x] Make repo visible to public
- [x] Init commit added existing papers

## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=Andrewzh112/Awesome-LLM-based-MultiAgents&type=Date)](https://star-history.com/#Andrewzh112/Awesome-LLM-based-MultiAgents&Date)

[[Back the Top]](#awesome-large-language-modellarge-multi-modal-model--based-multi-agents)
