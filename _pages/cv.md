---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
excerpt: "Research experience, education, publications, and teaching of Yanzheng Xiang."
redirect_from:
  - /resume
---

[Download CV (PDF)]({{ '/files/yanzheng-cv.pdf' | relative_url }})

Professional Summary
======
{% include profile-summary.md %}

Experience
======
{% include profile-experience.md %}

Education
======
{% include profile-education.html detailed=true %}

Publications
======
<ul class="publication-list">
{% assign publications = site.publications | sort: 'order' %}
{% for publication in publications %}
  {% assign post = publication %}
  {% include publication-list-item.html %}
{% endfor %}
</ul>

Awards and Honors
======
- NMES International Studentship (2023 – 2027)
- Outstanding Graduate Student, Hefei University of Technology (2020)
- Merit Student, Hefei University of Technology (2018)

Invited Talks
======
- Meta, LLaMA Community Meet-up (Apr. 6, 2025): “[Towards Automatic Code Reproduction for Scientific Papers: Benchmarks and Methodologies]({{ '/talks/llama-community-meetup-2025' | relative_url }}).”

Competitions
======
- **National First Prize (Top 0.65%)**, China Undergraduate Mathematical Contest in Modelling (2018). Team-based modeling competition solving open-ended applied problems.
- **1st Place**, [Spider Leaderboard](https://yale-lily.github.io/spider) (2022). Our model G3R achieved the top rank on the “exact set match without values” metric.

Course Teaching
======
{% include course-teaching.html %}

Other Skills
======
- **IT:** C++, SQL, Python, LaTeX
- **Languages:** English (Fluent, IELTS 7.0), Chinese (Native)
