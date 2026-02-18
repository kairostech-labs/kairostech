---
layout: default
title: Cycles
permalink: /cycles/
---

# Cycles

{% for post in site.categories.cycles %}
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
{% endfor %}
