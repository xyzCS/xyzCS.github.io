---
permalink: /
author_profile: true
excerpt: "PhD student at King's College London researching AI for Scientific Discovery, code reproduction, and reinforcement learning for LLM-based agents."
redirect_from: 
  - /about/
  - /about.html
---

Hello! I'm a PhD student in the [NLP group](https://kclnlp.github.io/) at King’s College London, working with [Prof. Yulan He](https://sites.google.com/view/yulanhe) and [Dr. Lin Gui](https://sites.google.com/view/lin-gui/about-me).

{% include profile-summary.md %}

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

Invited Talks
======
- Meta, LLaMA Community Meet-up (Apr. 6, 2025): “Towards Automatic Code Reproduction for Scientific Papers: Benchmarks and Methodologies.” [[event post](https://www.linkedin.com/posts/yanzheng-xiang-9aa572282_ai-llm-agenticai-activity-7336720296193761281-yGy2/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAETIZhIBXh5XAI2i8HIYl-QGLzQlxhu0J98)]
