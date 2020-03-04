---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---




Below are some descriptions of my past and current projects. 

Past Projects
------
<details>
<summary> Twisted S-duality (joint with <a href="https://sites.google.com/site/philsangyoo/">Philsang Yoo</a>)</summary>
<p>
This project aims to illustrate a framework for the systematic and rigorous investigation of some mathematical implications of string dualities. The key ingredients are some amazing conjectures of Costello-Li giving descriptions of certain supersymmetry protected sectors of type II superstrings in terms of topological strings. This allows one to recover many calculational maneuvers familiar to string theorists in terms of data attached to a 5-Calabi-Yau category.  A key feature of these protected sectors is that the worldvolume theories of D-branes are twists of the worldvolume theories one normally finds. Since twists of supersymmetric field theories now sit on relatively firm mathematical foundations, these conjectures afford a useful framework for making mathematical conjectures about the effects of string dualities on various homotopical algebraic/derived geometric data attached to supersymmetric field theories. 
</p>

<p>
As a first step in this direction, we derive the action of S-duality on a certain supersymmetry protected sector of type IIB string theory. In mathematical terms, this amounts to constructing an action of $SL_2(\mathbb{Z})$ on the cyclic cochains of a Calabi-Yau 3-fold. We then show that S-duality in this protected sector is responsible for the Geometric Langlands correspondence for $GL_n$, and for a description of the quantized Coulomb branch ring of A-twisted 3d $\mathcal{N}=4$ quiver gauge theories in terms of shifted truncated Yangians. We conclude with some conjectures about other S-dual deformations of 4d $\mathcal{N}=4$ that our framework suggests.
</p>
</details>

Current Projects
------
1. Towards Generalized Geometric Langlands Correspondences from Twisted S-duality (joint with [Richard Derryberry](https://www.perimeterinstitute.ca/people/richard-derryberry))

Seminal work of Kapustin-Witten shows that the Geometric Langlands correspondence can be understood as a consequence of S-duality of 4d $\mathcal{N}=4$ Super Yang-Mills. Namely, the theory has a family of twists labeled by $\mathbb{CP}^1$. The points at zero and infinity of this $\mathbb{CP}^1$ are the so-called A and B twists; compactifying these twisted theories on Riemann Surfaces yields two 2d TQFTs whose categories of boundary conditions are the categories appearing in Geometric Langlands. In my project with Philsang Yoo (discussed above) we show that the A and B twists can be viewed as deformations of the theory on a D3 brane gotten by turning on certain closed string fields in a certain protected sector of IIB string theory. We further show that these two closed string fields are in fact exchanged by S-duality. Curiously, the A and B twists sit in an infinite family of S-dual pairs of closed string fields.

This (in progress) project aims to establish a compatibility between twisted S-duality, and the so-called dolbeault Geomtric Langlands conjecture, in a way that hints at Langlands-like correspondences for other S-dual pairs of closed string fields. Mathematically, this is expressed as follows: let $\Sigma$ be a complex projective curve. A theorem of [Donagi-Pantev](https://arxiv.org/abs/math/0604617) establishes a nontrivial self equivalence of the category $\text{Coh}(\text{Higgs}_{GL_n}\Sigma)$ away from the discriminant locus. We show this induces an action of $\mathbb{Z}/4\mathbb{Z}$ on $\mathcal{O}(T^*[1]\mathrm{Higgs}_{GL_n}\Sigma)$ viewed as Hamiltonian deformations of the shifted symplectic stack $T^*[1]\operatorname{Higgs}_{GL_n}(\Sigma)$. Further, we construct a map from the cyclic cochains $HC^\bullet(T^*\Sigma\times\mathbb{C})\to\mathcal{O}(T^*[1]\mathrm{Higgs}_{GL_n}\Sigma)$ intertwining the action of S-duality on the source with the action of $\mathbb{Z}/4\mathbb{Z}$ on the target. 

2. Khovanov Homology, Coherent Convoution 2-categories, and Surface Defects in a twist of 5d $\mathcal{N}=2$ Gauge Theory

In my master's thesis I began a project to try and relate two constructions of Khovanov Homology. One is due to [Witten](https://arxiv.org/abs/1101.3216) and realizes Khovanov Homology of a link $L$ as the Hilbert space for the theory living on a surface defect supported on $L\times\mathbb{R}$ in an A-type twist of 5d $\mathcal{N}=2$ gauge theory. Another is due to [Cautis-Kamnitzer](https://arxiv.org/abs/math/0701194) and uses a certain 2-category built out of coherent sheaves on convolution products of orbits in the affine Grassmannian. My master's work substantiated a claim that the 2-category of Cautis-Kamnitzer can be understood as a specific subcategory of the 2-category of surface defects in a holomorphic-topological twist of 5d $\mathcal{N}=2$ gauge theory.

Since then, I have given a brane realization for the construction in my master's work in a particular twist of type IIA string theory. This brane realization can be lifted to a [twist of M-theory](https://arxiv.org/abs/1610.04144) studied by Costello, and upon doing so, matches the M-theoretic lift of the brane construction originally studied by Witten. Further work of [Mykhailov-Witten](https://arxiv.org/abs/1410.1175) uses a slight modification of the original brane construction to construct a knot homology they call "Khovanov homology for supergroups". The M-theoretic lift of this modification suggests a variation of the construction of my master's work that yields a certain geometrically defined 2-category from which Mykhailov-Witten's knot homology can conjecturally be computed as a certain Ext. Joint with [Arjuna Hathaway](https://pages.uoregon.edu/jayh/) I am currently trying to use this 2-category to categorify the intertwiners of $GL(1\|1)$.



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
