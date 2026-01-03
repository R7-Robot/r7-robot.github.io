---
layout: archive
title: "Robot Prototypings"
permalink: /Prototypings/
author_profile: true
---

<svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
  <symbol id="icon-nav" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="3 11 22 2 13 21 11 13 3 11"/></symbol>
  <symbol id="icon-follow" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="8.5" cy="7" r="4"/><polyline points="17 11 19 13 23 9"/></symbol>
  <symbol id="icon-find" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></symbol>
  <symbol id="icon-calendar" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></symbol>
  <symbol id="icon-box" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"/><polyline points="3.27 6.96 12 12.01 20.73 6.96"/><line x1="12" y1="22.08" x2="12" y2="12"/></symbol>
  <symbol id="icon-plus" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></symbol>
  <symbol id="icon-trophy" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M8 21h8m-4-4v4m-8.24-7.62a2 2 0 0 1 .78-3.22L12 3l7.46 2.16a2 2 0 0 1 .78 3.22M6 14h12a6 6 0 0 0 6-6V7a1 1 0 0 0-1-1H1a1 1 0 0 0-1 1v1a6 6 0 0 0 6 6z"/></symbol>
</svg>

<style>
  /* General Styles */
  .prototyping-intro {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #374151;
    background-color: #f9fafb;
    padding: 1.5rem;
    border-radius: 8px;
    border-left: 4px solid #2563eb;
    margin-bottom: 2.5rem;
  }

  h2.section-title {
    font-size: 1.8rem;
    color: #111827;
    margin-top: 3rem;
    margin-bottom: 1.5rem;
    padding-bottom: 0.5rem;
    border-bottom: 2px solid #e5e7eb;
    position: relative;
  }
  
  h2.section-title::after {
    content: '';
    position: absolute;
    bottom: -2px;
    left: 0;
    width: 60px;
    height: 2px;
    background-color: #2563eb;
  }

  /* Project Card Style */
  .project-card {
    background: #fff;
    border: 1px solid #e5e7eb;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
    margin-bottom: 2rem;
  }

  .project-header {
    padding: 1.5rem 1.5rem 0.5rem;
    font-size: 1.05rem;
    color: #374151;
  }

  /* * CUSTOM FLEX GALLERY 
   * 这是一个更灵活的画廊
   */
  .flex-gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 15px;
    padding: 15px;
    background: #f3f4f6;
  }

  .flex-gallery img {
    /* 桌面端：使用 CSS 变量 --h 控制高度，默认 300px */
    height: var(--h, 300px); 
    width: auto;
    
    /* 样式美化 */
    border-radius: 6px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: transform 0.2s;
  }

  .flex-gallery img:hover {
    transform: scale(1.02);
  }

  /* Features Grid Styles */
  .features-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
    padding: 1.5rem;
    background-color: #f9fafb;
    border-top: 1px solid #e5e7eb;
  }

  .feature-item {
    display: flex;
    align-items: flex-start;
    gap: 0.75rem;
  }

  .feature-icon {
    flex-shrink: 0;
    width: 24px;
    height: 24px;
    color: #2563eb;
    margin-top: 3px;
  }

  .feature-content h4 {
    margin: 0 0 0.25rem 0;
    font-size: 1rem;
    font-weight: 600;
    color: #1f2937;
  }

  .feature-content p {
    margin: 0;
    font-size: 0.9rem;
    color: #6b7280;
    line-height: 1.4;
  }

  /* Video Container */
  .video-container {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
    height: 0;
    overflow: hidden;
    border-radius: 12px;
    margin: 2rem auto;
    box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
  }

  .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }

  /* Honors Section */
  .honors-list {
    list-style: none;
    padding: 0;
    margin: 1.5rem 0;
  }

  .honor-item {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    padding: 0.75rem;
    background: #fff;
    border: 1px solid #e5e7eb;
    border-radius: 8px;
    margin-bottom: 0.5rem;
    transition: all 0.2s;
  }
  
  .honor-item:hover {
    border-color: #2563eb;
    transform: translateX(5px);
  }

  .honor-icon {
    width: 20px;
    height: 20px;
    color: #d97706; /* Bronze/Gold color */
  }

  /* Other Robots List */
  .robot-list {
    display: grid;
    gap: 1rem;
  }

  .robot-item {
    background: #f9fafb;
    padding: 1rem;
    border-radius: 8px;
    border-left: 3px solid #9ca3af;
  }
  .robot-item strong { color: #1f2937; }

  /* Responsive adjustments: Mobile */
  @media (max-width: 768px) {
    /* 在手机上强制图片宽度占满，高度自动，忽略设定的固定高度 */
    .flex-gallery {
      flex-direction: column;
    }
    .flex-gallery img {
      height: auto !important;
      width: 100%;
      max-width: 100%;
    }
  }
</style>

<div class="prototyping-intro">
  During my undergraduate studies majoring in robotics engineering, I had the pleasure of founding and leading an undergraduate robotics innovation group named <strong>CP-Robot</strong>. Together, we had the opportunity to design and build several cool robots, encompassing mechanical designs, sophisticated algorithms, and system integration. These projects allowed us to participate in and win several international and national robotics competitions.
</div>

<h2 class="section-title">Service Robot Seeker</h2>

<div class="project-card">
  <div class="project-header">
    The Service Robot Seeker is a mobile robot designed for human-robot interaction, providing various services to assist people in their daily lives.
  </div>

  <div class="flex-gallery" style="--h: 500px;">
    <img src="/images/Seeker1.jpg" alt="Service Robot Seeker View 1" />
    <img src="/images/Seeker2.jpg" alt="Service Robot Seeker View 2" />
  </div>

  <div class="features-grid">
    <div class="feature-item">
      <svg class="feature-icon"><use href="#icon-nav"/></svg>
      <div class="feature-content">
        <h4>Semantic Navigation</h4>
        <p>Understand and navigate different environments efficiently with semantic mapping.</p>
      </div>
    </div>
    <div class="feature-item">
      <svg class="feature-icon"><use href="#icon-follow"/></svg>
      <div class="feature-content">
        <h4>Human Following</h4>
        <p>Robust algorithms enable the robot to track and follow individuals for seamless assistance.</p>
      </div>
    </div>
    <div class="feature-item">
      <svg class="feature-icon"><use href="#icon-find"/></svg>
      <div class="feature-content">
        <h4>Human Finding</h4>
        <p>Integrated vision sensors detect and locate humans to initiate interaction.</p>
      </div>
    </div>
    <div class="feature-item">
      <svg class="feature-icon"><use href="#icon-calendar"/></svg>
      <div class="feature-content">
        <h4>Calendar Reminder</h4>
        <p>Alerts users of scheduled tasks, synchronized with popular calendar apps.</p>
      </div>
    </div>
    <div class="feature-item">
      <svg class="feature-icon"><use href="#icon-box"/></svg>
      <div class="feature-content">
        <h4>Object Detection & Delivery</h4>
        <p>ML models identify objects for interaction and delivery tasks.</p>
      </div>
    </div>
    <div class="feature-item">
      <svg class="feature-icon"><use href="#icon-plus"/></svg>
      <div class="feature-content">
        <h4>Additional Features</h4>
        <p>Includes voice recognition, task scheduling, and real-time feedback.</p>
      </div>
    </div>
  </div>
</div>

<div class="video-container">
  <iframe src="https://www.youtube.com/embed/xhyb7qtM-Rc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<h3>Honors & Competitions</h3>

<ul class="honors-list">
  <li class="honor-item">
    <svg class="honor-icon"><use href="#icon-trophy"/></svg>
    <span><strong>Second Place</strong>: <a href="https://www.ijcai19.org/competitions.html" target="_blank">The IJCAI-2019 Eldercare Robot Challenge</a>, Macau, China, 2019.</span>
  </li>
  <li class="honor-item">
    <svg class="honor-icon"><use href="#icon-trophy"/></svg>
    <span><strong>Third Prize</strong>: RoboCup2019 China Open @Home, Shaoxing, China, 2019.</span>
  </li>
</ul>

<div class="flex-gallery" style="--h: 300px;">
  <img src="/images/RoboCup.jpg" alt="RoboCup" />
  <img src="/images/IJCAI.jpg" alt="IJCAI" />
</div>

<div class="flex-gallery" style="--h: 280px;">
  <img src="/images/Game0.jpg" alt="Game Demo" />
  <img src="/images/Game2.jpg" alt="Game Demo 2" />
</div>


<h2 class="section-title">Other Robots</h2>

<p>
  Demo videos of these robots can be found <a href="https://www.youtube.com/watch?v=mUI77WsNyaw" target="_blank" style="color: #2563eb; font-weight: 600;">here <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align: middle;"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg></a>.
</p>

<div class="robot-list">
  <div class="robot-item">
    <strong>Tennis Ball-Automatic-Recovery Robot</strong>: Utilized SLAM navigation and computer vision technology to accurately locate and retrieve tennis balls.
  </div>
  <div class="robot-item">
    <strong>Field Robot</strong>: Designed to trace black ground lines and jump over obstacles.
  </div>
  <div class="robot-item">
    <strong>Dancing Robot</strong>: Equipped with the ability to recognize various music genres and dance in sync with the rhythm.
  </div>
  <div class="robot-item">
    <strong>Vehicle Rescue Robot</strong>: Receives real-time video signals to facilitate obstacle clearance.
  </div>
  <div class="robot-item">
    <strong>Fighting Robot</strong>: Integrated with weapon transfer capabilities and an electronic speed controller.
  </div>
</div>

<h3>Honors</h3>
<ul class="honors-list">
  <li class="honor-item">
    <svg class="honor-icon"><use href="#icon-trophy"/></svg>
    <span><strong>Champion</strong>, Softbank Cup2018-China Robot Skills Competition (Innovation Section), Taizhou, China, 2018.</span>
  </li>
  <li class="honor-item">
    <svg class="honor-icon"><use href="#icon-trophy"/></svg>
    <span><strong>Second Prize</strong>, Softbank Cup2018-China Robot Skills Competition (Field Robot Section), Taizhou, China, 2018.</span>
  </li>
</ul>

<div class="flex-gallery" style="--h: 300px;">
  <img src="/images/SoftBank.jpg" alt="SoftBank" />
  <img src="/images/SoftBank1.jpg" alt="SoftBank 1" />
  <img src="/images/SoftBank2.jpg" alt="SoftBank 2" />
</div>
