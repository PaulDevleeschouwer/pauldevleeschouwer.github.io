---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in mathematics, Sorbonne University, 2025-2026
* B.S. in mathematics, Grenoble Alpes University, 2024-2025
* Preparatory classes, MPSI and MP-ET, Lycée Champollion, 2022-2024
  
Skills
======
* LaTeX
* Inkscape
* Anki
* Algebraic topology, commutative algebra

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
