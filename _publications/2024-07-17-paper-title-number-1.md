---
title: "Towards Collaborative Intelligence: Propagating Intentions and Reasoning for Multi-Agent Coordination with Large Language Models"
collection: publications
category: manuscripts
permalink: /publication/2024-07-17-paper-title-number-1
excerpt: '<div style="text-align: justify;">The paper proposes REMALIS, a framework using LLMs in multi - agent systems. It shares intentions, has bidirectional coordination, and recursive reasoning, outperforming baselines in complex tasks.</div>'
date: 2024-07-17
venue: 'arXiv'
paperurl: 'http://jizhanpeng.cn/xiongyujie.github.io/files/Towards_Collaborative_Intelligence_Propagating_Intentions_and_Reasoning_for_Multi-Agent_Coordination_with_Large_Language_Models.pdf'
citation: '<br/><div style="text-align: justify;">Towards Collaborative Intelligence: Propagating Intentions and Reasoning for Multi-Agent Coordination with Large Language Models, X.-H. Qiu*, H.-Y. Wang, X.-Y. Tan, C. Qu, Y.-J. Xiong, Y. Chen, Y.-H. Xu, W. Chu, Y. Qi, arxiv preprint, arxiv:2407.12532 (2024)</div>'
---

<div style="text-align: justify;">Effective collaboration in multi-agent systems requires communicating goals and intentions between agents. Current agent frameworks often suffer from dependencies on singleagent execution and lack robust inter-module communication, frequently leading to suboptimal multi-agent reinforcement learning (MARL) policies and inadequate task coordination. To address these challenges, we present a framework for training large language models (LLMs) as collaborative agents to enable coordinated behaviors in cooperative MARL. Each agent maintains a private intention consisting of its current goal and associated sub-tasks. Agents broadcast their intentions periodically, allowing other agents to infer coordination tasks. A propagation network transforms broadcast intentions into teammate-specific communication messages, sharing relevant goals with designated teammates. The architecture of our framework is structured into planning, grounding, and execution modules. During execution, multiple agents interact in a downstream environment and communicate intentions to enable coordinated behaviors. The grounding module dynamically adapts comprehension strategies based on emerging coordination patterns, while feedback from execution agents influnces the planning module, enabling the dynamic re-planning of sub-tasks. Results in collaborative environment simulation demonstrate intention propagation reduces miscoordination errors by aligning sub-task dependencies between agents. Agents learn when to communicate intentions and which teammates require task details, resulting in emergent coordinated behaviors. This demonstrates the efficacy of intention sharing for cooperative multi-agent RL based on LLMs.</div>

<br/>
