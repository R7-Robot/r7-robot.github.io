---
permalink: /
title: "Ruiqi Wang"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p class="hx-pron">/ Ray-chee Wong /</p>

<div class="hx-intro" markdown="0">

<p>I am a Postdoctoral Research Fellow at the University of Southern California, working with Professor <a href="https://ebiyik.github.io/">Erdem Bıyık</a> in the <a href="https://liralab.usc.edu/">LiRA Lab</a>. I received my Ph.D. from Purdue University, where I worked with Professor <a href="http://www.smart-laboratory.org/group/bcm.html">B.C. Min</a> in the SMART Lab.</p>

<p>My research focuses on <strong>robot learning from humans to close the last mile of embodied AI</strong>. Robotic foundation models pretrained at scale bring broad capabilities, yet real-world deployment presents unfamiliar tasks, unforeseen situations, and users with their own expectations. Human feedback communicates what success means in each setting, including goals, preferences, and constraints that pretraining alone cannot fully specify. I build methods that let robots bridge this gap through the feedback people naturally provide: preferences, language, and implicit signals.</p>

<details class="hx-details">
<summary>My work mainly asks three questions</summary>

<ul class="hx-questions">
<li><strong>How can robots learn more from less human feedback?</strong> I use foundation models as synthetic teachers to amplify sparse human feedback into rich supervision, enabling robots to learn beyond the examples people explicitly evaluate.</li>
<li><strong>How can robots capture what people actually want?</strong> Human feedback is coarse, noisy, and often comes from many people who disagree. I develop reward learning methods that attribute holistic judgments to the specific behaviors that matter and model diverse, even conflicting, preferences across a crowd, yielding rewards that faithfully reflect human intent.</li>
<li><strong>How can robots generalize and adapt beyond what they were taught?</strong> I study how to distill human intent into reusable structure that transfers across tasks, users, and embodiments, and how robots can adapt to new people at deployment, whether by steering a pretrained policy or by inferring intent in context from multimodal feedback, without retraining.</li>
</ul>

<p>Together, these directions aim to make robots easier to teach, more faithful to human intent, and quicker to adapt to new tasks and the people they work with.</p>
</details>

</div>

<section class="hx-section" markdown="0">
  <h2 class="hx-h2">News</h2>
  <div class="hx-news">
    <ul>
      {%- for n in site.data.news %}
      <li><span class="hx-date">{{ n.date }}</span><span>{{ n.text }}</span></li>
      {%- endfor %}
    </ul>
  </div>
</section>

<section class="hx-section" markdown="0">
  <h2 class="hx-h2">Selected Publications</h2>
  {%- assign all_pubs = site.data.publications | where_exp: "p", "p.hidden != true" %}
  <p class="hx-note">† Equal contribution · § Work I mentored · <a class="hx-plain" href="/Publications/"><strong>See all {{ all_pubs.size }} publications →</strong></a></p>
  {%- assign selected = site.data.publications | where_exp: "p", "p.selected" | where_exp: "p", "p.hidden != true" | sort: "selected" %}
  <div class="hx-publist">
    {%- for p in selected %}
    {% include pub-entry.html pub=p summary=true %}
    {%- endfor %}
  </div>
</section>

<section class="hx-section hx-service" markdown="0">
  <h2 class="hx-h2">Service</h2>
  <p><strong>Associate Editor</strong>, ICRA 2027 (Robot Learning)</p>
  <p><strong>Outstanding Reviewer</strong>, CoRL 2026</p>
  <p><strong>Reviewer</strong>: NeurIPS, ICLR, CoRL, ICRA, IROS, HRI · IEEE T-CYB, RA-L, T-HMS, ACM THRI</p>
</section>
