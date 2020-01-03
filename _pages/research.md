---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

#Current Projects
1. Generalized Geometric Langlands Correspondences from Twisted S-duality

2. Khovanov Homology, Coherent Convoution 2-categories, and Surface Defects in a twist of 5d N=2 Gauge Theory

#Past Projects
1. Twisted S-duality

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
