---
layout: archive
title: "Selected Publications"
permalink: /Publications/
author_profile: true
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
  <symbol id="icon-collab" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="12" cy="5" r="3"/><circle cx="5" cy="19" r="3"/><circle cx="19" cy="19" r="3"/>
    <line x1="12" y1="8" x2="5" y2="16"/><line x1="12" y1="8" x2="19" y2="16"/><line x1="8" y1="19" x2="16" y2="19"/>
  </symbol>
</svg>

<style>
/* Icon colors */
.pub-icon {
  width: 20px;
  height: 20px;
  display: inline-block;
  vertical-align: middle;
  flex-shrink: 0;
}

.icon-team { color: #2563eb; }
.icon-state { color: #7c3aed; }
.icon-learning { color: #dc2626; }
.icon-collab { color: #059669; }

/* Legend */
.pub-legend {
  display: flex;
  flex-wrap: wrap;
  gap: 1.25rem;
  margin-bottom: 2rem;
  padding: 1.25rem;
  background: #fff;
  border-radius: 12px;
  border: 1px solid #e5e5e5;
}

.pub-legend-item {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-size: 0.875rem;
  color: #555;
}

.pub-note {
  font-size: 0.85rem;
  color: #555;
  margin-bottom: 2rem;
}

/* Publication list */
.pub-list {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  list-style: none;
  padding: 0;
  margin: 0;
}

/* Publication card with image */
.pub-card {
  display: flex;
  gap: 1.25rem;
  background: #fff;
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  padding: 1.25rem;
  transition: all 0.2s ease;
}

.pub-card:hover {
  border-color: #ccc;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.06);
  transform: translateY(-2px);
}

/* Thumbnail */
.pub-thumb {
  flex-shrink: 0;
  width: 140px;
  height: 100px;
  border-radius: 8px;
  overflow: hidden;
  background: #f3f4f6;
  display: flex;
  align-items: center;
  justify-content: center;
}

.pub-thumb img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.3s;
}

.pub-thumb img:hover {
  transform: scale(1.05);
}

/* No image placeholder */
.pub-thumb.placeholder {
  background: linear-gradient(135deg, #f3f4f6 0%, #e5e7eb 100%);
}

.pub-thumb.placeholder svg {
  width: 40px;
  height: 40px;
  color: #9ca3af;
}

/* Content area */
.pub-content {
  flex: 1;
  min-width: 0;
}

.pub-header {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.5rem;
  margin-bottom: 0.5rem;
}

.pub-icons {
  display: flex;
  gap: 0.35rem;
  align-items: center;
}

.pub-venue {
  font-size: 0.8rem;
  font-weight: 600;
  color: #b45309;
  background: #fef3c7;
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
}

.pub-oral {
  font-size: 0.7rem;
  font-weight: 700;
  color: #991b1b;
  background: #fee2e2;
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
  text-transform: uppercase;
  letter-spacing: 0.02em;
}

.pub-title {
  font-size: 1.05rem;
  font-weight: 600;
  line-height: 1.4;
  margin-bottom: 0.4rem;
  color: #1a1a1a;
}

.pub-authors {
  font-size: 0.875rem;
  color: #555;
  margin-bottom: 0.3rem;
}

.pub-authors strong {
  color: #1a1a1a;
  font-weight: 600;
}

.pub-venue-detail {
  font-size: 0.8rem;
  color: #555;
  font-style: italic;
  margin-bottom: 0.6rem;
}

.pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
}

.pub-links a {
  font-size: 0.75rem;
  color: #2563eb;
  text-decoration: none;
  padding: 0.25rem 0.6rem;
  border: 1px solid #2563eb;
  border-radius: 5px;
  transition: all 0.15s ease;
}

.pub-links a:hover {
  background: #2563eb;
  color: white;
}

/* Responsive */
@media (max-width: 600px) {
  .pub-card {
    flex-direction: column;
  }
  
  .pub-thumb {
    width: 100%;
    height: 160px;
  }
  
  .pub-legend {
    padding: 1rem;
    gap: 0.75rem;
  }
}
</style>

<div class="pub-legend">
  <div class="pub-legend-item">
    <svg class="pub-icon icon-team"><use href="#icon-team"/></svg>
    Heterogeneity-Aware Human-Robot Teaming
  </div>
  <div class="pub-legend-item">
    <svg class="pub-icon icon-state"><use href="#icon-state"/></svg>
    Human State-Aware Interaction
  </div>
  <div class="pub-legend-item">
    <svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg>
    Interactive & Value-Aligned Learning
  </div>
  <div class="pub-legend-item">
    <svg class="pub-icon icon-collab"><use href="#icon-collab"/></svg>
    Interdisciplinary Collaboration
  </div>
</div>

<p class="pub-note">†: Equal contribution · §: Mentored student</p>

## Journal Papers

<div class="pub-list">

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/prefclm.png" alt="PrefCLM" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg>
      </div>
      <span class="pub-venue">IEEE RA-L</span>
    </div>
    <h3 class="pub-title">PrefCLM: Enhancing Preference-based Reinforcement Learning with Crowdsourced Large Language Models</h3>
    <p class="pub-authors"><strong>Ruiqi Wang†</strong>, Dezhong Zhao†, Ziqin Yuan, Ike Obi, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">IEEE Robotics and Automation Letters, Vol. 10, No. 3, pp. 2486-2493, March 2025.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2407.08213" target="_blank">Paper</a>
      <a href="https://prefclm.github.io/" target="_blank">Website</a>
      <a href="https://www.youtube.com/watch?v=0vyekC2fqrY" target="_blank">Video</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/thms.png" alt="Cognitive Load Allocation" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-state"><use href="#icon-state"/></svg>
      </div>
      <span class="pub-venue">IEEE T-HMS</span>
    </div>
    <h3 class="pub-title">Cognitive Load-based Affective Workload Allocation for Multi-Human Multi-Robot Teams</h3>
    <p class="pub-authors">Wonse Jo, <strong>Ruiqi Wang</strong>, Baijian Yang, Dan Foti, Mo Rastgaar, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">IEEE Transactions on Human-Machine Systems, Vol. 55, No. 1, pp. 23-36, February 2025.</p>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/document/10816723" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/affective-workload-allocation/home" target="_blank">Website</a>
      <a href="https://www.youtube.com/watch?v=qrmAQqfdLZk" target="_blank">Video</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/audformer.png" alt="Audformer" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-collab"><use href="#icon-collab"/></svg>
      </div>
      <span class="pub-venue">IEEE T-ASLP</span>
    </div>
    <h3 class="pub-title">Multimodal Audio-based Disease Prediction with Transformer-based Hierarchical Fusion Network</h3>
    <p class="pub-authors">Jinjin Cai†, <strong>Ruiqi Wang†</strong>, Dezhong Zhao, Ziqin Yuan, Victoria McKenna, Aaron Friedman, Rachel Foot, Susan Storey, Ryan Boente, Sudip Vhaduri, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">IEEE Transactions on Audio, Speech, and Language Processing, vol. 33, pp. 1170-1182, February 2025.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2410.09289" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/audformer" target="_blank">Website</a>
      <a href="https://github.com/R7-Robot/Mul-Aud" target="_blank">Code</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/ita-aehrl.png" alt="ITA-AEHRL" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-team"><use href="#icon-team"/></svg>
      </div>
      <span class="pub-venue">IEEE RA-L</span>
    </div>
    <h3 class="pub-title">Initial Task Allocation in Multi-Human Multi-Robot Teams: An Attention-enhanced Hierarchical Reinforcement Learning Approach</h3>
    <p class="pub-authors"><strong>Ruiqi Wang†</strong>, Dezhong Zhao†, Arjun Gupte§, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">IEEE Robotics and Automation Letters, vol. 9, no. 4, pp. 3451-3458, April 2024.</p>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/10436714" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/ita-aehrl" target="_blank">Website</a>
      <a href="https://www.youtube.com/watch?v=wMXLYCuktRk" target="_blank">Video</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/husformer.png" alt="Husformer" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-state"><use href="#icon-state"/></svg>
      </div>
      <span class="pub-venue">IEEE T-CDS</span>
    </div>
    <h3 class="pub-title">Husformer: A Multi-Modal Transformer for Multi-Modal Human State Recognition</h3>
    <p class="pub-authors"><strong>Ruiqi Wang†</strong>, Wonse Jo†, Dezhong Zhao, Weizheng Wang, Baijian Yang, Guohua Chen, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">IEEE Transactions on Cognitive and Developmental Systems, Vol. 16, No. 4, pp. 1374-1390, August 2024.</p>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/document/10413204" target="_blank">Paper</a>
      <a href="https://github.com/SMARTlab-Purdue/Husformer" target="_blank">Code</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/mocas.png" alt="MOCAS" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-state"><use href="#icon-state"/></svg>
      </div>
      <span class="pub-venue">IEEE T-AFFC</span>
    </div>
    <h3 class="pub-title">MOCAS: A Multimodal Dataset for Objective Cognitive Workload Assessment on Simultaneous Tasks</h3>
    <p class="pub-authors">Wonse Jo†, <strong>Ruiqi Wang†</strong>, Go-Eum Cha, Su Sun, Revanth Senthilkumaran§, Daniel Foti, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">IEEE Transactions on Affective Computing, Early Access, 2024.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2210.03065" target="_blank">Paper</a>
      <a href="https://www.youtube.com/watch?v=BxVVj7R9b70&feature=youtu.be" target="_blank">Video</a>
      <a href="https://zenodo.org/records/10396672" target="_blank">Dataset</a>
    </div>
  </div>
</article>

</div>

## Conference Papers

<div class="pub-list">

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/primt.gif" alt="PRIMT" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg>
      </div>
      <span class="pub-venue">NeurIPS 2025</span>
      <span class="pub-oral">Oral · Top 0.36%</span>
    </div>
    <h3 class="pub-title">PRIMT: Preference-based Reinforcement Learning with Multimodal Feedback and Trajectory Synthesis from Foundation Models</h3>
    <p class="pub-authors"><strong>Ruiqi Wang†</strong>, Dezhong Zhao†§, Ziqin Yuan†§, Tianyu Shao, Guohua Chen, Dominic Kao, Sungeun Hong, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">Advances in Neural Information Processing Systems (NeurIPS), San Diego, USA, December 2025.</p>
    <div class="pub-links">
      <a href="https://primt25.github.io/" target="_blank">Website</a>
      <a href="https://arxiv.org/abs/2509.15607" target="_blank">Preprint</a>
      <a href="https://primt25.github.io/" target="_blank">Code</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/prefmmt.png" alt="PrefMMT" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg>
      </div>
      <span class="pub-venue">IROS 2025</span>
    </div>
    <h3 class="pub-title">PrefMMT: Modeling Human Preferences in Preference-based Reinforcement Learning with Multimodal Transformers</h3>
    <p class="pub-authors">Dezhong Zhao†§, <strong>Ruiqi Wang†</strong>, Dayoon Suh, Taehyeon Kim, Ziqin Yuan, Byung-Cheol Min, and Guohua Chen.</p>
    <p class="pub-venue-detail">IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Hangzhou, China, October 2025.</p>
    <div class="pub-links">
      <a href="https://sites.google.com/view/prefmmt/home" target="_blank">Website</a>
      <a href="https://arxiv.org/abs/2409.13683" target="_blank">ArXiv</a>
      <a href="https://www.youtube.com/watch?v=_g1Nl4POPxo" target="_blank">Video</a>
      <a href="https://github.com/SMARTlab-Purdue/PrefMMT" target="_blank">Code</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/trust.png" alt="Trust Dynamics" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-team"><use href="#icon-team"/></svg>
        <svg class="pub-icon icon-state"><use href="#icon-state"/></svg>
      </div>
      <span class="pub-venue">IROS 2025</span>
    </div>
    <h3 class="pub-title">Modeling and Evaluating Trust Dynamics in Multi-Human Multi-Robot Task Allocation</h3>
    <p class="pub-authors">Ike Obi, <strong>Ruiqi Wang</strong>, Wonse Jo, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Hangzhou, China, October 2025.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2409.16009" target="_blank">ArXiv</a>
      <a href="https://www.youtube.com/watch?v=75gRdjIpHD4" target="_blank">Video</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/pbarl.png" alt="PBARL" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg>
      </div>
      <span class="pub-venue">ICRA 2025</span>
    </div>
    <h3 class="pub-title">Personalization in Human-Robot Interaction through Preference-based Action Representation Learning</h3>
    <p class="pub-authors"><strong>Ruiqi Wang†</strong>, Dezhong Zhao†, Dayoon Suh§, Ziqin Yuan, Guohua Chen, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">IEEE International Conference on Robotics and Automation (ICRA), Atlanta, USA, 19-23 May, 2025.</p>
    <div class="pub-links">
      <a href="https://sites.google.com/view/pbarl/home" target="_blank">Website</a>
      <a href="https://arxiv.org/abs/2409.13822" target="_blank">ArXiv</a>
      <a href="https://youtu.be/LWmmS0uGsCw" target="_blank">Video</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/ata-hrl.png" alt="ATA-HRL" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-team"><use href="#icon-team"/></svg>
        <svg class="pub-icon icon-state"><use href="#icon-state"/></svg>
      </div>
      <span class="pub-venue">ICRA 2025</span>
    </div>
    <h3 class="pub-title">Adaptive Task Allocation in Multi-Human Multi-Robot Teams under Team Heterogeneity and Dynamic Information Uncertainty</h3>
    <p class="pub-authors">Ziqin Yuan†, <strong>Ruiqi Wang†</strong>, Taehyeon Kim, Dezhong Zhao, Ike Obi, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">IEEE International Conference on Robotics and Automation (ICRA), Atlanta, USA, 19-23 May, 2025.</p>
    <div class="pub-links">
      <a href="https://sites.google.com/view/ata-hrl/home" target="_blank">Website</a>
      <a href="https://arxiv.org/abs/2409.13824" target="_blank">ArXiv</a>
      <a href="https://www.youtube.com/watch?v=T5-DcMCpA5Q" target="_blank">Video</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/samarl.png" alt="SAMARL" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-team"><use href="#icon-team"/></svg>
      </div>
      <span class="pub-venue">ICRA 2024</span>
    </div>
    <h3 class="pub-title">Multi-Robot Cooperative Socially-Aware Navigation using Multi-Agent Reinforcement Learning</h3>
    <p class="pub-authors">Weizheng Wang, Le Mao, <strong>Ruiqi Wang</strong>, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">International Conference on Robotics and Automation (ICRA 2024), Yokohama, Japan, May 13-17, 2024.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2309.15234" target="_blank">Paper</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/ita-atrl.png" alt="ITA-AtRL" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-team"><use href="#icon-team"/></svg>
      </div>
      <span class="pub-venue">IROS 2023</span>
    </div>
    <h3 class="pub-title">Initial Task Allocation for Multi-Human Multi-Robot Teams with Attention-based Deep Reinforcement Learning</h3>
    <p class="pub-authors"><strong>Ruiqi Wang</strong>, Dezhong Zhao, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2023), Detroit, USA, October 1-5, 2023.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2303.02486" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/ITA-AtRL" target="_blank">Website</a>
      <a href="https://www.youtube.com/watch?v=P_3nURWuSnk" target="_blank">Video</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/navistar.png" alt="NaviSTAR" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg>
      </div>
      <span class="pub-venue">IROS 2023</span>
    </div>
    <h3 class="pub-title">NaviSTAR: Socially Aware Robot Navigation with Hybrid Spatio-Temporal Graph Transformer and Preference Learning</h3>
    <p class="pub-authors">Weizheng Wang, <strong>Ruiqi Wang</strong>, Le Mao, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2023), Detroit, USA, October 1-5, 2023.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2304.05979" target="_blank">Paper</a>
      <a href="https://github.com/SMARTlab-Purdue/SAN-NaviSTAR" target="_blank">Code</a>
    </div>
  </div>
</article>

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/san-fapl.png" alt="SAN-FAPL" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg>
      </div>
      <span class="pub-venue">IROS 2022</span>
    </div>
    <h3 class="pub-title">Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation</h3>
    <p class="pub-authors"><strong>Ruiqi Wang</strong>, Weizheng Wang, and Byung-Cheol Min.</p>
    <p class="pub-venue-detail">2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2022), Kyoto, Japan, October 23-27, 2022.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2109.02823" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/san-fapl" target="_blank">Website</a>
      <a href="https://www.youtube.com/watch?v=ZVb5ZEzDKhM&feature=youtu.be" target="_blank">Video</a>
    </div>
  </div>
</article>

</div>

## Pre-prints / Under Review

<div class="pub-list">

<article class="pub-card">
  <div class="pub-thumb">
    <img src="/images/publications/rebel.png" alt="REBEL" />
  </div>
  <div class="pub-content">
    <div class="pub-header">
      <div class="pub-icons">
        <svg class="pub-icon icon-team"><use href="#icon-team"/></svg>
      </div>
    </div>
    <h3 class="pub-title">REBEL: Rule-based and Experience-enhanced Learning with LLMs for Initial Task Allocation in Multi-Human Multi-Robot Teams</h3>
    <p class="pub-authors">Arjun Gupte†§, <strong>Ruiqi Wang†</strong>, L. N. Vishnunandan Venkatesh, Taehyeon Kim, Dezhong Zhao, and Byung-Cheol Min.</p>
    <div class="pub-links">
      <a href="https://sites.google.com/view/ita-rebel/home" target="_blank">Website</a>
      <a href="https://arxiv.org/abs/2409.16266" target="_blank">ArXiv</a>
      <a href="https://www.youtube.com/watch?v=HeGPVLd1Bps" target="_blank">Video</a>
    </div>
  </div>
</article>

</div>
