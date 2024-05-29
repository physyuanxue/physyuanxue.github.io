---
layout: archive
title: "Activities"
permalink: /activities/
author_profile: true
---

{% if site.author.googlescholar %}
  You can find my publications and preprints on [my Google Scholar profile](https://scholar.google.com/citations?user=1aal5_wAAAAJ&hl=zh-CN)
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
* Ancilla-free scheme of deterministic topological quantum gates for Majorana qubits <br>
   _Su-Qi Zhang, Jian-Song Hong, **Yuan Xue**, Xun-Jiang Luo, Li-Wei Yu, Xiong-Jun Liu, Xin Liu_ <br>
   Physics Review B, 2024 | [arXiv: 2305.18190](https://arxiv.org/abs/2305.18190)
