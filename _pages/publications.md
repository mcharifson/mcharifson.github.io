---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

#"Evolutionary origins of Polycystic Ovary Syndrome: An environmental mismatch disorder"
Charifson, M. Trumble, BC. “Evolutionary origins of Polycystic Ovary Syndrome: An environmental mismatch disorder”. Evolution, Medicine and Public Health (2019).[Download paper here](https://doi.org/10.1093/emph/eoz011)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
