---
permalink: /
title: "Ruiqi Wang"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

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
  <symbol id="icon-speaker" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"></polygon>
    <path d="M19.07 4.93a10 10 0 0 1 0 14.14M15.54 8.46a5 5 0 0 1 0 7.07"></path>
  </symbol>
  <symbol id="icon-download" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/>
  </symbol>
  <symbol id="icon-file" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/><polyline points="10 9 9 9 8 9"/>
  </symbol>
</svg>

<style>
/* Pronunciation - Simplified subtle style */
.name-pronunciation {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  color: #6b7280;
  font-size: 0.9rem;
  font-weight: 400;
  margin-top: -0.75rem;
  margin-bottom: 2rem;
  display: flex;
  align-items: center;
  gap: 0.4rem;
  opacity: 0.85;
  transition: opacity 0.2s ease;
}

.name-pronunciation:hover {
  opacity: 1;
}

.pronounce-icon {
  width: 16px;
  height: 16px;
  color: #9ca3af;
  flex-shrink: 0;
}

.name-pronunciation span {
  font-size: 0.9rem;
  color: #6b7280;
  font-weight: 400;
  letter-spacing: 0.02em;
}

/* Elegant Button Container */
.hero-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 0.875rem;
  margin-bottom: 2.5rem;
  margin-top: 1.75rem;
}

/* Premium Light Blue Gradient Buttons */
.action-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.6rem;
  padding: 0.875rem 1.5rem;
  border-radius: 10px;
  text-decoration: none !important;
  font-weight: 600;
  font-size: 0.94rem;
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  border: none;
  position: relative;
  overflow: hidden;
  color: white !important;
}

.action-btn::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.25), transparent);
  transition: left 0.5s;
}

.action-btn:hover::before {
  left: 100%;
}

.action-btn svg {
  width: 19px;
  height: 19px;
  transition: transform 0.3s ease;
}

.action-btn:hover svg {
  transform: scale(1.1) rotate(-5deg);
}

/* CV Button - Premium Medium Blue */
.btn-primary {
  background: linear-gradient(135deg, #60a5fa 0%, #3b82f6 50%, #2563eb 100%);
  box-shadow: 0 4px 14px rgba(59, 130, 246, 0.25);
}

.btn-primary:hover {
  background: linear-gradient(135deg, #3b82f6 0%, #2563eb 50%, #1d4ed8 100%);
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(59, 130, 246, 0.35);
}

/* Research Statement Button - Lighter Blue */
.btn-secondary {
  background: linear-gradient(135deg, #93c5fd 0%, #60a5fa 50%, #3b82f6 100%);
  box-shadow: 0 4px 14px rgba(96, 165, 250, 0.25);
}

.btn-secondary:hover {
  background: linear-gradient(135deg, #60a5fa 0%, #3b82f6 50%, #2563eb 100%);
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(96, 165, 250, 0.35);
}

/* Hero Section */
.hero-intro {
  font-size: 1.08rem;
  line-height: 1.75;
  color: #374151;
  margin-bottom: 1.25rem;
}

.hero-intro a {
  color: #2563eb;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s;
  font-weight: 500;
}

.hero-intro a:hover {
  border-bottom-color: #2563eb;
}

/* Research goal highlight */
.hero-intro + p {
  font-size: 1.05rem;
  line-height: 1.7;
  margin-bottom: 1.25rem;
}

/* Research Dimensions - Vertical Layout */
.research-dimensions {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin: 1.75rem 0 2.25rem;
}

.dimension-card {
  background: #fff;
  border: 1px solid #e5e7eb;
  border-left: 3px solid #e5e7eb;
  border-radius: 0 10px 10px 0;
  padding: 1.2rem 1.4rem;
  transition: all 0.25s ease;
}

.dimension-card:hover {
  border-color: #d1d5db;
  box-shadow: 0 3px 10px rgba(0,0,0,0.06);
  transform: translateX(3px);
}

.dimension-card.blue { border-left-color: #2563eb; }
.dimension-card.purple { border-left-color: #7c3aed; }
.dimension-card.red { border-left-color: #dc2626; }

.dimension-header {
  display: flex;
  align-items: center;
  gap: 0.7rem;
  margin-bottom: 0.65rem;
}

.dimension-icon {
  width: 24px;
  height: 24px;
  flex-shrink: 0;
}

.dimension-icon.blue { color: #2563eb; }
.dimension-icon.purple { color: #7c3aed; }
.dimension-icon.red { color: #dc2626; }

.dimension-title {
  font-size: 1.02rem;
  font-weight: 600;
  color: #1f2937;
  margin: 0;
  letter-spacing: -0.01em;
}

.dimension-desc {
  font-size: 0.93rem;
  color: #4b5563;
  line-height: 1.65;
  margin: 0;
}

/* Research Areas Tags */
.research-areas {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  margin: 1.25rem 0 2.5rem;
}

.area-tag {
  background: #f3f4f6;
  color: #374151;
  padding: 0.45rem 0.9rem;
  border-radius: 18px;
  font-size: 0.86rem;
  font-weight: 500;
  transition: all 0.2s;
  border: 1px solid transparent;
}

.area-tag:hover {
  background: #e5e7eb;
  border-color: #d1d5db;
  transform: translateY(-1px);
}

/* News Section */
.news-section h2 {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  margin-bottom: 1.5rem;
  margin-top: 2.5rem;
}

.news-year {
  font-size: 0.95rem;
  font-weight: 700;
  color: #6b7280;
  margin: 1.75rem 0 0.85rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e5e7eb;
  letter-spacing: 0.02em;
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
  gap: 1.1rem;
  padding: 0.8rem 0;
  border-bottom: 1px solid #f3f4f6;
  transition: background-color 0.2s;
}

.news-item:hover {
  background-color: #fafbfc;
  margin-left: -0.5rem;
  margin-right: -0.5rem;
  padding-left: 0.5rem;
  padding-right: 0.5rem;
  border-radius: 6px;
}

.news-item:last-child {
  border-bottom: none;
}

.news-date {
  flex-shrink: 0;
  width: 68px;
  font-size: 0.82rem;
  font-weight: 600;
  color: #9ca3af;
  padding-top: 0.1rem;
}

.news-content {
  font-size: 0.95rem;
  color: #374151;
  line-height: 1.6;
}

.news-content a {
  color: #2563eb;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s;
}

.news-content a:hover {
  border-bottom-color: #2563eb;
}

.news-badge {
  display: inline-block;
  background: #fee2e2;
  color: #991b1b;
  font-size: 0.7rem;
  font-weight: 700;
  padding: 0.2rem 0.5rem;
  border-radius: 4px;
  text-transform: uppercase;
  margin-left: 0.3rem;
  vertical-align: baseline;
  line-height: 1;
}

/* Collapsible old news */
.news-toggle {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: #f9fafb;
  border: 1px solid #e5e7eb;
  padding: 0.65rem 1.1rem;
  border-radius: 8px;
  font-size: 0.88rem;
  color: #6b7280;
  cursor: pointer;
  margin-top: 1.25rem;
  transition: all 0.2s;
  font-weight: 500;
}

.news-toggle:hover {
  background: #f3f4f6;
  color: #374151;
  border-color: #d1d5db;
}

.news-old {
  display: none;
  margin-top: 0.5rem;
}

.news-old.show {
  display: block;
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero-intro {
    font-size: 1.05rem;
  }
  
  .dimension-card {
    padding: 1.1rem 1.2rem;
  }
  
  .dimension-title {
    font-size: 0.98rem;
  }
  
  .dimension-desc {
    font-size: 0.91rem;
  }
  
  .news-item {
    gap: 0.9rem;
  }
  
  .news-date {
    width: 62px;
    font-size: 0.8rem;
  }
  
  .news-content {
    font-size: 0.93rem;
  }
}

@media (max-width: 640px) {
  .hero-buttons {
    flex-direction: column;
  }
  
  .action-btn {
    justify-content: center;
    width: 100%;
  }
  
  .name-pronunciation {
    font-size: 0.85rem;
  }
  
  .research-areas {
    gap: 0.5rem;
  }
  
  .area-tag {
    font-size: 0.82rem;
    padding: 0.4rem 0.8rem;
  }
  
  .news-item {
    flex-direction: column;
    gap: 0.3rem;
  }
  
  .news-date {
    width: auto;
    padding-top: 0;
  }
}
</style>

<div class="name-pronunciation">
  <svg class="pronounce-icon"><use href="#icon-speaker"/></svg>
  <span>/ Ray-chee Wong /</span>
</div>

## Hello! 

<p class="hero-intro">
I'm a Ph.D. candidate at Purdue University, where I work in the <a href="http://www.smart-laboratory.org/">Smart Machine And Robotics Technology (SMART) Lab</a> with Professor <a href="http://www.smart-laboratory.org/group/bcm.html">B.C. Min</a>.
</p>

My research goal is to facilitate the **seamless integration of robots into unstructured, human-centered environments**: from assistive service in homes to collaborative operations in the field.

To this end, my research centers on developing data-driven and interactive learning methods that enable **robots to learn from and adapt to human-centered dynamics** across three key dimensions:

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

Spanning scales from one-to-one human-robot interaction to team-level coordination in multi-human multi-robot teams, my work aims to lay the foundation for a future where robots can naturally understand, adapt to, and collaborate with any human, in any context or situation.

<div class="hero-buttons">
  <a href="/files/Ruiqi_Wang_CV.pdf" target="_blank" class="action-btn btn-primary">
    <svg><use href="#icon-download"/></svg> Curriculum Vitae
  </a>
  <a href="/files/Research_Statement.pdf" target="_blank" class="action-btn btn-secondary">
    <svg><use href="#icon-file"/></svg> Research Statement
  </a>
</div>

**Research Areas:**

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
    <span class="news-content">PRIMT accepted as <span class="news-badge">Oral (Top 0.35%)</span> at NeurIPS 2025!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jun 15</span>
    <span class="news-content">Two papers accepted at <a href="#">IROS 2025</a>!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Feb 10</span>
    <span class="news-content">Paper on <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570655">Multimodal Audio-based Disease Prediction</a> accepted at IEEE/ACM T-ASLP!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jan 27</span>
    <span class="news-content">Three papers (including one RA-L transfer) accepted at <a href="#">ICRA 2025</a>!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jan 06</span>
    <span class="news-content"><a href="https://sites.google.com/view/ita-aehrl">PrefCLM</a> accepted at IEEE Robotics and Automation Letters!</span>
  </li>
</ul>

<div class="news-year">2024</div>
<ul class="news-list">
  <li class="news-item">
    <span class="news-date">Dec 16</span>
    <span class="news-content">Arjun (mentored undergrad) won <span class="news-badge">First Place</span> at <a href="https://www.purdue.edu/undergrad-research/conferences/fall/index.php">Purdue Fall Undergraduate Research Expo</a>!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Dec 13</span>
    <span class="news-content">Passed my Ph.D. dissertation proposal defense! 🎉</span>
  </li>
  <li class="news-item">
    <span class="news-date">Nov 26</span>
    <span class="news-content"><a href="https://sites.google.com/view/affective-workload-allocation/home">Cognitive Load-based Affective Workload Allocation</a> accepted at IEEE T-HMS!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jul 10</span>
    <span class="news-content"><a href="https://ieeexplore.ieee.org/document/10557131">MOCAS Dataset</a> accepted at IEEE Transactions on Affective Computing!</span>
  </li>
  <li class="news-item">
    <span class="news-date">May 02</span>
    <span class="news-content">Passed my Ph.D. preliminary exam!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Feb 05</span>
    <span class="news-content"><a href="https://sites.google.com/view/ita-aehrl">Attention-enhanced Hierarchical RL for Task Assignment</a> accepted at IEEE RA-L!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jan 28</span>
    <span class="news-content"><a href="https://sites.google.com/view/samarl">SAMARL</a> accepted at ICRA 2024!</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jan 17</span>
    <span class="news-content"><a href="https://ieeexplore.ieee.org/document/10413204">Husformer</a> accepted at IEEE T-CDS! <a href="https://github.com/SMARTlab-Purdue/Husformer">[Code]</a></span>
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
    <span class="news-content">Conducted <a href="https://polytechnic.purdue.edu/ahmrs/outreach/2023-fall-wlhs">robotics seminar</a> at West Lafayette Jr./Sr. High School.</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jun 21</span>
    <span class="news-content">Two papers accepted at <a href="https://ieee-iros.org/">IROS 2023</a>: <a href="https://sites.google.com/view/ITA-AtRL">ITA-AtRL</a> and <a href="https://sites.google.com/view/san-navistar">NaviSTAR</a>!</span>
  </li>
  <li class="news-item">
    <span class="news-date">May 27</span>
    <span class="news-content">Conducted <a href="https://polytechnic.purdue.edu/ahmrs/outreach/2023-spring-wlhs">five-day robotics outreach program</a> for K-12 students.</span>
  </li>
</ul>

<div class="news-year">2022</div>
<ul class="news-list">
  <li class="news-item">
    <span class="news-date">Dec 18</span>
    <span class="news-content">Held <a href="https://polytechnic.purdue.edu/ahmrs/outreach/2022-fall-macau-anglican-college">outreach event</a> at Macau Anglican College.</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jun 30</span>
    <span class="news-content"><a href="https://sites.google.com/view/san-fapl">Feedback-efficient Active Preference Learning</a> accepted at IROS 2022!</span>
  </li>
</ul>

</div>

</div>
