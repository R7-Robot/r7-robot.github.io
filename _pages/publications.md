---
layout: archive
title: "Publications"
permalink: /Publications/
author_profile: true
---

{%- assign pubs = site.data.publications | where_exp: "p", "p.hidden != true" %}
{%- assign years = "2026,2025,2024,2023,2022" | split: "," %}

<div class="hx-publist" id="publist" markdown="0">

  <p class="hx-lead">My research centers on robot learning from human feedback, enabling robots to generalize to new tasks and adapt to individual users. Alongside this core line, I have studied how robots perceive and adapt to broader human signals, such as cognitive workload and physiological state, and how these ideas extend to multi-human multi-robot teams.</p>

  <p class="hx-note">Reverse chronological order. † Equal contribution · § Work I mentored · Also on <a class="hx-plain" href="https://scholar.google.com/citations?hl=en&user=b6LHm70AAAAJ&view_op=list_works&sortby=pubdate">Google Scholar</a>.</p>

  <div class="hx-toggle" role="group" aria-label="Filter publications">
    <button type="button" class="is-active" data-view="all">All</button>
    <button type="button" data-view="selected">Selected</button>
  </div>

  {%- for y in years %}
  {%- assign yr = y | plus: 0 %}
  {%- assign group = pubs | where: "year", yr %}
  {%- if group.size > 0 %}
  {%- assign sel = group | where_exp: "p", "p.selected" %}
  <div class="hx-group{% if sel.size == 0 %} no-selected{% endif %}">
    <h2 class="hx-year">{{ y }}</h2>
    {%- for p in group %}
    {% include pub-entry.html pub=p %}
    {%- endfor %}
  </div>
  {%- endif %}
  {%- endfor %}

</div>

<script>
(function () {
  var list = document.getElementById('publist');
  if (!list) return;
  var buttons = list.querySelectorAll('.hx-toggle button');
  buttons.forEach(function (b) {
    b.addEventListener('click', function () {
      buttons.forEach(function (x) { x.classList.remove('is-active'); });
      b.classList.add('is-active');
      list.classList.toggle('only-selected', b.getAttribute('data-view') === 'selected');
    });
  });
})();
</script>
