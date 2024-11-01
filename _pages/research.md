---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<h2>Working papers</h2>
{% for post in site.research reversed %}
  {% if post.pubtype == 'workingpaper' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

