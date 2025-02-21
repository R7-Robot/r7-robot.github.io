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

---

### Adaptive Teaming Strategies 

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

---

### Multimodal Human State Reasoning

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

---

### Dynamic Adaptation Mechanisms During Operation

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




## Human-in-the-loop Robot Learning for Personalized Human-Robot Interaction
Human preferences for robot interaction behaviors are inherently diverse and individual. Adapting and personalizing robot behaviors to these individual preferences is crucial, as it can significantly enhance user satisfaction, engagement, and overall interaction quality. This project aims to develop efficient human-in-the-loop robot learning algorithms to facilitate this personalization process. Our primary objective is to develop innovative and transformative frameworks and algorithms that enable seamless robot adaptation in human-robot interaction by efficiently understanding and learning from human feedback and preferences.

<div style="display: flex; justify-content: center; align-items: center;">
  <img src="/images/frame1.gif" style="height: 300px; width: auto; margin-right: 10px;" />
  <img src="/images/User2.gif" style="height: 300px; width: auto;" />
</div>


Related papers:  
- [Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation](https://sites.google.com/view/san-fapl), IROS 2022.
- [PrefCLM: Enhancing Preference-based Reinforcement Learning with Crowdsourced Large Language Models](https://prefclm.github.io/), ArXiv Pre-print.




## Socially-aware Robot Navigation
Socially-aware robot navigation (SAN), in which a robot must optimize its trajectory to maintain comfortable and compliant spatial interactions with humans while also reaching its goal without collisions, is a fundamental but challenging task in the context of human-robot interaction. In this project, our work focuses on two main areas: 1) Encoding Complex Social Interactions: We are developing algorithms to better encode and interpret the intricate social dynamics within varied environments. This involves utilizing advanced deep learning techniques to understand human behaviors in different settings, enabling robots to navigate with a deeper awareness of social nuances; and 2) Innovative Teaching Methods for Robots: We are exploring new methods to teach robots that move beyond traditional reinforcement and inverse reinforcement learning. This includes devising intuitive and effective reward systems that more accurately reflect social compliance and exploring alternatives to reduce reliance on human demonstrations.

<div style="text-align: center;">
  <img src="/images/SAN2.PNG" style="max-width: 85%; height: auto; display: block; margin: 0 auto;" />
</div>

Relevant papers:  
- [Multi-Robot Cooperative Socially-Aware Navigation using Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2309.15234), ICRA 2024.
- [NaviSTAR: Socially Aware Robot Navigation with Hybrid Spatio-Temporal Graph Transformer and Preference Learning](https://arxiv.org/pdf/2304.05979), IROS 2023.
- [Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation](https://sites.google.com/view/san-fapl), IROS 2022.



