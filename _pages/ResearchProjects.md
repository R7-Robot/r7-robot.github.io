---
layout: archive
title: "Research Projects"
permalink: /ResearchProjects/
author_profile: true
---

## Adaptive Multi-Human Multi-Robot Systems
Multi-human multi-robot (MH-MR) teams are emerging as promising assets for tackling high-stakes and large-scale missions, such as environmental monitoring, disaster recovery, and search and rescue. The simultaneous collaboration of multiple humans and robots with diverse capabilities, expertise, and characteristics offers tremendous potential to enhance team complementarity, productivity, and versatility. However, this inherent heterogeneity also introduces significant coordination challenges. 

Furthermore, while integrating human operators at the core of the decision-making process can greatly improve the team's situational awareness and flexibility, it also introduces additional uncertainty and complexity. Human states, such as cognitive load and emotion, as well as performance are inherently fickle, influenced by various internal or external factors.

To address these challenges and unlock the full potential of MH-MR teams, this project focuses on three core objectives:


### _Adaptive Teaming Strategies_ 

Develop advanced Initial Task Allocation (ITA) strategies that account for team heterogeneity during the teaming stage. This involves dynamically initializing task distribution, assigning roles, and defining collaboration patterns by considering the diverse capabilities of both humans and robots under varying task requirements. The objective is to harness this heterogeneity constructively, forming complementary human-robot pairings or chains that optimize overall team performance.

<div style="display: flex; justify-content: center; align-items: center;">
  <figure style="margin: 0 10px; text-align: center;">
    <img src="/images/ITA.PNG" style="height: 300px; width: auto;" />
  </figure>
  <figure style="margin: 0 10px; text-align: center;">
    <img src="/images/ITAENV.gif" style="height: 300px; width: auto;" />
  </figure>
</div>

**Related Papers:**  
- [Initial Task Allocation in Multi-Human Multi-Robot Teams: An Attention-enhanced Hierarchical Reinforcement Learning Approach](https://sites.google.com/view/ita-aehrl), *IEEE RA-L 2024*.  
- [Initial Task Allocation for Multi-Human Multi-Robot Teams with Attention-based Deep Reinforcement Learning](https://sites.google.com/view/ITA-AtRL), *IROS 2023*.  
- [REBEL: Rule-based and Experience-enhanced Learning with LLMs for Initial Task Allocation in Multi-Human Multi-Robot Teams](https://sites.google.com/view/ita-rebel/home), *Arxiv, pre-print 2025*.  


### _Multimodal Human State Reasoning_

Investigate the dynamics of human states, including cognitive load and emotion, and develop models that provide real-time assessments using multimodal physiological and behavioral signals.

<div style="display: flex; justify-content: center; align-items: center;">
  <div style="margin-right: 10px;">
    <img src="/files/mocas.png" style="max-width: 100%; height: auto; display: block;" />
  </div>
  <div>
    <img src="/files/hus.png" style="max-width: 100%; height: auto; display: block;" />
  </div>
</div>


**Related Papers:**  
- [MOCAS: A Multimodal Dataset for Objective Cognitive Workload Assessment on Simultaneous Tasks](https://arxiv.org/pdf/2210.03065), *IEEE TAFFC 2024*.  
- [Husformer: A Multi-Modal Transformer for Multi-Modal Human State Recognition](https://ieeexplore.ieee.org/document/10413204), *IEEE TCDS 2024*.  


### _Dynamic Adaptation Mechanisms During Operation_

Develop adaptive mechanisms to re-adjust team collaboration patterns and re-allocate tasks within the team according to perceived changes in human states, robot conditions, and evolving task progress.


<div style="display: flex; justify-content: center; align-items: center;">
  <div style="margin-right: 10px;">
    <img src="/images/ahmrs.png" style="max-width: 100%; height: auto; display: block;" />
  </div>
  <div>
    <img src="/images/MHMRENV.PNG" style="max-width: 100%; height: auto; display: block;" />
  </div>
</div>


**Related Papers:**  
- [Adaptive Task Allocation in Multi-Human Multi-Robot Teams under Team Heterogeneity and Dynamic Information Uncertainty](https://sites.google.com/view/ata-hrl/home), *ICRA 2025*.  
- [Cognitive Load-based Affective Workload Allocation for Multi-Human Multi-Robot Teams](https://sites.google.com/view/affective-workload-allocation/home), *IEEE THMS*.  


---

## Human-in-the-Loop Robot Learning for Personalized Human-Robot Interaction

While human-robot systems can be optimized for objective factors, such as team heterogeneity and operational states, individual preferences often transcend these measurable aspects. Individuals with similar capabilities or operational conditions may still prefer different interaction patterns. Personalizing robot behaviors to align with these unique preferences is critical, as it enhances user satisfaction, engagement, and overall interaction quality. 

This project aims to develop efficient human-in-the-loop, preference-based robot learning algorithms to facilitate this personalization process. We specifically investigate how to improve the efficiency of feedback required, how to accurately model human preferences toward robot behaviors, and how to efficiently fine-tune robot policies to reflect these preferences.

<div style="display: flex; justify-content: center; align-items: center;">
  <img src="/images/frame1.gif" style="height: 300px; width: auto; margin-right: 10px;" />
  <img src="/images/User2.gif" style="height: 300px; width: auto;" />
</div>


**Related Papers:**  
- [PrefCLM: Enhancing Preference-based Reinforcement Learning with Crowdsourced Large Language Models](https://prefclm.github.io/), *IEEE RA-L 2025*.  
- [Personalization in Human-Robot Interaction through Preference-based Action Representation Learning](https://sites.google.com/view/pbarl/home), *ICRA 2025*.  
- [PrefMMT: Modeling Human Preferences in Preference-based Reinforcement Learning with Multimodal Transformers](https://sites.google.com/view/prefmmt/home), *Arxiv*.
- [Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation](https://sites.google.com/view/san-fapl), *IROS 2022*.   


---

## Socially-Aware Robot Navigation

Socially-aware robot navigation (SAN) involves optimizing a robot's trajectory to maintain comfortable and compliant spatial interactions with humans while efficiently reaching its goal without collisions. This task is fundamental yet challenging within human-robot interaction contexts, as it requires balancing safety, efficiency, and social etiquette.

Our work focuses on **Modeling Complex Social Interactions** by developing algorithms that better encode and interpret the intricate social dynamics within varied environments. This involves leveraging advanced deep learning techniques to understand human behaviors in diverse settings, enabling robots to navigate with a deeper awareness of social nuances.

<div style="text-align: center;">
  <img src="/images/SAN2.PNG" style="max-width: 85%; height: auto; display: block; margin: 0 auto;" alt="Socially-Aware Robot Navigation" />
</div>



**Related Papers:**  
- [Multi-Robot Cooperative Socially-Aware Navigation using Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2309.15234), *ICRA 2024*.  
- [NaviSTAR: Socially Aware Robot Navigation with Hybrid Spatio-Temporal Graph Transformer and Preference Learning](https://arxiv.org/pdf/2304.05979), *IROS 2023*.  
- [Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation](https://sites.google.com/view/san-fapl), *IROS 2022*.  



