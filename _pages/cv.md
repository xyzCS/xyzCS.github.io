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
My research focuses on agentic coding and large language models, including reliable code reproduction from academic papers, tool-augmented reasoning, memory management, and generating synthetic trajectories for supervised fine-tuning and reinforcement learning on complex coding tasks.

Education
======
* **King's College London**, Ph.D. in Computer Science (Sep. 2023 – Jun. 2027, expected)  \\
  Supervised by Prof. Yulan He with Dr. Lin Gui as co-advisor. Topics: large language models, in-context learning, interpretability.
* **Southeast University**, M.S. in Software Engineering (Sep. 2020 – Jun. 2023)  \\
  Average score: 86.42/100. Supervised by Prof. Deyu Zhou. Topics: question answering, code generation.
* **Hefei University of Technology**, B.E. in Computer Science and Technology (Sep. 2016 – Jun. 2020)  \\
  Average score: 90.10/100. Coursework highlights: linear algebra, advanced mathematics, probability theory, data structures, Java programming, software engineering, internet protocols.

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
{% for publication in site.publications reversed %}
  {% assign post = publication %}
  {% include archive-single.html type='plain' %}
{% endfor %}
  
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
