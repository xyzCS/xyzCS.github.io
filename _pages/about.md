---
permalink: /
author_profile: true
excerpt: "PhD student at King's College London researching AI for Scientific Discovery, code reproduction, and reinforcement learning for LLM-based agents."
redirect_from: 
  - /about/
  - /about.html
---

Hello! I'm a PhD student in the [NLP group](https://kclnlp.github.io/) at King’s College London, working with [Prof. Yulan He](https://sites.google.com/view/yulanhe) and [Dr. Lin Gui](https://sites.google.com/view/lin-gui/about-me).

[View my CV]({{ '/cv/' | relative_url }}) · [Download CV (PDF)]({{ '/files/yanzheng-cv.pdf' | relative_url }})

Professional Summary
======
{% include profile-summary.md %}

Experience
======
{% include profile-experience.md %}

Education
======
{% include profile-education.html %}

Awards and Honors
======
- NMES International Studentship (2023 – 2027)
- Outstanding Graduate Student, Hefei University of Technology (2020)
- Merit Student, Hefei University of Technology (2018)

Invited Talks
======
- Meta, LLaMA Community Meet-up (Apr. 6, 2025): “Towards Automatic Code Reproduction for Scientific Papers: Benchmarks and Methodologies.” [[event post](https://www.linkedin.com/posts/yanzheng-xiang-9aa572282_ai-llm-agenticai-activity-7336720296193761281-yGy2/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAETIZhIBXh5XAI2i8HIYl-QGLzQlxhu0J98)]

Competitions
======
- **National First Prize (Top 0.65%)**, China Undergraduate Mathematical Contest in Modelling (2018). Team-based modeling competition solving open-ended applied problems.
- **1st Place**, [Spider Leaderboard](https://yale-lily.github.io/spider) (2022). Our model G3R achieved the top rank on the “exact set match without values” metric.

Course Teaching
======
{% include course-teaching.html %}

Publications
======
<ul class="publication-list">
{% assign publications = site.publications | sort: 'order' %}
{% for publication in publications %}
  {% assign post = publication %}
  {% include publication-list-item.html %}
{% endfor %}
</ul>
