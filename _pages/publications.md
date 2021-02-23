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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

1. Zhao, Zhiqin, Xu Qian, **Bowen Wang**, and Bowen Jia. "Numerical simulation of the effects of InAlSb barrier layers on the InSb mid-infrared photodetectors on a mismatched substrate." In *Optoelectronic Devices and Integration VIII*, vol. 11184, p. 1118411. International Society for Optics and Photonics, 2019.<a href="{{ https://github.com/jayrobwilliams/Peace-Agreement-Strength }}"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a> <a href="{{ https://bw-wang.github.io/publications/ }}"><i class="fas fa-fw fa-code zoom" aria-hidden="true"></i></a>  <a href="{{ /files/pdf/papers/SPIE.pdf }}"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a>  <a href="{{ https://doi.org/10.1117/12.2536915 }}"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a>

<sup>*</sup> Equal authorship statement

