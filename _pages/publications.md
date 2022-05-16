---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=R7_PYuQAAAAJ" target='_blank'>my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
