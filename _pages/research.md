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
Below are some descriptions of my past and current projects. 

# Past Projects
1. Twisted S-duality (joint with Philsang Yoo)

# Current Projects
1. Generalized Geometric Langlands Correspondences from Twisted S-duality (joint with Richard Derryberry)

Seminal work of Kapustin-Witten shows that the Geometric Langlands correspondence can be understood as a consequence of S-duality of 4d N=4 Super Yang-Mills. Namely, the theory has a family of twists labeled by CP^1. The points at zero and infinity of this CP^1 are the so-called A and B twists; compactifying these twisted theories on Riemann Surfaces yields two 2d TQFTs whose categories of boundary conditions are the categories appearing in Geometric Langlands. In my project with Philsang Yoo (discussed above) we show that the A and B twists can be viewed as deformations of the theory on a D3 brane gotten by turning on certain closed string fields in a certain protected sector of IIB string theory. We further show that these two closed string fields are in fact exchanged by S-duality. Curiously, the A and B twists sit in an infinite family of S-dual pairs of closed string fields.

2. Khovanov Homology, Coherent Convoution 2-categories, and Surface Defects in a twist of 5d N=2 Gauge Theory


3. 4d Chern-Simons with Gauge supergroup and 


{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
