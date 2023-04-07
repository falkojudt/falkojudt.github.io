---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Judt, F.,** and S. S. Chen, 2010: Convectively Generated Potential Vorticity in Rainbands and Formation of the Secondary Eyewall in Hurricane Rita of 2005. *J. Atmos. Sci.,* **67**, 3581–3599, https://doi.org/10.1175/2010JAS3471.1.
[Download paper here](http://academicpages.github.io/files/JudtandChen2010.pdf)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
