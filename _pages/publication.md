---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="[https://scholar.google.com/citations?user=heXZzcQAAAAJ&hl=en](https://scholar.google.com/citations?hl=en&user=knbD-EQAAAAJ&view_op=list_works&gmla=ALUCkoU0bXz3oUnyvNhXkQ1hk4xZB_acIb4NVfy65ytKtfvirb5kL9s0mRnWB9FQgriYi-Aob21jsy99OX0CwOUX)">my Google Scholar profile</a>.</u>

{% if author.googlescholar %}

{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

