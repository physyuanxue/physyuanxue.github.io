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
