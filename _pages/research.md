---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /publications
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
