---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
---

{% include base_path %}

<h1> Publications </h1>

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=R7_PYuQAAAAJ">my Google Scholar profile</a>.</u>

##{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

