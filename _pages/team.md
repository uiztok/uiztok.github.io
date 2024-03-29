---
title: "Meet our team"
layout: archive
permalink: /team/
---

![Group photo](/images/team.jpg)
From the latest retreat of the Lab and the spin-out company [Infinite](http://www.infinite-biotech.com/).


Group Leader
------------
<div class="grid">
<div class="wrapper">
{% for post in site.team %} 
  {% if post.tags contains 'PI' %} 
    {% include archive-single-proj.html type="grid" %} 
  {% endif %} 
{% endfor %}
</div>
</div>

Researchers
-----------
<div class="grid">
<div class="wrapper">
{% for post in site.team %} {% if post.tags contains 'researcher' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}
</div>
</div>

Postdocs
-----------
<div class="grid">
<div class="wrapper">
{% for post in site.team %} {% if post.tags contains 'postdoc' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}
</div>
</div>

PhD Students
------------
<div class="grid">
<div class="wrapper">
{% for post in site.team %} {% if post.tags contains 'phd' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}
</div>
</div>

Staff
-----
<div class="grid">
<div class="wrapper">
{% for post in site.team %} {% if post.tags contains 'staff' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}
</div>
</div>

Students
--------
<div class="grid">
<div class="wrapper">
{% for post in site.team %} {% if post.tags contains 'student' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}
</div>
</div>

Past members since 2020
--------
<div class="grid">
<div class="wrapper">
{% for post in site.team %} {% if post.tags contains 'former' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}
</div>
</div>