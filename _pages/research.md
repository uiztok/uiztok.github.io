---
layout: archive
title: "Research fields"
permalink: /research/
---
{% include base_path %}

<hr>
<div class="grid">
<div class="wrapper">
  {% for post in site.research %}
    {% include archive-single-proj.html type="grid" %}
  {% endfor %}
</div>
</div>