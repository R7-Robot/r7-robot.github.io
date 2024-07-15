---
layout: archive
title: "Research Projects"
permalink: /ResearchProjects/
author_profile: true
---
## Adaptive Multi-Human Multi-Robot Systems
Multi-human multi-robot (MH-MR) teams are emerging as promising assets for tackling complex and expansive missions, such as environmental monitoring, disaster recovery, and military operations. The collaboration of multiple humans and robots with diverse capabilities, expertise, and characteristics presents great potential to enhance team complementarity, productivity, and versatility. However, this inherent heterogeneity within the team also introduces coordination challenges. Moreover, incorporating human operators as the core of the decision-making process can significantly improve the situational awareness and flexibility of the team, but it also introduces more uncertainty and complexity. Human affective conditions, such as cognitive load and emotion, as well as performance, are inconsistent and susceptible to various internal or external factors.

To unlock the full potential of MH-MR teams, this project focuses on developing adaptive systems capable of initializing mission-specific MH-MR teams by considering the inherent heterogeneity, proactively monitoring and analyzing the cognitive and emotional states of operators, and enabling human operators to adapt to robot system changes and robots to adapt to human cognitive and emotional states. Specifically, we aim to:

- Develop sophisticated initial task allocation (ITA) strategies that adapt to team heterogeneity. These strategies will optimally initialize task distribution by allocating and scheduling a variety of tasks, each with unique specifications, to a team comprising multiple humans, each influenced by varied factors, and multiple robots, each with different characteristics.
   
<figure style="text-align: center;">
  <img src="/images/ITA.PNG" style="max-width: 90%; height: auto; display: block; margin: 0 auto;" />
</figure>
<figure style="text-align: center;">
  <img src="/images/ITAENV.gif" style="max-width: 90%; height: auto; display: block; margin: 0 auto;" />
</figure>

   <div style="display: flex; justify-content: center; align-items: center;">
  <figure style="margin: 0 10px; text-align: center;">
    <img src="/images/ITA.PNG" style="max-width: 100%; height: auto;" />
  </figure>
  <figure style="margin: 0 10px; text-align: center;">
    <img src="/images/ITAENV.gif" style="max-width: 100%; height: auto;" />
  </figure>
</div>

- Build multimodal human state recognition models that reason in real-time about the cognitive load and emotional states of human operators using various physiological and behavioral signals.
- Develop affective controllers that enable adaptive task re-allocation and adjustments based on the perceived human states.
   

<div style="display: flex; justify-content: center; align-items: center;">
  <div style="margin-right: 10px;">
    <img src="/images/ahmrs.png" style="max-width: 100%; height: auto; display: block;" />
  </div>
  <div>
    <img src="/images/MHMRENV.PNG" style="max-width: 100%; height: auto; display: block;" />
  </div>
</div>

This project is supported by the National Science Foundation under Grant No. IIS-1846221. Relevant papers:  
- [Initial Task Allocation in Multi-Human Multi-Robot Teams: An Attention-enhanced Hierarchical Reinforcement Learning Approach](https://sites.google.com/view/ita-aehrl), RA-L 2024.
- [MOCAS: A Multimodal Dataset for Objective Cognitive Workload Assessment on Simultaneous Tasks](https://arxiv.org/pdf/2210.03065), IEEE TAFFC 2024.
- [Husformer: A Multi-Modal Transformer for Multi-Modal Human State Recognition](https://ieeexplore.ieee.org/document/10413204), IEEE TCDS 2024.
- [Affective Workload Allocation for Multi-human Multirobot Teams](https://arxiv.org/pdf/2303.10465), ArXiv Pre-print.
- [Initial Task Allocation for Multi-Human Multi-Robot Teams with Attention-based Deep Reinforcement Learning](https://sites.google.com/view/ITA-AtRL), IROS 2023.



## Human-in-the-loop Robot Learning for Personalized Human-Robot Interactions
Human preferences for robot interaction behaviors are inherently diverse and individual. Adapting and personalizing robot behaviors to these individual preferences is crucial, as it can significantly enhance user satisfaction, engagement, and overall interaction quality. This project aims to develop efficient human-in-the-loop robot learning algorithms to facilitate this personalization process. Our primary objective is to develop innovative and transformative frameworks and algorithms that enable seamless robot adaptation in human-robot interaction by efficiently understanding and learning from human feedback and preferences.

<div style="display: flex; justify-content: center; align-items: center;">
  <img src="/images/frame1.gif" style="height: 300px; width: auto; margin-right: 10px;" />
  <img src="/images/User2.gif" style="height: 300px; width: auto;" />
</div>


Relevant papers:  
- [Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation](https://sites.google.com/view/san-fapl), IROS 2022.
- [PrefCLM: Enhancing Preference-based Reinforcement Learning with Crowdsourced Large Language Models](https://prefclm.github.io/), ArXiv Pre-print.



## Socially-aware Robot Navigation
Socially-aware robot navigation (SAN), in which a robot must optimize its trajectory to maintain comfortable and compliant spatial interactions with humans while also reaching its goal without collisions, is a fundamental but challenging task in the context of human-robot interaction. In this project, our work focuses on two main areas: 1) Encoding Complex Social Interactions: We are developing algorithms to better encode and interpret the intricate social dynamics within varied environments. This involves utilizing advanced deep learning techniques to understand human behaviors in different settings, enabling robots to navigate with a deeper awareness of social nuances; and 2) Innovative Teaching Methods for Robots: We are exploring new methods to teach robots that move beyond traditional reinforcement and inverse reinforcement learning. This includes devising intuitive and effective reward systems that more accurately reflect social compliance and exploring alternatives to reduce reliance on human demonstrations.

<div style="text-align: center;">
  <img src="/images/SAN.PNG" style="max-width: 100%; height: auto; display: block; margin: 0 auto;" />
</div>

Relevant papers:  
- [Multi-Robot Cooperative Socially-Aware Navigation using Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2309.15234), ICRA 2024.
- [NaviSTAR: NaviSTAR: Socially Aware Robot Navigation with Hybrid Spatio-Temporal Graph Transformer and Preference Learning](https://arxiv.org/pdf/2304.05979), IROS 2023.
- [Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation](https://sites.google.com/view/san-fapl), IROS 2022.



