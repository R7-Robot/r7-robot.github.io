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

<p>My research focuses on <strong>robot learning from humans to close the last mile of robot intelligence</strong>. Large-scale pretraining gives robots broad capabilities, yet real-world deployment brings unfamiliar tasks, unforeseen situations, and users with their own expectations. Human feedback communicates what success means in each setting, including goals, preferences, and constraints that pretraining alone cannot fully specify. I build methods that let robots bridge this gap through the feedback people naturally provide: preferences, language, and implicit signals.</p>

<p>My work mainly asks three questions:</p>

<ul class="hx-questions">
<li><strong>How can robots learn more from less human feedback?</strong> I use foundation models as synthetic teachers to amplify sparse human feedback into rich supervision, enabling robots to learn beyond the examples people explicitly evaluate.</li>
<li><strong>How can robots reuse what they learn from people?</strong> I study how to capture human intent in reusable representations that separate transferable structure from context-specific details. This allows robots to carry prior learning across tasks, users, and embodiments, reducing the need to learn from scratch.</li>
<li><strong>How can robots adapt to people in context?</strong> I develop general human-conditioned reward models that infer what a person wants from multimodal feedback at deployment. This makes human feedback a direct input to adaptation, enabling robots to adjust their behavior in context without retraining.</li>
</ul>

<p>Together, these directions aim to make robots easier to teach, better at building on experience, and more responsive to the people they work with.</p>

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
  <p><strong>Reviewer</strong>: NeurIPS, ICLR, CoRL, ICRA, IROS, HRI · IEEE T-CYB, RA-L, T-HMS, ACM THRI</p>
</section>
