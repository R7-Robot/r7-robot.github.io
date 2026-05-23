---
layout: archive
title: "Selected Publications"
permalink: /Publications/
author_profile: true
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
  <symbol id="icon-collab" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="12" cy="5" r="3"/><circle cx="5" cy="19" r="3"/><circle cx="19" cy="19" r="3"/>
    <line x1="12" y1="8" x2="5" y2="16"/><line x1="12" y1="8" x2="19" y2="16"/><line x1="8" y1="19" x2="16" y2="19"/>
  </symbol>
</svg>

<style>
/* ========== Filter Section ========== */
.filter-section {
  background: #fff;
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  padding: 1rem 1.25rem;
  margin-bottom: 1.5rem;
}

.filter-group {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.5rem;
  margin-bottom: 0.6rem;
}

.filter-group:last-child { margin-bottom: 0; }

.filter-label {
  font-size: 0.75rem;
  font-weight: 600;
  color: #6b7280;
  min-width: 55px;
  text-transform: uppercase;
  letter-spacing: 0.03em;
}

.filter-btn {
  padding: 0.35rem 0.75rem;
  font-size: 0.78rem;
  font-weight: 500;
  color: #4b5563;
  background: #f3f4f6;
  border: 1px solid transparent;
  border-radius: 16px;
  cursor: pointer;
  transition: all 0.15s ease;
}

.filter-btn:hover { background: #e5e7eb; }
.filter-btn.active { background: #1f2937; color: #fff; }

.filter-btn[data-theme="team"].active { background: #2563eb; }
.filter-btn[data-theme="state"].active { background: #7c3aed; }
.filter-btn[data-theme="learning"].active { background: #dc2626; }
.filter-btn[data-theme="collab"].active { background: #059669; }

.filter-btn svg { width: 14px; height: 14px; margin-right: 3px; vertical-align: -2px; }

/* Results count */
.results-count { font-size: 0.85rem; color: #6b7280; margin-bottom: 1.25rem; }
.results-count strong { color: #1f2937; }

/* ========== Icon colors ========== */
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

/* ========== Legend ========== */
.pub-legend {
  display: flex;
  flex-wrap: wrap;
  gap: 1.25rem;
  margin-bottom: 1.5rem;
  padding: 1rem 1.25rem;
  background: #f9fafb;
  border-radius: 10px;
  border: 1px solid #e5e5e5;
}

.pub-legend-item { display: flex; align-items: center; gap: 0.5rem; font-size: 0.8rem; color: #555; }
.pub-note { font-size: 0.85rem; color: #555; margin-bottom: 2rem; }

/* ========== Year section ========== */
.year-section { margin-bottom: 2rem; }
.year-section.hidden { display: none; }

.year-header { display: flex; align-items: center; gap: 1rem; margin-bottom: 1rem; }
.year-badge { font-size: 1.5rem; font-weight: 700; color: #1f2937; }
.year-line { flex: 1; height: 2px; background: linear-gradient(90deg, #e5e7eb, transparent); }
.year-count {
  font-size: 0.85rem;
  color: #6b7280;
  background: #f3f4f6;
  padding: 0.25rem 0.75rem;
  border-radius: 12px;
}

/* ========== Publication list ========== */
.pub-list {
  display: flex;
  flex-direction: column;
  gap: 0;
  list-style: none;
  padding: 0;
  margin: 0;
}

/* ========== Publication row (compact, horizontal) ========== */
.pub-card {
  display: flex;
  align-items: center;
  gap: 1.25rem;
  padding: 1rem 0.5rem;
  border-bottom: 1px solid #f0f0f0;
  transition: background-color 0.15s ease;
}

.pub-card:last-child { border-bottom: none; }
.pub-card.hidden { display: none; }
.pub-card:hover { background: #fafbfc; }

/* Thumbnail (left) */
.pub-thumb { flex: 0 0 240px; }

.pub-thumb img {
  width: 100%;
  height: auto;
  border-radius: 6px;
  display: block;
  cursor: zoom-in;
  border: 1px solid #eee;
  transition: transform 0.2s, box-shadow 0.2s;
}

.pub-thumb img:hover {
  transform: scale(1.02);
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.12);
}

/* Body (right) */
.pub-body { flex: 1; min-width: 0; }

.pub-header {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.45rem;
  margin-bottom: 0.4rem;
}

.pub-icons { display: flex; gap: 0.3rem; align-items: center; }

.pub-venue {
  font-size: 0.78rem;
  font-weight: 600;
  color: #b45309;
  background: #fef3c7;
  padding: 0.15rem 0.55rem;
  border-radius: 4px;
}

.pub-oral {
  font-size: 0.68rem;
  font-weight: 700;
  color: #991b1b;
  background: #fee2e2;
  padding: 0.15rem 0.55rem;
  border-radius: 4px;
  text-transform: uppercase;
  letter-spacing: 0.02em;
}

.pub-preprint {
  font-size: 0.78rem;
  font-weight: 600;
  color: #6b7280;
  background: #f3f4f6;
  padding: 0.15rem 0.55rem;
  border-radius: 4px;
}

.pub-title {
  font-size: 1.02rem;
  font-weight: 600;
  line-height: 1.4;
  margin: 0 0 0.3rem;
  color: #1a1a1a;
}

.pub-authors { font-size: 0.86rem; color: #555; margin: 0 0 0.25rem; line-height: 1.5; }
.pub-authors strong { color: #1a1a1a; font-weight: 600; }

.pub-venue-detail { font-size: 0.82rem; color: #666; font-style: italic; margin: 0 0 0.5rem; }

/* Links — inline slash-separated text */
.pub-links { display: flex; flex-wrap: wrap; align-items: center; gap: 0.4rem; }
.pub-links a {
  font-size: 0.82rem;
  color: #2563eb;
  text-decoration: none;
  border: none !important;
  background: none !important;
  padding: 0 !important;
  border-radius: 0 !important;
}
.pub-links a:hover {
  text-decoration: underline;
  background: none !important;
  color: #2563eb !important;
}
.pub-links a:not(:last-child)::after { content: "/"; color: #cbd5e1; margin-left: 0.4rem; }

/* ========== Lightbox ========== */
.lightbox {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0, 0, 0, 0.85);
  z-index: 9999;
  align-items: center;
  justify-content: center;
  cursor: zoom-out;
  padding: 2rem;
}

.lightbox.open { display: flex; }

.lightbox img {
  max-width: 92%;
  max-height: 92%;
  border-radius: 8px;
  box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
}

/* ========== Responsive ========== */
@media (max-width: 600px) {
  .filter-section { padding: 0.85rem; }
  .filter-label { min-width: 100%; margin-bottom: 0.2rem; }
  .pub-legend { padding: 1rem; gap: 0.75rem; }
  .pub-card { flex-direction: column; gap: 0.75rem; padding: 1rem 0; }
  .pub-thumb { flex: 0 0 auto; max-width: 280px; }
}
</style>

<div class="filter-section">
  <div class="filter-group">
    <span class="filter-label">Year</span>
    <button class="filter-btn active" data-filter="year" data-value="all">All</button>
    <button class="filter-btn" data-filter="year" data-value="2025">2025</button>
    <button class="filter-btn" data-filter="year" data-value="2024">2024</button>
    <button class="filter-btn" data-filter="year" data-value="2023">2023</button>
    <button class="filter-btn" data-filter="year" data-value="2022">2022</button>
  </div>

  <div class="filter-group">
    <span class="filter-label">Venue</span>
    <button class="filter-btn active" data-filter="type" data-value="all">All</button>
    <button class="filter-btn" data-filter="type" data-value="journal">Journal</button>
    <button class="filter-btn" data-filter="type" data-value="conference">Conference</button>
  </div>

  <div class="filter-group">
    <span class="filter-label">Theme</span>
    <button class="filter-btn active" data-filter="theme" data-value="all">All</button>
    <button class="filter-btn" data-filter="theme" data-value="learning" data-theme="learning">
      <svg class="pub-icon"><use href="#icon-learning"/></svg>
    </button>
    <button class="filter-btn" data-filter="theme" data-value="state" data-theme="state">
      <svg class="pub-icon"><use href="#icon-state"/></svg>
    </button>
    <button class="filter-btn" data-filter="theme" data-value="team" data-theme="team">
      <svg class="pub-icon"><use href="#icon-team"/></svg>
    </button>
    <button class="filter-btn" data-filter="theme" data-value="collab" data-theme="collab">
      <svg class="pub-icon"><use href="#icon-collab"/></svg>
    </button>
  </div>
</div>

<div class="results-count">
  Showing <strong><span id="visible-count">16</span></strong> of <strong>16</strong> publications
</div>

<div class="pub-legend">
  <div class="pub-legend-item">
    <svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg>
    Robot Learning from Human Feedback
  </div>
  <div class="pub-legend-item">
    <svg class="pub-icon icon-state"><use href="#icon-state"/></svg>
    Human State-Aware Interaction
  </div>
  <div class="pub-legend-item">
    <svg class="pub-icon icon-team"><use href="#icon-team"/></svg>
    Heterogeneity-Aware Human-Robot Teaming
  </div>
  <div class="pub-legend-item">
    <svg class="pub-icon icon-collab"><use href="#icon-collab"/></svg>
    Interdisciplinary Collaboration
  </div>
</div>

<p class="pub-note">†: Equal contribution · §: Work I led</p>


<div class="year-section" data-year="2025">
  <div class="year-header">
    <span class="year-badge">2025</span>
    <div class="year-line"></div>
    <span class="year-count"><span class="year-visible">9</span> papers</span>
  </div>

  <div class="pub-list">

  <article class="pub-card" data-year="2025" data-type="conference" data-themes="learning">
    <div class="pub-thumb"><img src="/images/publications/PRIMT.gif" alt="PRIMT" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg></div>
        <span class="pub-venue">NeurIPS 2025</span>
        <span class="pub-oral">Oral · Top 0.36%</span>
      </div>
      <h3 class="pub-title">PRIMT: Preference-based Reinforcement Learning with Multimodal Feedback and Trajectory Synthesis from Foundation Models</h3>
      <p class="pub-authors"><strong>Ruiqi Wang†</strong>, Dezhong Zhao†, Ziqin Yuan†, Tianyu Shao, Guohua Chen, Dominic Kao, Sungeun Hong, and Byung-Cheol Min.</p>
      <p class="pub-venue-detail">Advances in Neural Information Processing Systems (NeurIPS), San Diego, USA, December 2025.</p>
      <div class="pub-links">
        <a href="https://primt25.github.io/" target="_blank">Website</a>
        <a href="https://arxiv.org/abs/2509.15607" target="_blank">Preprint</a>
        <a href="https://primt25.github.io/" target="_blank">Code</a>
      </div>
    </div>
  </article>

  <article class="pub-card" data-year="2025" data-type="conference" data-themes="learning">
    <div class="pub-thumb"><img src="/images/publications/PrefMMT.png" alt="PrefMMT" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg></div>
        <span class="pub-venue">IROS 2025</span>
      </div>
      <h3 class="pub-title">PrefMMT: Modeling Human Preferences in Preference-based Reinforcement Learning with Multimodal Transformers</h3>
      <p class="pub-authors">Dezhong Zhao†, <strong>Ruiqi Wang†§</strong>, Dayoon Suh, Taehyeon Kim, Ziqin Yuan, Byung-Cheol Min, and Guohua Chen.</p>
      <p class="pub-venue-detail">IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Hangzhou, China, October 2025.</p>
      <div class="pub-links">
        <a href="https://sites.google.com/view/prefmmt/home" target="_blank">Website</a>
        <a href="https://arxiv.org/abs/2409.13683" target="_blank">ArXiv</a>
        <a href="https://www.youtube.com/watch?v=_g1Nl4POPxo" target="_blank">Video</a>
        <a href="https://github.com/SMARTlab-Purdue/PrefMMT" target="_blank">Code</a>
      </div>
    </div>
  </article>

  <article class="pub-card" data-year="2025" data-type="conference" data-themes="team state">
    <div class="pub-thumb"><img src="/images/publications/trust.png" alt="Trust Dynamics" /></div>
    <div class="pub-body">
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

  <article class="pub-card" data-year="2025" data-type="conference" data-themes="learning">
    <div class="pub-thumb"><img src="/images/publications/pbarl.gif" alt="PBARL" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg></div>
        <span class="pub-venue">ICRA 2025</span>
      </div>
      <h3 class="pub-title">Personalization in Human-Robot Interaction through Preference-based Action Representation Learning</h3>
      <p class="pub-authors"><strong>Ruiqi Wang†</strong>, Dezhong Zhao†, Dayoon Suh, Ziqin Yuan, Guohua Chen, and Byung-Cheol Min.</p>
      <p class="pub-venue-detail">IEEE International Conference on Robotics and Automation (ICRA), Atlanta, USA, 19-23 May, 2025.</p>
      <div class="pub-links">
        <a href="https://sites.google.com/view/pbarl/home" target="_blank">Website</a>
        <a href="https://arxiv.org/abs/2409.13822" target="_blank">ArXiv</a>
        <a href="https://youtu.be/LWmmS0uGsCw" target="_blank">Video</a>
      </div>
    </div>
  </article>

  <article class="pub-card" data-year="2025" data-type="conference" data-themes="team state">
    <div class="pub-thumb"><img src="/images/publications/ATA.gif" alt="ATA-HRL" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons">
          <svg class="pub-icon icon-team"><use href="#icon-team"/></svg>
          <svg class="pub-icon icon-state"><use href="#icon-state"/></svg>
        </div>
        <span class="pub-venue">ICRA 2025</span>
      </div>
      <h3 class="pub-title">Adaptive Task Allocation in Multi-Human Multi-Robot Teams under Team Heterogeneity and Dynamic Information Uncertainty</h3>
      <p class="pub-authors">Ziqin Yuan†, <strong>Ruiqi Wang†§</strong>, Taehyeon Kim, Dezhong Zhao, Ike Obi, and Byung-Cheol Min.</p>
      <p class="pub-venue-detail">IEEE International Conference on Robotics and Automation (ICRA), Atlanta, USA, 19-23 May, 2025.</p>
      <div class="pub-links">
        <a href="https://sites.google.com/view/ata-hrl/home" target="_blank">Website</a>
        <a href="https://arxiv.org/abs/2409.13824" target="_blank">ArXiv</a>
        <a href="https://www.youtube.com/watch?v=T5-DcMCpA5Q" target="_blank">Video</a>
      </div>
    </div>
  </article>

  <article class="pub-card" data-year="2025" data-type="journal" data-themes="learning">
    <div class="pub-thumb"><img src="/images/publications/CLM.gif" alt="PrefCLM" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg></div>
        <span class="pub-venue">IEEE RA-L</span>
      </div>
      <h3 class="pub-title">PrefCLM: Enhancing Preference-based Reinforcement Learning with Crowdsourced Large Language Models</h3>
      <p class="pub-authors"><strong>Ruiqi Wang</strong>, Dezhong Zhao, Ziqin Yuan, Ike Obi, and Byung-Cheol Min.</p>
      <p class="pub-venue-detail">IEEE Robotics and Automation Letters, Vol. 10, No. 3, pp. 2486-2493, March 2025.</p>
      <div class="pub-links">
        <a href="https://arxiv.org/abs/2407.08213" target="_blank">Paper</a>
        <a href="https://prefclm.github.io/" target="_blank">Website</a>
        <a href="https://www.youtube.com/watch?v=0vyekC2fqrY" target="_blank">Video</a>
      </div>
    </div>
  </article>

  <article class="pub-card" data-year="2025" data-type="journal" data-themes="state">
    <div class="pub-thumb"><img src="/images/publications/AW.gif" alt="Cognitive Load Allocation" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-state"><use href="#icon-state"/></svg></div>
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

  <article class="pub-card" data-year="2025" data-type="journal" data-themes="collab">
    <div class="pub-thumb"><img src="/images/publications/audformer.png" alt="Audformer" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-collab"><use href="#icon-collab"/></svg></div>
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

  <article class="pub-card" data-year="2025" data-type="journal" data-themes="state">
    <div class="pub-thumb"><img src="/images/publications/mocas.gif" alt="MOCAS" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-state"><use href="#icon-state"/></svg></div>
        <span class="pub-venue">IEEE T-AFFC</span>
      </div>
      <h3 class="pub-title">MOCAS: A Multimodal Dataset for Objective Cognitive Workload Assessment on Simultaneous Tasks</h3>
      <p class="pub-authors">Wonse Jo†, <strong>Ruiqi Wang†</strong>, Go-Eum Cha, Su Sun, Revanth Senthilkumaran, Daniel Foti, and Byung-Cheol Min.</p>
      <p class="pub-venue-detail">IEEE Transactions on Affective Computing, vol. 16, no. 1, pp. 116-132, Jan.-March 2025.</p>
      <div class="pub-links">
        <a href="https://arxiv.org/pdf/2210.03065" target="_blank">Paper</a>
        <a href="https://www.youtube.com/watch?v=BxVVj7R9b70&feature=youtu.be" target="_blank">Video</a>
        <a href="https://zenodo.org/records/10396672" target="_blank">Dataset</a>
      </div>
    </div>
  </article>

  </div>
</div>


<div class="year-section" data-year="2024">
  <div class="year-header">
    <span class="year-badge">2024</span>
    <div class="year-line"></div>
    <span class="year-count"><span class="year-visible">4</span> papers</span>
  </div>
  <div class="pub-list">

  <article class="pub-card" data-year="2024" data-type="preprint" data-themes="team">
    <div class="pub-thumb"><img src="/images/publications/REBEL.png" alt="REBEL" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-team"><use href="#icon-team"/></svg></div>
        <span class="pub-preprint">Preprint</span>
      </div>
      <h3 class="pub-title">REBEL: Rule-based and Experience-enhanced Learning with LLMs for Initial Task Allocation in Multi-Human Multi-Robot Teams</h3>
      <p class="pub-authors">Arjun Gupte†, <strong>Ruiqi Wang†§</strong>, L. N. Vishnunandan Venkatesh, Taehyeon Kim, Dezhong Zhao, and Byung-Cheol Min.</p>
      <p class="pub-venue-detail">Under review.</p>
      <div class="pub-links">
        <a href="https://sites.google.com/view/ita-rebel/home" target="_blank">Website</a>
        <a href="https://arxiv.org/abs/2409.16266" target="_blank">ArXiv</a>
        <a href="https://www.youtube.com/watch?v=HeGPVLd1Bps" target="_blank">Video</a>
      </div>
    </div>
  </article>

  <article class="pub-card" data-year="2024" data-type="journal" data-themes="team">
    <div class="pub-thumb"><img src="/images/publications/aehrl2.gif" alt="ITA-AEHRL" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-team"><use href="#icon-team"/></svg></div>
        <span class="pub-venue">IEEE RA-L</span>
      </div>
      <h3 class="pub-title">Initial Task Allocation in Multi-Human Multi-Robot Teams: An Attention-enhanced Hierarchical Reinforcement Learning Approach</h3>
      <p class="pub-authors"><strong>Ruiqi Wang</strong>, Dezhong Zhao, Arjun Gupte, and Byung-Cheol Min.</p>
      <p class="pub-venue-detail">IEEE Robotics and Automation Letters, vol. 9, no. 4, pp. 3451-3458, April 2024.</p>
      <div class="pub-links">
        <a href="https://ieeexplore.ieee.org/abstract/document/10436714" target="_blank">Paper</a>
        <a href="https://sites.google.com/view/ita-aehrl" target="_blank">Website</a>
        <a href="https://www.youtube.com/watch?v=wMXLYCuktRk" target="_blank">Video</a>
      </div>
    </div>
  </article>

  <article class="pub-card" data-year="2024" data-type="journal" data-themes="state">
    <div class="pub-thumb"><img src="/images/publications/hus.jpg" alt="Husformer" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-state"><use href="#icon-state"/></svg></div>
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

  <article class="pub-card" data-year="2024" data-type="conference" data-themes="team">
    <div class="pub-thumb"><img src="/images/publications/SAMARL.png" alt="SAMARL" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-team"><use href="#icon-team"/></svg></div>
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

  </div>
</div>


<div class="year-section" data-year="2023">
  <div class="year-header">
    <span class="year-badge">2023</span>
    <div class="year-line"></div>
    <span class="year-count"><span class="year-visible">2</span> papers</span>
  </div>

  <div class="pub-list">

  <article class="pub-card" data-year="2023" data-type="conference" data-themes="team">
    <div class="pub-thumb"><img src="/images/ITA.PNG" alt="ITA-AtRL" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-team"><use href="#icon-team"/></svg></div>
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

  <article class="pub-card" data-year="2023" data-type="conference" data-themes="learning">
    <div class="pub-thumb"><img src="/images/publications/Navi.gif" alt="NaviSTAR" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg></div>
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

  </div>
</div>


<div class="year-section" data-year="2022">
  <div class="year-header">
    <span class="year-badge">2022</span>
    <div class="year-line"></div>
    <span class="year-count"><span class="year-visible">1</span> paper</span>
  </div>

  <div class="pub-list">

  <article class="pub-card" data-year="2022" data-type="conference" data-themes="learning">
    <div class="pub-thumb"><img src="/images/publications/FAPL.png" alt="SAN-FAPL" /></div>
    <div class="pub-body">
      <div class="pub-header">
        <div class="pub-icons"><svg class="pub-icon icon-learning"><use href="#icon-learning"/></svg></div>
        <span class="pub-venue">IROS 2022</span>
      </div>
      <h3 class="pub-title">Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation</h3>
      <p class="pub-authors"><strong>Ruiqi Wang</strong>, Weizheng Wang, and Byung-Cheol Min.</p>
      <p class="pub-venue-detail">2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2022), Kyoto, Japan, October 23-27, 2022.</p>
      <div class="pub-links">
        <a href="https://arxiv.org/abs/2201.00469" target="_blank">Paper</a>
        <a href="https://sites.google.com/view/san-fapl" target="_blank">Website</a>
        <a href="https://www.youtube.com/watch?v=ZVb5ZEzDKhM&feature=youtu.be" target="_blank">Video</a>
      </div>
    </div>
  </article>

  </div>
</div>

<script>
(function() {
  const filters = { year: 'all', type: 'all', theme: 'all' };
  const filterBtns = document.querySelectorAll('.filter-btn');
  const pubCards = document.querySelectorAll('.pub-card');
  const yearSections = document.querySelectorAll('.year-section');
  const visibleCountEl = document.getElementById('visible-count');

  filterBtns.forEach(btn => {
    btn.addEventListener('click', function() {
      const filterType = this.dataset.filter;
      const filterValue = this.dataset.value;
      filters[filterType] = filterValue;

      document.querySelectorAll(`[data-filter="${filterType}"]`).forEach(b => b.classList.remove('active'));
      this.classList.add('active');
      applyFilters();
    });
  });

  function applyFilters() {
    let visibleCount = 0;

    pubCards.forEach(card => {
      const yearMatch = filters.year === 'all' || card.dataset.year === filters.year;
      const typeMatch = filters.type === 'all' || card.dataset.type === filters.type;
      const themeMatch = filters.theme === 'all' || (card.dataset.themes || '').includes(filters.theme);

      if (yearMatch && typeMatch && themeMatch) {
        card.classList.remove('hidden');
        visibleCount++;
      } else {
        card.classList.add('hidden');
      }
    });

    visibleCountEl.textContent = visibleCount;

    yearSections.forEach(section => {
      const visibleInSection = section.querySelectorAll('.pub-card:not(.hidden)').length;
      const yearCountEl = section.querySelector('.year-visible');
      if (yearCountEl) yearCountEl.textContent = visibleInSection;
      section.classList.toggle('hidden', visibleInSection === 0);
    });
  }

  // ===== Lightbox: click thumbnail to zoom =====
  const lightbox = document.createElement('div');
  lightbox.id = 'pub-lightbox';
  lightbox.style.cssText = 'display:none;position:fixed;inset:0;width:100%;height:100%;background:rgba(0,0,0,0.85);z-index:99999;align-items:center;justify-content:center;cursor:zoom-out;padding:2rem;box-sizing:border-box;';
  const lightboxImg = document.createElement('img');
  lightboxImg.style.cssText = 'max-width:92%;max-height:92%;border-radius:8px;box-shadow:0 10px 40px rgba(0,0,0,0.5);';
  lightbox.appendChild(lightboxImg);
  document.body.appendChild(lightbox);

  function openLightbox(src) {
    lightboxImg.src = src;
    lightbox.style.display = 'flex';
  }
  function closeLightbox() {
    lightbox.style.display = 'none';
    lightboxImg.src = '';
  }

  document.querySelectorAll('.pub-thumb img').forEach(img => {
    img.style.cursor = 'zoom-in';
    img.addEventListener('click', function() { openLightbox(this.src); });
  });

  lightbox.addEventListener('click', closeLightbox);
  document.addEventListener('keydown', function(e) {
    if (e.key === 'Escape') closeLightbox();
  });
})();
</script>
