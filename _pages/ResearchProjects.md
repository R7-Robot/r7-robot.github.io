---
layout: archive
title: "Research Projects"
permalink: /ResearchProjects/
author_profile: true
---

<style>
/* Project Section */
.project-section {
  margin-bottom: 2rem;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  overflow: hidden;
  background: #fff;
}

/* Project Header */
.project-header {
  padding: 1.5rem;
  border-bottom: 1px solid #e5e7eb;
}

.project-title {
  font-size: 1.35rem;
  font-weight: 700;
  color: #1f2937;
  margin: 0 0 0.75rem 0;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.project-icon {
  width: 28px;
  height: 28px;
  flex-shrink: 0;
}

.project-icon.blue { color: #2563eb; }
.project-icon.purple { color: #7c3aed; }
.project-icon.green { color: #059669; }

.project-summary {
  font-size: 0.95rem;
  line-height: 1.65;
  color: #4b5563;
  margin: 0;
}

/* Subproject Accordion */
.subproject-list {
  padding: 0.5rem 1.5rem 1.5rem;
}

.subproject {
  border: 1px solid #e5e7eb;
  border-radius: 8px;
  margin-bottom: 0.75rem;
  overflow: hidden;
  transition: all 0.2s;
}

.subproject:last-child {
  margin-bottom: 0;
}

.subproject:hover {
  border-color: #d1d5db;
}

.subproject[open] {
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
}

.subproject-title {
  padding: 1rem 1.25rem;
  font-size: 1rem;
  font-weight: 600;
  color: #1f2937;
  cursor: pointer;
  list-style: none;
  display: flex;
  align-items: center;
  gap: 0.75rem;
  background: #f9fafb;
  transition: background 0.2s;
}

.subproject-title::-webkit-details-marker {
  display: none;
}

.subproject-title::before {
  content: "";
  width: 4px;
  height: 18px;
  border-radius: 2px;
  flex-shrink: 0;
}

.subproject.blue .subproject-title::before { background: #2563eb; }
.subproject.purple .subproject-title::before { background: #7c3aed; }
.subproject.green .subproject-title::before { background: #059669; }

.subproject-title::after {
  content: "▸";
  margin-left: auto;
  color: #9ca3af;
  transition: transform 0.2s;
}

.subproject[open] .subproject-title::after {
  transform: rotate(90deg);
}

.subproject-title:hover {
  background: #f3f4f6;
}

.subproject-content {
  padding: 1.25rem;
  border-top: 1px solid #e5e7eb;
}

.subproject-desc {
  font-size: 0.95rem;
  color: #4b5563;
  line-height: 1.65;
  margin: 0 0 1.25rem 0;
}

/* Image Gallery */
.project-images {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 1rem;
  margin: 1.25rem 0;
  flex-wrap: wrap;
}

.project-images img {
  max-height: 260px;
  width: auto;
  border-radius: 8px;
  border: 1px solid #e5e7eb;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  transition: transform 0.2s;
}

.project-images img:hover {
  transform: scale(1.02);
}

.project-images.single img {
  max-width: 85%;
  max-height: 300px;
}

/* Paper Links */
.paper-list {
  margin-top: 1.25rem;
}

.paper-label {
  font-size: 0.75rem;
  font-weight: 600;
  color: #6b7280;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  margin-bottom: 0.5rem;
}

.paper-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.paper-link {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
  background: #f3f4f6;
  color: #374151;
  padding: 0.4rem 0.75rem;
  border-radius: 6px;
  font-size: 0.85rem;
  text-decoration: none;
  transition: all 0.2s;
  border: 1px solid transparent;
}

.paper-link:hover {
  background: #e5e7eb;
  border-color: #d1d5db;
  color: #1f2937;
}

.paper-venue {
  font-size: 0.7rem;
  font-weight: 600;
  color: #6b7280;
  background: #fff;
  padding: 0.15rem 0.4rem;
  border-radius: 3px;
}

/* Responsive */
@media (max-width: 768px) {
  .project-header, .subproject-list {
    padding: 1rem;
  }
  
  .project-images {
    flex-direction: column;
  }
  
  .project-images img {
    max-width: 100%;
  }
}
</style>

<!-- SVG Icons -->
<svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
  <symbol id="icon-team" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="7" cy="5" r="2.5"/><path d="M3 21v-2a4 4 0 0 1 4-4h0a4 4 0 0 1 4 4v2"/>
    <rect x="15" y="3" width="6" height="5" rx="1"/><path d="M18 8v3"/><path d="M15 14h6"/><path d="M16 14v7"/><path d="M20 14v7"/>
  </symbol>
  <symbol id="icon-learning" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="12" cy="12" r="10"/><circle cx="12" cy="12" r="6"/><circle cx="12" cy="12" r="2"/>
    <path d="M12 2v4"/><path d="M12 18v4"/><path d="M2 12h4"/><path d="M18 12h4"/>
  </symbol>
  <symbol id="icon-nav" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="12" cy="12" r="10"/>
    <polygon points="16.24 7.76 14.12 14.12 7.76 16.24 9.88 9.88 16.24 7.76"/>
  </symbol>
</svg>


<!-- ==================== PROJECT 1 ==================== -->
<div class="project-section">
  <div class="project-header">
    <h2 class="project-title">
      <svg class="project-icon blue"><use href="#icon-team"/></svg>
      Adaptive Multi-Human Multi-Robot Systems
    </h2>
    <p class="project-summary">
      Multi-human multi-robot (MH-MR) teams are emerging as promising assets for tackling high-stakes and large-scale missions. The simultaneous collaboration of multiple humans and robots with diverse capabilities offers tremendous potential, but also introduces significant coordination challenges. This project focuses on adaptive teaming strategies, human state reasoning, and dynamic adaptation mechanisms.
    </p>
  </div>
  
  <div class="subproject-list">
    <!-- Subproject 1.1 -->
    <details class="subproject blue">
      <summary class="subproject-title">Adaptive Teaming Strategies</summary>
      <div class="subproject-content">
        <p class="subproject-desc">
          Develop advanced Initial Task Allocation (ITA) strategies that account for team heterogeneity during the teaming stage. This involves dynamically initializing task distribution, assigning roles, and defining collaboration patterns by considering the diverse capabilities of both humans and robots under varying task requirements. The objective is to harness this heterogeneity constructively, forming complementary human-robot pairings or chains that optimize overall team performance.
        </p>
        
        <div class="project-images">
          <img src="/images/ITA.PNG" alt="Initial Task Allocation Framework" />
          <img src="/images/ITAENV.gif" alt="ITA Environment Demo" />
        </div>
        
        <div class="paper-list">
          <div class="paper-label">Related Papers</div>
          <div class="paper-links">
            <a href="https://sites.google.com/view/ita-aehrl" class="paper-link" target="_blank">
              Attention-enhanced Hierarchical RL <span class="paper-venue">RA-L '24</span>
            </a>
            <a href="https://sites.google.com/view/ITA-AtRL" class="paper-link" target="_blank">
              Attention-based Deep RL <span class="paper-venue">IROS '23</span>
            </a>
            <a href="https://sites.google.com/view/ita-rebel/home" class="paper-link" target="_blank">
              REBEL: LLM-enhanced Learning <span class="paper-venue">Preprint</span>
            </a>
          </div>
        </div>
      </div>
    </details>

    <!-- Subproject 1.2 -->
    <details class="subproject blue">
      <summary class="subproject-title">Multimodal Human State Reasoning</summary>
      <div class="subproject-content">
        <p class="subproject-desc">
          Investigate the dynamics of human states, including cognitive load and emotion, and develop models that provide real-time assessments using multimodal physiological and behavioral signals.
        </p>
        
        <div class="project-images">
          <img src="/files/mocas.png" alt="MOCAS Dataset" />
          <img src="/files/hus.png" alt="Husformer Architecture" />
        </div>
        
        <div class="paper-list">
          <div class="paper-label">Related Papers</div>
          <div class="paper-links">
            <a href="https://arxiv.org/pdf/2210.03065" class="paper-link" target="_blank">
              MOCAS Dataset <span class="paper-venue">TAFFC '24</span>
            </a>
            <a href="https://ieeexplore.ieee.org/document/10413204" class="paper-link" target="_blank">
              Husformer <span class="paper-venue">TCDS '24</span>
            </a>
          </div>
        </div>
      </div>
    </details>

    <!-- Subproject 1.3 -->
    <details class="subproject blue">
      <summary class="subproject-title">Dynamic Adaptation Mechanisms During Operation</summary>
      <div class="subproject-content">
        <p class="subproject-desc">
          Develop adaptive mechanisms to re-adjust team collaboration patterns and re-allocate tasks within the team according to perceived changes in human states, robot conditions, and evolving task progress.
        </p>
        
        <div class="project-images">
          <img src="/images/ahmrs.png" alt="AHMRS Framework" />
          <img src="/images/MHMRENV.PNG" alt="MH-MR Environment" />
        </div>
        
        <div class="paper-list">
          <div class="paper-label">Related Papers</div>
          <div class="paper-links">
            <a href="https://sites.google.com/view/ata-hrl/home" class="paper-link" target="_blank">
              Adaptive Task Allocation <span class="paper-venue">ICRA '25</span>
            </a>
            <a href="https://sites.google.com/view/affective-workload-allocation/home" class="paper-link" target="_blank">
              Cognitive Load-based Allocation <span class="paper-venue">THMS '25</span>
            </a>
          </div>
        </div>
      </div>
    </details>
  </div>
</div>


<!-- ==================== PROJECT 2 ==================== -->
<div class="project-section">
  <div class="project-header">
    <h2 class="project-title">
      <svg class="project-icon purple"><use href="#icon-learning"/></svg>
      Human-in-the-Loop Robot Learning for Personalized HRI
    </h2>
    <p class="project-summary">
      Individual preferences often transcend measurable factors—people with similar capabilities may still prefer different interaction patterns. This project develops efficient human-in-the-loop, preference-based robot learning algorithms to personalize robot behaviors, enhancing user satisfaction and interaction quality.
    </p>
  </div>
  
  <div class="subproject-list">
    <details class="subproject purple">
      <summary class="subproject-title">Preference-based Robot Learning</summary>
      <div class="subproject-content">
        <p class="subproject-desc">
          We specifically investigate: how to minimize the amount of human feedback required while maximizing learning outcomes; how to accurately model human preferences toward robot behaviors; and how to allow rapid and effective adaptation of robot policies based on preference data.
        </p>
        
        <div class="project-images">
          <img src="/images/frame1.gif" alt="Preference Learning Demo 1" />
          <img src="/images/User2.gif" alt="Preference Learning Demo 2" />
        </div>
        
        <div class="paper-list">
          <div class="paper-label">Related Papers</div>
          <div class="paper-links">
            <a href="https://prefclm.github.io/" class="paper-link" target="_blank">
              PrefCLM <span class="paper-venue">RA-L '25</span>
            </a>
            <a href="https://sites.google.com/view/pbarl/home" class="paper-link" target="_blank">
              Preference-based Action Representation <span class="paper-venue">ICRA '25</span>
            </a>
            <a href="https://sites.google.com/view/prefmmt/home" class="paper-link" target="_blank">
              PrefMMT <span class="paper-venue">IROS '25</span>
            </a>
            <a href="https://sites.google.com/view/san-fapl" class="paper-link" target="_blank">
              Feedback-efficient Preference Learning <span class="paper-venue">IROS '22</span>
            </a>
          </div>
        </div>
      </div>
    </details>
  </div>
</div>


<!-- ==================== PROJECT 3 ==================== -->
<div class="project-section">
  <div class="project-header">
    <h2 class="project-title">
      <svg class="project-icon green"><use href="#icon-nav"/></svg>
      Socially-Aware Robot Navigation
    </h2>
    <p class="project-summary">
      Socially-aware robot navigation (SAN) involves optimizing a robot's trajectory to maintain comfortable spatial interactions with humans while efficiently reaching its goal. This requires balancing safety, efficiency, and social etiquette in varied environments.
    </p>
  </div>
  
  <div class="subproject-list">
    <details class="subproject green">
      <summary class="subproject-title">Modeling Complex Social Interactions</summary>
      <div class="subproject-content">
        <p class="subproject-desc">
          Our work focuses on developing algorithms that better encode and interpret the intricate social dynamics across humans and robots within varied environments. This involves leveraging advanced deep learning techniques to understand human behaviors in diverse settings, enabling robots to navigate with a deeper awareness of social nuances.
        </p>
        
        <div class="project-images single">
          <img src="/images/SAN2.PNG" alt="Socially-Aware Robot Navigation" />
        </div>
        
        <div class="paper-list">
          <div class="paper-label">Related Papers</div>
          <div class="paper-links">
            <a href="https://arxiv.org/abs/2309.15234" class="paper-link" target="_blank">
              Multi-Robot Cooperative SAN <span class="paper-venue">ICRA '24</span>
            </a>
            <a href="https://arxiv.org/pdf/2304.05979" class="paper-link" target="_blank">
              NaviSTAR <span class="paper-venue">IROS '23</span>
            </a>
            <a href="https://sites.google.com/view/san-fapl" class="paper-link" target="_blank">
              Feedback-efficient Preference Learning <span class="paper-venue">IROS '22</span>
            </a>
          </div>
        </div>
      </div>
    </details>
  </div>
</div>
