---
permalink: /
author_profile: true
excerpt: "PhD student at King's College London researching Auto Research, code reproduction, and reinforcement learning for LLM-based agents."
redirect_from: 
  - /about/
  - /about.html
---

Hello! I'm a PhD student in the [NLP group](https://kclnlp.github.io/) at King’s College London, working with [Prof. Yulan He](https://sites.google.com/view/yulanhe) and [Dr. Lin Gui](https://sites.google.com/view/lin-gui/about-me).

{% include profile-summary.md %}

News
======
{% include news-list.html limit=4 %}

[All news]({{ '/news/' | relative_url }})

Experience
======
{% include profile-experience.md %}

Publications
======
<ul class="publication-list">
{% assign publications = site.publications | sort: 'order' %}
{% for publication in publications %}
  {% assign post = publication %}
  {% include publication-list-item.html %}
{% endfor %}
</ul>
