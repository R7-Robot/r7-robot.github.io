---
permalink: /
title: "Ruiqi Wang"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- Custom SVG Icons -->
<svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
  <symbol id="icon-team" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="7" cy="5" r="2.5"/><path d="M3 21v-2a4 4 0 0 1 4-4h0a4 4 0 0 1 4 4v2"/>
    <rect x="15" y="3" width="6" height="5" rx="1"/><path d="M18 8v3"/><path d="M15 14h6"/><path d="M16 14v7"/><path d="M20 14v7"/>
  </symbol>
  <symbol id="icon-state" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="12" cy="9" r="5"/><path d="M12 14v3"/><path d="M8 22h8"/>
    <path d="M7 4.5c-1.5 1-2.5 2.5-2.5 4.5"/><path d="M4 3c-2 1.5-3 4-3 6"/>
    <path d="M17 4.5c1.5 1 2.5 2.5 2.5 4.5"/><path d="M20 3c2 1.5 3 4 3 6"/>
  </symbol>
  <symbol id="icon-learning" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="12" cy="12" r="10"/><circle cx="12" cy="12" r="6"/><circle cx="12" cy="12" r="2"/>
    <path d="M12 2v4"/><path d="M12 18v4"/><path d="M2 12h4"/><path d="M18 12h4"/>
  </symbol>
</svg>

<style>
/* Hero Section */
.hero-intro {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #374151;
  margin-bottom: 1.5rem;
}

.hero-intro a {
  color: #2563eb;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s;
}

.hero-intro a:hover {
  border-bottom-color: #2563eb;
}

.highlight-text {
  background: linear-gradient(120deg, #fef3c7 0%, #fde68a 100%);
  padding: 0 4px;
  border-radius: 3px;
}

/* Research Dimensions - Vertical Layout */
.research-dimensions {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin: 1.5rem 0 2rem;
}

.dimension-card {
  background: #fff;
  border: 1px solid #e5e7eb;
  border-left: 4px solid #e5e7eb;
  border-radius: 0 12px 12px 0;
  padding: 1.25rem 1.5rem;
  transition: all 0.2s ease;
}

.dimension-card:hover {
  border-color: #d1d5db;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  transform: translateX(4px);
}

.dimension-card.blue { border-left-color: #2563eb; }
.dimension-card.purple { border-left-color: #7c3aed; }
.dimension-card.red { border-left-color: #dc2626; }

.dimension-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 0.6rem;
}

.dimension-icon {
  width: 26px;
  height: 26px;
  flex-shrink: 0;
}

.dimension-icon.blue { color: #2563eb; }
.dimension-icon.purple { color: #7c3aed; }
.dimension-icon.red { color: #dc2626; }

.dimension-title {
  font-size: 1.05rem;
  font-weight: 600;
  color: #1f2937;
  margin: 0;
}

.dimension-desc {
  font-size: 0.92rem;
  color: #4b5563;
  line-height: 1.6;
  margin: 0;
}

/* Vision statement */
.vision-box {
  background: linear-gradient(135deg, #eff6ff 0%, #f5f3ff 100%);
  border-left: 4px solid #2563eb;
  padding: 1rem 1.25rem;
  border-radius: 0 8px 8px 0;
  margin: 1.5rem 0;
  font-size: 0.95rem;
  color: #374151;
  line-height: 1.6;
  font-style: italic;
}

/* Research Areas Tags */
.research-areas {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin: 1rem 0 2rem;
}

.area-tag {
  background: #f3f4f6;
  color: #374151;
  padding: 0.4rem 0.85rem;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: 500;
  transition: all 0.2s;
}

.area-tag:hover {
  background: #e5e7eb;
}

/* News Section */
.news-section h2 {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  margin-bottom: 1.25rem;
}

.news-year {
  font-size: 0.9rem;
  font-weight: 600;
  color: #6b7280;
  margin: 1.5rem 0 0.75rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e5e7eb;
}

.news-year:first-of-type {
  margin-top: 0;
}

.news-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.news-item {
  display: flex;
  gap: 1rem;
  padding: 0.75rem 0;
  border-bottom: 1px solid #f3f4f6;
}

.news-item:last-child {
  border-bottom: none;
}

.news-date {
  flex-shrink: 0;
  width: 70px;
  font-size: 0.8rem;
  font-weight: 600;
  color: #9ca3af;
}

.news-content {
  font-size: 0.95rem;
  color: #374151;
  line-height: 1.5;
}

.news-content a {
  color: #2563eb;
  text-decoration: none;
}

.news-content a:hover {
  text-decoration: underline;
}

.news-badge {
  display: inline-block;
  background: #fee2e2;
  color: #991b1b;
  font-size: 0.7rem;
  font-weight: 700;
  padding: 0.15rem 0.5rem;
  border-radius: 4px;
  text-transform: uppercase;
  margin-left: 0.25rem;
}

/* Collapsible old news */
.news-toggle {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: #f9fafb;
  border: 1px solid #e5e7eb;
  padding: 0.6rem 1rem;
  border-radius: 8px;
  font-size: 0.9rem;
  color: #6b7280;
  cursor: pointer;
  margin-top: 1rem;
  transition: all 0.2s;
}

.news-toggle:hover {
  background: #f3f4f6;
  color: #374151;
}

.news-old {
  display: none;
}

.news-old.show {
  display: block;
}
</style>

## Hello! 

<p class="hero-intro">
I'm a Ph.D. candidate at Purdue University, where I work in the <a href="http://www.smart-laboratory.org/">Smart Machine And Robotics Technology (SMART) Lab</a> with Professor <a href="http://www.smart-laboratory.org/group/bcm.html">Byung-Cheol Min</a>.
</p>


I am passionate about facilitating the **seamless integration of robots into unstructured, human-centered environments**: from assistive service in homes to collaborative operations in the field.


To this end, my research centers on developing robot learning methods that enable **robots to learn from and adapt to human-centered dynamics** across three key dimensions:

<div class="research-dimensions">
  <div class="dimension-card blue">
    <div class="dimension-header">
      <svg class="dimension-icon blue"><use href="#icon-team"/></svg>
      <h4 class="dimension-title">Capability Heterogeneity</h4>
    </div>
    <p class="dimension-desc">How to optimize human–robot teaming by accounting for inherent yet diverse human capabilities (e.g., cognitive abilities, skill levels, backgrounds) and robot characteristics (e.g., mobility, sensing, autonomy) within specific task contexts?</p>
  </div>
  
  <div class="dimension-card purple">
    <div class="dimension-header">
      <svg class="dimension-icon purple"><use href="#icon-state"/></svg>
      <h4 class="dimension-title">State Uncertainty</h4>
    </div>
    <p class="dimension-desc">How to enable proactive perception and responsiveness to human states (e.g., cognitive load, attention, trust), robot working conditions, and task status that evolve dynamically during operation?</p>
  </div>
  
  <div class="dimension-card red">
    <div class="dimension-header">
      <svg class="dimension-icon red"><use href="#icon-learning"/></svg>
      <h4 class="dimension-title">Preference Variability</h4>
    </div>
    <p class="dimension-desc">How to align robot interactive patterns with individual preferences through continuous, multimodal human feedback?</p>
  </div>
</div>

<div class="vision-box">
Spanning scales from one-to-one human-robot interaction to team-level coordination in multi-human multi-robot teams, my work aims to lay the foundation for a future where robots can naturally understand, adapt to, and collaborate with any human, in any context or situation.
</div>

**My broad areas of research include:**

<div class="research-areas">
  <span class="area-tag">Human-Robot Interaction</span>
  <span class="area-tag">Human-in-the-Loop Reinforcement Learning</span>
  <span class="area-tag">Multi-Human Multi-Robot Teaming</span>
  <span class="area-tag">Foundation Models for Robotics</span>
  <span class="area-tag">Multimodal Perception and Reasoning</span>
</div>

## News

<div class="news-section">

<div class="news-year">2025</div>
<ul class="news-list">
  <li class="news-item">
    <span class="news-date">Sep 18</span>
    <span class="news-content">PRIMT has been accepted as <span class="news-badge">Oral (Top 0.35%)</span> in NeurIPS 2025!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jun 15</span>
    <span class="news-content">Two papers are accepted in IROS 2025!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Feb 10</span>
    <span class="news-content">Our paper "Multimodal Audio-based Disease Prediction with Transformer-based Hierarchical Fusion Network" has been accepted for publication in <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570655">IEEE/ACM Transactions on Audio, Speech, and Language Processing</a>!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jan 27</span>
    <span class="news-content">Three papers (including one RA-L transfer) are accepted in ICRA 2025!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jan 06</span>
    <span class="news-content">Our paper <a href="https://sites.google.com/view/ita-aehrl">"PrefCLM: Enhancing Preference-based Reinforcement Learning with Crowdsourced Large Language Models"</a> has been accepted for publication in <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7083369">IEEE Robotics and Automation Letters</a> (RA-L)!</span>
  </li>
</ul>

<div class="news-year">2024</div>
<ul class="news-list">
  <li class="news-item">
    <span class="news-date">Dec 16</span>
    <span class="news-content">Arjun, an undergraduate I mentored, won <span class="news-badge">First Place</span> at the <a href="https://www.purdue.edu/undergrad-research/conferences/fall/index.php">Purdue University 2024 Fall Undergraduate Research Expo</a>! He presented his outstanding research on <a href="https://sites.google.com/view/ita-rebel">Initial Task Allocation in Multi-Human Multi-Robot Teams</a>.</span>
  </li>
  <li class="news-item">
    <span class="news-date">Dec 13</span>
    <span class="news-content">I passed my Ph.D. dissertation proposal defense!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Nov 26</span>
    <span class="news-content">Our paper <a href="https://sites.google.com/view/affective-workload-allocation/home">"Cognitive Load-based Affective Workload Allocation for Multi-Human Multi-Robot Teams"</a> has been accepted for publication in <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6221037">IEEE Transactions on Human-Machine Systems</a>!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jul 10</span>
    <span class="news-content">Our paper <a href="https://ieeexplore.ieee.org/document/10557131">"MOCAS: A Multimodal Dataset for Objective Cognitive Workload Assessment on Simultaneous Tasks"</a> has been accepted for publication in <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5165369">IEEE Transactions on Affective Computing</a>!</span>
  </li>
  <li class="news-item">
    <span class="news-date">May 02</span>
    <span class="news-content">I passed my Ph.D. preliminary exam! Special thanks to my advisor, my committee members, and my peers in the SMART lab!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Feb 05</span>
    <span class="news-content">Our paper <a href="https://sites.google.com/view/ita-aehrl">"Initial Task Assignment in Multi-Human Multi-Robot Teams: An Attention-enhanced Hierarchical Reinforcement Learning Approach"</a> has been accepted for publication in <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7083369">IEEE Robotics and Automation Letters</a> (RA-L)!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jan 28</span>
    <span class="news-content">Our paper <a href="https://sites.google.com/view/samarl">"SAMARL: Multi Robot Socially-aware Navigation with Multi-agent Reinforcement Learning"</a> has been accepted in <a href="https://2024.ieee-icra.org/">ICRA 2024</a>!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jan 17</span>
    <span class="news-content">Our paper <a href="https://ieeexplore.ieee.org/document/10413204">"Husformer: A Multi-Modal Transformer for Multi-Modal Human State Recognition"</a> has been accepted for publication in <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274989">IEEE Transactions on Cognitive and Developmental Systems</a>! Check out our <a href="https://github.com/SMARTlab-Purdue/Husformer">source code</a> as well!</span>
  </li>
</ul>

<button class="news-toggle" onclick="document.querySelector('.news-old').classList.toggle('show'); this.innerHTML = this.innerHTML.includes('Show') ? '▲ Hide older news' : '▼ Show older news (2022-2023)';">
  ▼ Show older news (2022-2023)
</button>

<div class="news-old">

<div class="news-year">2023</div>
<ul class="news-list">
  <li class="news-item">
    <span class="news-date">Dec 28</span>
    <span class="news-content">Conducted a one-day <a href="https://polytechnic.purdue.edu/ahmrs/outreach/2023-fall-wlhs">robotics seminar</a> at <a href="https://www.wl.k12.in.us/jrsr">West Lafayette Jr./Sr. High School</a> to introduce and explore the realms of cutting-edge research in human-robot interaction, multi-robot systems, and robot design.</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jun 21</span>
    <span class="news-content">Two papers <a href="https://sites.google.com/view/ITA-AtRL">"Initial Task Allocation for Multi-Human Multi-Robot Teams with Attention-based Deep Reinforcement Learning"</a> and <a href="https://sites.google.com/view/san-navistar">"NaviSTAR: Socially Aware Robot Navigation with Hybrid Spatio-Temporal Graph Transformer and Preference Learning"</a> are accepted in <a href="https://ieee-iros.org/">IROS 2023</a>!</span>
  </li>
  <li class="news-item">
    <span class="news-date">May 27</span>
    <span class="news-content">Conducted an exceptional <a href="https://polytechnic.purdue.edu/ahmrs/outreach/2023-spring-wlhs">five-day robotics outreach program</a> at <a href="https://www.wl.k12.in.us/jrsr">West Lafayette Jr./Sr. High School</a> to captivate K-12 students with the intriguing world of robotics, providing them with invaluable hands-on experiences and insights into practical applications!</span>
  </li>
</ul>

<div class="news-year">2022</div>
<ul class="news-list">
  <li class="news-item">
    <span class="news-date">Dec 18</span>
    <span class="news-content">Held a one-day <a href="https://polytechnic.purdue.edu/ahmrs/outreach/2022-fall-macau-anglican-college">outreach event</a> at <a href="https://acm.edu.mo/">Macau Anglican College</a> to provide K-12 students and their teachers with cutting-edge robotic research on Human-in-the-loop Reinforcement Learning and Affective Robotics!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jun 30</span>
    <span class="news-content">Our paper <a href="https://ieeexplore.ieee.org/document/9981616">"Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation"</a> is accepted in <a href="https://iros2022.org/">IROS 2022</a>! Check the <a href="https://sites.google.com/view/san-fapl">Project Website</a> for details.</span>
  </li>
</ul>

</div>

</div>
