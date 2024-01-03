---
layout: archive
title: "Teaching and Organization"
permalink: /teach+org/
author_profile: true
---

{% include base_path %}

## Seminars:
{% for post in site.seminars reversed %}
  {% include archive-single.html %}
{% endfor %}

## Courses:
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
