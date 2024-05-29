---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my publications and preprints on <a href="{{[site.author.googlescholar](https://scholar.google.com/citations?user=1aal5_wAAAAJ&hl=zh-CN)}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
* Ancilla-free scheme of deterministic topological quantum gates for Majorana qubits <br>
   _Su-Qi Zhang, Jian-Song Hong, **Yuan Xue**, Xun-Jiang Luo, Li-Wei Yu, Xiong-Jun Liu, Xin Liu_ <br>
   Phys. Rev. B | [arXiv: 2305.18190](https://arxiv.org/abs/2305.18190)

