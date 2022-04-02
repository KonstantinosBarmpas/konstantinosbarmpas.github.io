---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For a complete updated list of my publications page, visit my [Google Scholar profile](https://scholar.google.com/citations?user=JkRlsiQAAAAJ&hl=el&oi=ao).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
