---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Professional Summary
======
My current research focuses on AI for Scientific Discovery and Agentic Coding within machine learning. I investigate approaches for reliable code reproduction from academic papers, efficient memory management, and tool use, as well as the generation of synthetic trajectories to enable supervised fine-tuning and reinforcement learning aimed at enhancing LLMs’ capabilities in complex research-oriented coding tasks.

Education
======
<ul class="education-list">
  <li>
    <div class="education-header">
      <span class="education-institution"><strong>King's College London</strong>, London, United Kingdom</span>
      <span class="education-dates">Sep. 2023 – Jun. 2027 (expected)</span>
    </div>
    <div class="education-degree">Ph.D. in Computer Science.</div>
    <div class="education-notes">Supervised by Prof. Yulan He with Dr. Lin Gui as co-advisor. Research topics: large language models, in-context learning, interpretability.</div>
  </li>
  <li>
    <div class="education-header">
      <span class="education-institution"><strong>Southeast University</strong>, Nanjing, China</span>
      <span class="education-dates">Sep. 2020 – Jun. 2023</span>
    </div>
    <div class="education-degree">M.S. in Software Engineering.</div>
    <div class="education-notes">Average score: 86.42/100. Supervised by Prof. Deyu Zhou with research on question answering and code generation.</div>
  </li>
  <li>
    <div class="education-header">
      <span class="education-institution"><strong>Hefei University of Technology</strong>, Hefei, China</span>
      <span class="education-dates">Sep. 2016 – Jun. 2020</span>
    </div>
    <div class="education-degree">B.E. in Computer Science and Technology.</div>
    <div class="education-notes">Average score: 90.10/100. Coursework highlights: linear algebra, advanced mathematics, probability theory, data structures, Java programming, software engineering, internet protocols.</div>
  </li>
</ul>

Awards and Honors
======
* NMES International Studentship (2023 – 2027)
* Outstanding Graduate Student, Hefei University of Technology (2020)
* Merit Student, Hefei University of Technology (2018)

Work Experience
======
* **Meta** — Contractor (Nov. 2025 – Dec. 2025)  \\
  Worked with Dr. Yoram Bachrach on AI Scientist agents, LLM-based systems that automate research workflows and machine learning engineering tasks.
* **AstraZeneca** — Internship (Jul. 2025 – Oct. 2025)  \\
  Supervised by Dr. Saseendran and Dr. Jin. Investigated generating multiple tokens per decoding step in Diffusion Language Models to accelerate decoding.

Invited Talks
======
* Meta, LLaMA Community Meet-up (Apr. 6, 2025): “Towards Automatic Code Reproduction for Scientific Papers: Benchmarks and Methodologies.”

Competitions
======
* National First Prize (Top 0.65%), China Undergraduate Mathematical Contest in Modelling (2018).
* 1st Place, Spider Leaderboard (2022). Model G3R ranked first on the “exact set match without values” metric and is currently fifth overall.

Publications
======
<ul class="publication-list">
{% assign publications = site.publications | sort: 'order' %}
{% for publication in publications %}
  {% assign post = publication %}
  {% include publication-list-item.html %}
{% endfor %}
</ul>
  
Talks
======
{% for talk in site.talks reversed %}
  {% assign post = talk %}
  {% include archive-single.html type='plain' %}
{% endfor %}
  
Teaching
======
{% for course in site.teaching reversed %}
  {% assign post = course %}
  {% include archive-single.html type='plain' %}
{% endfor %}
  
Other Skills
======
* **IT:** C++, SQL, Python, LaTeX
* **Languages:** English (Fluent, IELTS 7.0), Chinese (Native)
