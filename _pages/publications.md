---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## 2021
- Pasande M, Hosseini R, Araabi BN. (2023). Stochastic First-Order Learning for Large-Scale Flexibly-Tied Gaussian Mixture Model. arXiv preprint [arxiv 2212.05402]{http://arxiv.org/abs/2212.05402}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
