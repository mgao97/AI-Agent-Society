# AI Agent and Agent Society

Existing research is gradually moving from individual LLM agents toward multi-agent collaboration and agent societies. Early work focuses on agent architectures with memory, planning, reflection, and tool use, while subsequent studies investigate role-based collaboration, communication, and organizational structures. More recent work, such as *Generative Agents*, *AgentVerse*, and *SOTOPIA*, goes beyond task-oriented collaboration to study social interaction, emergent behaviors, social intelligence, and collective dynamics, suggesting a transition from building better individual agents to understanding how intelligent societies can emerge from interacting agents.

---

## 1. Generative Agents: Interactive Simulacra of Human Behavior

**Authors:** Joon Sung Park, Joseph C. O'Brien, Carrie J. Cai, Meredith Ringel Morris, Percy Liang, Michael S. Bernstein

**Venue:** UIST 2023

**Paper:** https://doi.org/10.1145/3586183.3606763

This work introduces **Generative Agents**, a framework that combines LLMs with memory, reflection, observation, and planning to simulate believable human-like behaviors. By deploying 25 agents in an interactive virtual town, the authors demonstrate that individual behaviors and higher-level **emergent social behaviors**, such as information spreading, relationship formation, and group coordination, can arise from agent interactions.

---

## 2. CAMEL: Communicative Agents for “Mind” Exploration of Large Language Model Society

**Authors:** Guohao Li, Hasan Abed Al Kader Hammoud, Hani Itani, Dmitrii Khizbullin, Bernard Ghanem

**Venue:** NeurIPS 2023 Workshop / arXiv

**Paper:** https://openreview.net/forum?id=3IyL2XWDkG

CAMEL investigates how multiple LLM agents can autonomously cooperate through **role-playing and communicative interactions**. The framework assigns agents different roles and uses inception prompting to guide their interactions, providing an early foundation for studying the behaviors, capabilities, and dynamics of an emerging **LLM-based society**.

---

## 3. AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors

**Authors:** Weize Chen, Yusheng Su, Jingwei Zuo, Cheng Yang, Chenfei Yuan, Chi-Min Chan, Heyang Yu, Yaxi Lu, Yi-Hsin Hung, Chen Qian, Yujia Qin, Xin Cong, Ruobing Xie, Zhiyuan Liu, Maosong Sun, Jie Zhou

**Venue:** ICLR 2024

**Paper:** https://proceedings.iclr.cc/paper_files/paper/2024/hash/578e65cdee35d00c708d4c64bce32971-Abstract-Conference.html

AgentVerse provides a multi-agent framework for dynamically organizing groups of specialized agents to solve complex tasks. Beyond demonstrating that agent groups can outperform individual agents, the work explicitly analyzes **emergent collaborative behaviors** arising from agent interactions, making it an important step from multi-agent orchestration toward agent-society research.

---

## 4. SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents

**Authors:** Xuhui Zhou, Hao Zhu, Leena Mathur, Ruohong Zhang, Haofei Yu, Zhengyang Qi, Louis-Philippe Morency, Yonatan Bisk, Daniel Fried, Graham Neubig, Maarten Sap

**Venue:** ICLR 2024

**Paper:** https://proceedings.iclr.cc/paper_files/paper/2024/hash/b3075b88e583a0e98d8b24338a613060-Abstract-Conference.html

SOTOPIA introduces an open-ended environment for evaluating **social intelligence in language agents** through complex role-playing interactions. Agents must coordinate, collaborate, compete, negotiate, and pursue social goals, revealing that even strong LLMs still struggle with social commonsense, strategic communication, and goal completion compared with humans.

---

## 5. AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation

**Authors:** Qingyun Wu, Gagan Bansal, Jieyu Zhang, Yiran Wu, Beibin Li, Erkang Zhu, Li Jiang, Xiaoyun Zhang, Shaokun Zhang, Jiale Zhan, et al.

**Venue:** COLM 2024

**Paper:** https://arxiv.org/abs/2308.08155

AutoGen proposes a framework for building LLM applications through **multi-agent conversations**, where agents can interact with other agents, humans, and external tools. The work focuses primarily on flexible agent orchestration and communication patterns, providing an important infrastructure for constructing more complex multi-agent systems.

---

## 6. MetaGPT: Meta Programming for Multi-Agent Collaborative Framework

**Authors:** Sirui Hong, Mingchen Zhuge, Jonathan Chen, Xiawu Zheng, Yuheng Cheng, Ceyao Zhang, Jinlin Wang, Zili Wang, et al.

**Venue:** ICLR 2024

**Paper:** https://proceedings.iclr.cc/paper_files/paper/2024/hash/6507b115562bb0a305f1958ccc87355a-Abstract-Conference.html

MetaGPT organizes multiple agents according to **human organizational roles and standard operating procedures (SOPs)**, such as product manager, architect, engineer, and reviewer. Rather than allowing agents to communicate freely, it structures their interactions according to predefined workflows, demonstrating how organizational structures can improve the reliability and efficiency of multi-agent collaboration.

---

## 7. ChatDev: Communicative Agents for Software Development

**Authors:** Chen Qian, Wei Liu, Hongzhang Liu, et al.

**Venue:** ACL 2024

**Paper:** https://aclanthology.org/2024.acl-long.810/

ChatDev simulates a software company in which specialized LLM agents, such as CEOs, programmers, reviewers, and testers, communicate through natural language to collaboratively develop software. The work demonstrates how **role specialization and structured communication** can transform multiple LLM agents into an organization-like system for complex task execution.

---

## 8. AgentBench: Evaluating LLMs as Agents

**Authors:** Xiao Liu, Hao Yu, Hanchen Zhang, Yifan Xu, Xuanyu Lei, Hanyu Lai, Yu Gu, Yifan Deng, et al.

**Venue:** ICLR 2024

**Paper:** https://proceedings.iclr.cc/paper_files/paper/2024/hash/e9df36b21ff4ee211a8b71ee8b7e9f57-Abstract-Conference.html

AgentBench introduces a benchmark for evaluating LLMs as **interactive agents** across multiple environments and tasks. It evaluates capabilities such as reasoning, planning, decision making, and instruction following, highlighting that agent performance depends on long-horizon interaction and decision making rather than language generation alone.

---

## 9. A Survey on Large Language Model based Autonomous Agents

**Authors:** Lei Wang, Chen Ma, Xueyang Feng, Zhiqiang Zhang, Hao Yang, Jingsen Zhang, Zhiyuan Chen, Junyan Tang, Xu Chen, Jiayuan Li, et al.

**Venue:** Frontiers of Computer Science, 2024

**Paper:** https://link.springer.com/article/10.1007/s11704-024-40231-1

This survey provides a systematic overview of LLM-based autonomous agents, covering their architectures, memory, planning, tool use, action, and applications. It provides a useful conceptual foundation for understanding how LLMs evolve from passive language models into **autonomous, interactive, and goal-directed agents**.

---

## 10. Large Language Model based Multi-Agents: A Survey of Progress and Challenges

**Authors:** Taicheng Guo, Xiang Ji, et al.

**Venue:** IJCAI 2024

**Paper:** https://www.ijcai.org/proceedings/2024/890

This survey reviews the development of LLM-based multi-agent systems, focusing on agent communication, collaboration, coordination, and emergent capabilities. It organizes existing work around how agents interact and cooperate, providing a broader view of the transition from individual agents toward **collective intelligence and multi-agent societies**.

## 11. AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society

**Authors:** Jinghua Piao, Yuwei Yan, Jun Zhang, Nian Li, Junbo Yan, Xiaochong Lan, Zhihong Lu, Zhiheng Zheng, Jing Yi Wang, Di Zhou, Chen Gao, Fengli Xu, Fang Zhang, Ke Rong, Jun Su, Yong Li

**Venue:** arXiv, 2025

**Paper:** https://arxiv.org/abs/2502.08691

AgentSociety develops a large-scale social simulator that integrates LLM-driven agents, realistic environments, and a scalable simulation engine. The system simulates more than **10,000 agents and 5 million interactions** and uses the resulting society to study polarization, inflammatory information propagation, policy interventions, and external shocks, pushing generative-agent research from small-scale demonstrations toward computational social science.

---

## 12. MultiAgentBench: Evaluating the Collaboration and Competition of LLM Agents

**Authors:** Kunlun Zhu, Hongyi Du, Zhaochen Hong, Xiaocheng Yang, Shuyi Guo, Zhe Wang, Zhenhailong Wang, Cheng Qian, Xiangru Tang, Heng Ji, Jiaxuan You

**Venue:** ACL 2025

**Paper:** https://aclanthology.org/2025.acl-long.421/

MultiAgentBench introduces a benchmark for evaluating **collaboration and competition among LLM agents** in interactive scenarios. It evaluates different coordination structures, including star, chain, tree, and graph topologies, and shows that the structure of agent communication can substantially affect collective performance, providing a more systematic way to study multi-agent coordination.

---

## 13. Investigating and Extending Homans’ Social Exchange Theory with Large Language Model based Agents

**Authors:** Lei Wang, Zheqing Zhang, Xu Chen

**Venue:** ACL 2025

**Paper:** https://aclanthology.org/2025.acl-long.481/

This work uses a virtual society of LLM agents to investigate **Homans’ Social Exchange Theory**, a classical theory explaining how social relationships emerge through repeated exchanges. The experiments show that agent behaviors can reproduce key patterns predicted by the theory and demonstrate how LLM-based societies can serve as experimental environments for testing and extending theories from social science.

---

## 14. MOSAIC: Modeling Social AI for Content Dissemination and Regulation in Multi-Agent Simulations

**Authors:** Genglin Liu, Vivian T. Le, Salman Rahman, Elisa Kreiss, Marzyeh Ghassemi, Saadia Gabriel

**Venue:** EMNLP 2025

**Paper:** https://aclanthology.org/2025.emnlp-main.325/

MOSAIC models an online social network using generative agents and a directed social graph, where agents simulate behaviors such as liking, sharing, and flagging content. The framework is used to study misinformation dissemination and moderation, showing how LLM-driven social simulations can connect **agent behavior, network structure, and large-scale information diffusion**.

---

## 15. Negotiating Comfort: Simulating Personality-Driven LLM Agents in Shared Residential Social Networks

**Authors:** Ann Nedime Nese Rende, Tolga Yilmaz, Özgür Ulusoy

**Venue:** arXiv, 2025

**Paper:** https://arxiv.org/abs/2507.09657

This work studies personality-driven LLM agents interacting within a shared residential social network, where agents negotiate decisions based on preferences, personality traits, relationships, and environmental conditions. The results show that personality characteristics can influence both individual decisions and emergent social outcomes such as happiness and friendship formation.

---

## 16. Unraveling the Emergence of Collective Behavior in Networks of Cognitive Agents

**Authors:** Nicola Zomer, Manlio De Domenico

**Venue:** npj Artificial Intelligence, 2026

**Paper:** https://www.nature.com/articles/s44387-026-00091-5

This work investigates how LLM-based cognitive agents generate **collective behavior** when connected through explicit communication networks. By comparing LLM agents with classical particle-based systems and studying both optimization and Schelling-style segregation, the authors show that agent intelligence, communication topology, and homophily can fundamentally alter collective dynamics and lead to new forms of emergent behavior.

---

## 17. Emergent Social Intelligence Risks in Generative Multi-Agent Systems

**Authors:** Yue Huang, Yu Jiang, Wenjie Wang, Haomin Zhuang, Xiaonan Luo, Yucheng Ma, Zhangchen Xu, Zichen Chen, Nuno Moniz, Zinan Lin, Pin-Yu Chen, Nitesh V. Chawla, Nouha Dziri, Huan Sun, Xiangliang Zhang

**Venue:** arXiv / Microsoft Research, 2026

**Paper:** https://www.microsoft.com/en-us/research/publication/emergent-social-intelligence-risks-in-generative-multi-agent-systems/

This work studies **emergent risks that arise at the collective level rather than from individual agents**, including collusion-like coordination and conformity. The results suggest that some social failure modes can spontaneously emerge from interaction protocols, resource competition, and role assignments, and therefore cannot be adequately addressed by applying safety mechanisms to individual agents alone.

---

## 18. Beyond Static Responses: Multi-Agent LLM Systems as a New Paradigm for Social Science Research

**Authors:** Jennifer Haase, Sebastian Pokutta

**Venue:** arXiv, 2025–2026

**Paper:** https://arxiv.org/abs/2506.01839

This work proposes a framework for understanding LLM-based agents as tools for **computational social science**, ranging from simple language-model applications to complex multi-agent simulations. It highlights the potential of agent societies for studying group dynamics, norm formation, and large-scale social processes, while emphasizing challenges in reproducibility, emergent bias, ethical oversight, and evaluation.

---

## 19. Emergent Relational Order in LLM Agent Societies: From Collective Affect to Authority Stratification

**Authors:** Zhiyuan Ji, Xinyu Chen, Ziqi Dai, Shiyun Tang, Chunyu Wei, Yueguo Chen

**Venue:** Findings of ACL 2026

**Paper:** https://aclanthology.org/2026.findings-acl.1658/

This work investigates whether complex social structures can emerge in LLM agent societies over long-horizon interactions. Using a framework grounded in Affect Control Theory, Social Identity Theory, and Durkheimian collective affect, the authors observe emergent labor specialization, relational cooperation decay, authority formation, and center–periphery stratification, demonstrating a shift from short-term agent coordination toward **long-term social structure formation**.

---

## 20. Experimental Evidence on the Emergent Social Network Patterns of LLM-Driven Multi-Agent System for Edge Service Collaboration

**Authors:** Weiyue Chen, Guoshuai Zhang, Jiaji Wu, Gwanggil Jeon

**Venue:** Tsinghua Science and Technology, 2026

**Paper:** https://doi.org/10.26599/TST.2026.9010040

This work explicitly models interactions among LLM agents as an **evolving social network** and analyzes more than 200,000 simulation records. The experiments reveal emergent network phenomena such as triadic closure, reciprocal relationships, and decreasing relationship strength with increasing group size, providing direct evidence that meaningful social-network structures can emerge without explicitly programmed social rules.

