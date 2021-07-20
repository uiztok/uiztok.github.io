---
title: "Meet our team"
layout: archive
permalink: /team/
---

![Group photo](/images/team_2021.jpg)


Group Leader
------------

{% for post in site.team %} {% if post.tags contains 'PI' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}


Researchers
-----------

{% for post in site.team %} {% if post.tags contains 'researcher' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}


PhD Students
------------

{% for post in site.team %} {% if post.tags contains 'phd' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}


Staff
-----

{% for post in site.team %} {% if post.tags contains 'staff' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}


Students
--------

{% for post in site.team %} {% if post.tags contains 'student' %} {% include archive-single-proj.html type="grid" %} {% endif %} {% endfor %}
