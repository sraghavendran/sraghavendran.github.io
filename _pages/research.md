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

Past Projects
------
1. Twisted S-duality (joint with [Philsang Yoo](https://sites.google.com/site/philsangyoo/))

This project aims to illustrate a framework for the systematic and rigorous investigation of some mathematical implications of string dualities. The key ingredients are some amazing conjectures of Costello-Li giving descriptions of certain supersymmetry protected sectors of type II superstrings in terms of topological strings. This allows one to recover many calculational maneuvers familiar to string theorists in terms of data attached to a 5-Calabi-Yau category.  A key feature of these protected sectors is that the worldvolume theories of D-branes are twists of the worldvolume theories one normally finds. Since twists of supersymmetric field theories now sit on relatively firm mathematical foundations, these conjectures afford a useful framework for making mathematical conjectures about the effects of string dualities on various homotopical algebraic/derived geometric data attached to supersymmetric field theories. 

As a first step in this direction, we derive the action of S-duality on a certain supersymmetry protected sector of type IIB string theory. In mathematical terms, this amounts to constructing an action of $SL_2(\mathbb{Z})$ on the cyclic cochains of a Calabi-Yau 3-fold. We then show that S-duality in this protected sector is responsible for the Geometric Langlands correspondence for $GL_n$, and for a description of the quantized Coulomb branch ring of A-twisted 3d $\mathcal{N}=4$ quiver gauge theories in terms of shifted truncated Yangians. We conclude with some conjectures about other S-dual deformations of 4d $\mathcal{N}=4$ that our framework suggests.

Current Projects
------
1. Generalized Geometric Langlands Correspondences from Twisted S-duality (joint with [Richard Derryberry](https://www.perimeterinstitute.ca/people/richard-derryberry))

Seminal work of Kapustin-Witten shows that the Geometric Langlands correspondence can be understood as a consequence of S-duality of 4d $\mathcal{N}=4$ Super Yang-Mills. Namely, the theory has a family of twists labeled by $\mathbb{CP}^1$. The points at zero and infinity of this $\mathbb{CP}^1$ are the so-called A and B twists; compactifying these twisted theories on Riemann Surfaces yields two 2d TQFTs whose categories of boundary conditions are the categories appearing in Geometric Langlands. In my project with Philsang Yoo (discussed above) we show that the A and B twists can be viewed as deformations of the theory on a D3 brane gotten by turning on certain closed string fields in a certain protected sector of IIB string theory. We further show that these two closed string fields are in fact exchanged by S-duality. Curiously, the A and B twists sit in an infinite family of S-dual pairs of closed string fields.

2. Khovanov Homology, Coherent Convoution 2-categories, and Surface Defects in a twist of 5d $\mathcal{N}=2$ Gauge Theory


3. 4d Chern-Simons with Gauge supergroup and Superspin chains


{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
