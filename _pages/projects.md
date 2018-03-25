---
layout: archive
permalink: projects/
title: projects
date: 2014-05-30T11:40:45-04:00
modified:
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.projects %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

