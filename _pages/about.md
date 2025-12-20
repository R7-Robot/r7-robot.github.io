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
  font-size: 1.15rem;
  line-height: 1.7;
  color: #374151;
  margin-bottom: 2rem;
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

/* Research Dimensions Cards */
.research-dimensions {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1rem;
  margin: 1.5rem 0 2rem;
}

.dimension-card {
  background: #fff;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 1.25rem;
  transition: all 0.2s ease;
}

.dimension-card:hover {
  border-color: #d1d5db;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  transform: translateY(-2px);
}

.dimension-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 0.75rem;
}

.dimension-icon {
  width: 28px;
  height: 28px;
  flex-shrink: 0;
}

.dimension-icon.blue { color: #2563eb; }
.dimension-icon.purple { color: #7c3aed; }
.dimension-icon.red { color: #dc2626; }

.dimension-title {
  font-size: 1rem;
  font-weight: 600;
  color: #1f2937;
  margin: 0;
}

.dimension-desc {
  font-size: 0.9rem;
  color: #6b7280;
  line-height: 1.5;
  margin: 0;
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
</style>

## Hello! 

<p class="hero-intro">
I'm a Ph.D. candidate at Purdue University, where I work in the <a href="http://www.smart-laboratory.org/">Smart Machine And Robotics Technology (SMART) Lab</a> with Professor <a href="http://www.smart-laboratory.org/group/bcm.html">Byung-Cheol Min</a>.
</p>

<p class="hero-intro">
I am passionate about facilitating the <span class="highlight-text">seamless integration of robots into unstructured, human-centered environments</span>: from assistive service in homes to collaborative operations in the field.
</p>

My research centers on developing robot learning methods that enable **robots to learn from and adapt to human-centered dynamics** across three key dimensions:

<div class="research-dimensions">
  <div class="dimension-card">
    <div class="dimension-header">
      <svg class="dimension-icon blue"><use href="#icon-team"/></svg>
      <h4 class="dimension-title">Capability Heterogeneity</h4>
    </div>
    <p class="dimension-desc">Optimizing human–robot teaming by accounting for diverse human capabilities and robot characteristics within specific task contexts.</p>
  </div>
  
  <div class="dimension-card">
    <div class="dimension-header">
      <svg class="dimension-icon purple"><use href="#icon-state"/></svg>
      <h4 class="dimension-title">State Uncertainty</h4>
    </div>
    <p class="dimension-desc">Enabling proactive perception and responsiveness to human states, robot conditions, and task status that evolve dynamically.</p>
  </div>
  
  <div class="dimension-card">
    <div class="dimension-header">
      <svg class="dimension-icon red"><use href="#icon-learning"/></svg>
      <h4 class="dimension-title">Preference Variability</h4>
    </div>
    <p class="dimension-desc">Aligning robot interactive patterns with individual preferences through continuous, multimodal human feedback.</p>
  </div>
</div>

<div class="vision-box">
Spanning scales from one-to-one human-robot interaction to team-level coordination in multi-human multi-robot teams, my work aims to lay the foundation for a future where robots can naturally understand, adapt to, and collaborate with any human, in any context.
</div>

**Research Areas:**

<div class="research-areas">
  <span class="area-tag">Human-Robot Interaction</span>
  <span class="area-tag">Human-in-the-Loop RL</span>
  <span class="area-tag">Multi-Human Multi-Robot Teaming</span>
  <span class="area-tag">Foundation Models for Robotics</span>
  <span class="area-tag">Multimodal Perception</span>
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
