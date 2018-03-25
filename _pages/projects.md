---
layout: archive
permalink: projects/
date: 2018-02-18
modified: 2018-03-25
---

# Projects big and small I've been working on

<div>
{% for post in site.categories.projects %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
