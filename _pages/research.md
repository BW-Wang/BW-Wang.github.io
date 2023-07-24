---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

{% include base_path %}

Please click on the paper title to view the free download link and short summary.

{% for post in site.research reversed %}
  {% include archive-single-research.html %}
{% endfor %}

