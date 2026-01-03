---
layout: archive
title: "Service"
permalink: /Service/
author_profile: true
---

<svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
  <symbol id="icon-journal" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"/><path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"/></symbol>
  <symbol id="icon-users" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></symbol>
  <symbol id="icon-teach" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></symbol>
  <symbol id="icon-outreach" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"/><path d="M19.07 4.93a10 10 0 0 1 0 14.14M15.54 8.46a5 5 0 0 1 0 7.07"/></symbol>
  
  <symbol id="icon-star" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></symbol>
  <symbol id="icon-next" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="9 18 15 12 9 6"/></symbol>
  <symbol id="icon-link" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></symbol>
  <symbol id="icon-check" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></symbol>
</svg>

<style>
  /* Section Headers */
  h2 {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    font-size: 1.5rem;
    border-bottom: 2px solid #f3f4f6;
    padding-bottom: 0.5rem;
    margin-top: 2.5rem;
    margin-bottom: 1.5rem;
    color: #1f2937;
  }
  
  h2 svg {
    width: 24px;
    height: 24px;
    color: #2563eb;
  }
  
  h3 {
    font-size: 1.1rem;
    color: #4b5563;
    margin-bottom: 1rem;
    font-weight: 600;
  }

  /* --- Review Section: Pills --- */
  .review-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
  }
  
  .review-list {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
  }
  
  .review-pill {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    background: #f9fafb;
    border: 1px solid #e5e7eb;
    padding: 0.4rem 0.8rem;
    border-radius: 6px;
    font-size: 0.85rem;
    color: #374151;
    text-decoration: none !important;
    transition: all 0.2s;
  }
  
  .review-pill:hover {
    background: #fff;
    border-color: #2563eb;
    color: #2563eb;
    transform: translateY(-1px);
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }
  
  .review-pill svg {
    width: 14px;
    height: 14px;
    opacity: 0.6;
  }

  /* --- Mentoring Section: Student Cards --- */
  .student-card {
    background: #fff;
    border: 1px solid #e5e7eb;
    border-left: 4px solid #2563eb;
    border-radius: 8px;
    padding: 1.25rem;
    margin-bottom: 1rem;
    transition: box-shadow 0.2s;
  }
  
  .student-card:hover {
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
  }

  .student-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 0.5rem;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  
  .student-name {
    font-size: 1.1rem;
    font-weight: 700;
  }
  
  .student-name a {
    color: #111827;
    text-decoration: none;
    border-bottom: 1px solid transparent;
  }
  
  .student-name a:hover {
    color: #2563eb;
    border-bottom-color: #2563eb;
  }
  
  .student-period {
    font-size: 0.85rem;
    color: #6b7280;
    font-family: monospace;
    background: #f3f4f6;
    padding: 2px 6px;
    border-radius: 4px;
  }

  .student-detail {
    font-size: 0.9rem;
    color: #4b5563;
    margin-bottom: 0.4rem;
    display: flex;
    align-items: flex-start;
    gap: 0.5rem;
  }
  
  .student-detail svg {
    width: 16px;
    height: 16px;
    margin-top: 3px;
    flex-shrink: 0;
  }
  
  .icon-star { color: #d97706; } /* Gold */
  .icon-next { color: #059669; } /* Green */

  /* --- Teaching Section: Course Cards --- */
  .course-card {
    background: #fff;
    border: 1px solid #e5e7eb;
    border-radius: 8px;
    padding: 1rem 1.25rem;
    margin-bottom: 0.75rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 1rem;
  }

  .course-info {
    flex: 1;
  }

  .course-code {
    font-size: 1.05rem;
    font-weight: 700;
    color: #1f2937;
    margin-bottom: 0.2rem;
  }

  .course-meta {
    font-size: 0.85rem;
    color: #6b7280;
  }

  .course-stats {
    text-align: right;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    gap: 0.3rem;
  }

  .stat-badge {
    background: #ecfdf5;
    color: #047857;
    font-size: 0.8rem;
    font-weight: 600;
    padding: 0.25rem 0.6rem;
    border-radius: 12px;
    border: 1px solid #a7f3d0;
    white-space: nowrap;
  }
  
  .role-badge {
    font-size: 0.7rem;
    text-transform: uppercase;
    font-weight: 700;
    letter-spacing: 0.05em;
    padding: 2px 6px;
    border-radius: 4px;
  }
  
  .role-instructor { background: #fee2e2; color: #991b1b; }
  .role-ta { background: #eff6ff; color: #1e40af; }

  /* --- Outreach Section: Timeline --- */
  .outreach-item {
    display: flex;
    gap: 1.25rem;
    margin-bottom: 1.5rem;
  }
  
  .outreach-date {
    flex-shrink: 0;
    width: 85px;
    text-align: right;
  }
  
  .date-box {
    display: inline-block;
    background: #f3f4f6;
    padding: 0.3rem 0.6rem;
    border-radius: 6px;
    font-size: 0.8rem;
    font-weight: 600;
    color: #4b5563;
  }
  
  .outreach-content {
    padding-top: 0.2rem;
  }
  
  .outreach-title {
    font-size: 0.95rem;
    font-weight: 700;
    color: #1f2937;
    margin-bottom: 0.25rem;
  }
  
  .outreach-desc {
    font-size: 0.9rem;
    color: #4b5563;
  }

  /* Responsive Mobile */
  @media (max-width: 600px) {
    .review-grid { grid-template-columns: 1fr; }
    .course-card { flex-direction: column; align-items: flex-start; gap: 0.5rem; }
    .course-stats { flex-direction: row; align-items: center; width: 100%; justify-content: space-between; margin-top: 0.5rem; }
  }
</style>

<h2><svg><use href="#icon-journal"/></svg> Reviews</h2>

<div class="review-grid">
  <div>
    <h3>Journal Reviewer</h3>
    <div class="review-list">
      <a href="https://www.ieee-ras.org/publications/ra-l" class="review-pill" target="_blank">IEEE RA-L <svg><use href="#icon-link"/></svg></a>
      <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570655" class="review-pill" target="_blank">IEEE T-ASLP <svg><use href="#icon-link"/></svg></a>
      <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570650" class="review-pill" target="_blank">IEEE T-CSS <svg><use href="#icon-link"/></svg></a>
      <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6221037" class="review-pill" target="_blank">IEEE T-HMS <svg><use href="#icon-link"/></svg></a>
      <a href="https://www.nature.com/srep/" class="review-pill" target="_blank">Nature Scientific Reports <svg><use href="#icon-link"/></svg></a>
      <a href="https://link.springer.com/journal/11227" class="review-pill" target="_blank">Journal of Supercomputing <svg><use href="#icon-link"/></svg></a>
    </div>
  </div>
  
  <div>
    <h3>Conference Reviewer</h3>
    <div class="review-list">
      <a href="https://iros2025.org/" class="review-pill" target="_blank">IROS 2023, 2025 <svg><use href="#icon-link"/></svg></a>
      <a href="https://2025.ieee-icra.org/" class="review-pill" target="_blank">ICRA 2024, 2025 <svg><use href="#icon-link"/></svg></a>
      <a href="https://www.biorob2024.org/" class="review-pill" target="_blank">BioRob 2024 <svg><use href="#icon-link"/></svg></a>
      <a href="https://www.tahri.org/" class="review-pill" target="_blank">TAHRI 2024 <svg><use href="#icon-link"/></svg></a>
    </div>
  </div>
</div>

<h2><svg><use href="#icon-users"/></svg> Mentoring</h2>

<div class="student-card">
  <div class="student-header">
    <span class="student-name"><a href="http://www.smart-laboratory.org/group/Arjun_Gupte.html" target="_blank">Arjun Gupte</a></span>
    <span class="student-period">Spring 2023 – Present</span>
  </div>
  <div class="student-detail">
    <span>B.S., Computer Engineering, Purdue University</span>
  </div>
  <div class="student-detail">
    <svg class="icon-star"><use href="#icon-star"/></svg>
    <span><strong>Honors:</strong> 2025 Class of Astronaut Scholarship; First Place, Oral Presentation, 2024 Fall Purdue Undergraduate Research Conference</span>
  </div>
</div>

<div class="student-card">
  <div class="student-header">
    <span class="student-name"><a href="http://www.smart-laboratory.org/group/Dayoon_Suh.html" target="_blank">Dayoon Suh</a></span>
    <span class="student-period">Fall 2024 – Spring 2025</span>
  </div>
  <div class="student-detail">
    <span>B.S., Data Science & Applied Statistics, Purdue University</span>
  </div>
  <div class="student-detail">
    <svg class="icon-star"><use href="#icon-star"/></svg>
    <span><strong>Honors:</strong> Mary-Ann Neel Computer Science Scholarship (2024)</span>
  </div>
  <div class="student-detail">
    <svg class="icon-next"><use href="#icon-next"/></svg>
    <span><strong>Next Position:</strong> M.S.E. in Robotics, University of Pennsylvania</span>
  </div>
</div>

<div class="student-card">
  <div class="student-header">
    <span class="student-name"><a href="http://www.smart-laboratory.org/group/Revanth_Krishna_Senthilkumaran.html" target="_blank">Revanth Krishna Senthilkumaran</a></span>
    <span class="student-period">Spring 2022 – Fall 2022</span>
  </div>
  <div class="student-detail">
    <span>B.S., Computer Engineering, Purdue University</span>
  </div>
  <div class="student-detail">
    <svg class="icon-star"><use href="#icon-star"/></svg>
    <span><strong>Honors:</strong> Third Place, Oral Presentation, 2022 Spring Purdue Undergraduate Research Conference</span>
  </div>
  <div class="student-detail">
    <svg class="icon-next"><use href="#icon-next"/></svg>
    <span><strong>Next Position:</strong> M.S. in Robotics, Carnegie Mellon University (CMU)</span>
  </div>
</div>

<h2><svg><use href="#icon-teach"/></svg> Teaching</h2>

<div class="course-card">
  <div class="course-info">
    <div class="course-code">CNIT 175 – Visual Programming</div>
    <div class="course-meta">Purdue University (Fall 2025)</div>
  </div>
  <div class="course-stats">
    <span class="role-badge role-instructor">Instructor</span>
    <span class="course-meta">34 Students</span>
  </div>
</div>

<div class="course-card">
  <div class="course-info">
    <div class="course-code">CNIT 105 – C Programming</div>
    <div class="course-meta">Purdue University (Fall 2024)</div>
  </div>
  <div class="course-stats">
    <span class="role-badge role-ta">Teaching Assistant</span>
    <span class="stat-badge">Eval: 4.5 / 5.0</span>
  </div>
</div>

<div class="course-card">
  <div class="course-info">
    <div class="course-code">CNIT 355 – Mobile Programming</div>
    <div class="course-meta">Purdue University (Fall 2024)</div>
  </div>
  <div class="course-stats">
    <span class="role-badge role-ta">Teaching Assistant</span>
    <span class="stat-badge">Eval: 4.7 / 5.0</span>
  </div>
</div>

<div class="course-card">
  <div class="course-info">
    <div class="course-code">CNIT 315 – Systems Programming</div>
    <div class="course-meta">Purdue University (Spring 2024)</div>
  </div>
  <div class="course-stats">
    <span class="role-badge role-ta">Teaching Assistant</span>
    <span class="stat-badge">Eval: 4.5 / 5.0</span>
  </div>
</div>

<div class="course-card">
  <div class="course-info">
    <div class="course-code">CNIT 355 – Software Development for Mobile Computers</div>
    <div class="course-meta">Purdue University (Fall 2022)</div>
  </div>
  <div class="course-stats">
    <span class="role-badge role-ta">Teaching Assistant</span>
    <span class="stat-badge">Eval: 4.8 / 5.0</span>
  </div>
</div>

<h2><svg><use href="#icon-outreach"/></svg> Outreach</h2>

<div class="outreach-item">
  <div class="outreach-date"><span class="date-box">Apr. 2025</span></div>
  <div class="outreach-content">
    <div class="outreach-title">West Lafayette Jr./Sr. High School, IN</div>
    <div class="outreach-desc">One-day seminar on generative AI for robotics (23 students, 1 teacher).</div>
  </div>
</div>

<div class="outreach-item">
  <div class="outreach-date"><span class="date-box">Dec. 2023</span></div>
  <div class="outreach-content">
    <div class="outreach-title">West Lafayette Jr./Sr. High School, IN</div>
    <div class="outreach-desc">One-day robotics seminar on HRI, multi-robot systems, and design (47 students, 1 teacher).</div>
  </div>
</div>

<div class="outreach-item">
  <div class="outreach-date"><span class="date-box">May 2023</span></div>
  <div class="outreach-content">
    <div class="outreach-title">West Lafayette Jr./Sr. High School, IN</div>
    <div class="outreach-desc">Five-day hands-on robotics program (15 students, 1 teacher).</div>
  </div>
</div>

<div class="outreach-item">
  <div class="outreach-date"><span class="date-box">Dec. 2022</span></div>
  <div class="outreach-content">
    <div class="outreach-title">Macau Anglican College, Macau, China</div>
    <div class="outreach-desc">One-day workshop (virtual) on human-in-the-loop RL and affective robotics (20 students, 4 teachers).</div>
  </div>
</div>
