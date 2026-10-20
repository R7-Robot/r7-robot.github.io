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

<div class="hx-intro">

<p>I am a Postdoctoral Research Fellow at the University of Southern California, working with Professor <a href="https://ebiyik.github.io/">Erdem Bıyık</a> in the <a href="https://liralab.usc.edu/">LiRA Lab</a>. I received my Ph.D. from Purdue University, where I worked with Professor <a href="http://www.smart-laboratory.org/group/bcm.html">B.C. Min</a> in the SMART Lab.</p>

<p>My research focuses on <strong>robot learning from humans to close the last mile of robot intelligence</strong>: bridging the gap between general capabilities acquired through large-scale pretraining and the task generalization and personalization needed for real-world deployment. I develop methods that enable robots to learn efficiently from natural human feedback, including preferences, language, and implicit signals, so they can handle novel task scenarios and adapt to individual users with minimal interaction.</p>

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
