---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I'm a PhD student in the [NLP group](https://kclnlp.github.io/) at King’s College London, working with [Prof. Yulan He](https://sites.google.com/view/yulanhe) and [Dr. Lin Gui](https://sites.google.com/view/lin-gui/about-me). You can reach me at [xyz1998seu@gmail.com](mailto:xyz1998seu@gmail.com).

Professional Summary
======
My current research centers on agentic coding in machine learning and artificial intelligence. I explore methods for reliable code reproduction from academic papers, effective memory management, tool utilization, and the creation of synthetic trajectories to perform supervised fine-tuning and reinforcement learning for improving large language model performance on complex coding tasks.

Experience
======
- **Meta** — Contractor (Nov. 2025 – Dec. 2025). Hired by Dr. Yoram Bachrach to develop AI Scientist agents: LLM systems that automate research tasks and machine learning engineering workflows.
- **AstraZeneca** — Internship (Jul. 2025 – Oct. 2025). Collaborated with Dr. Saseendran and Dr. Jin on generating multiple tokens per decoding step in Diffusion Language Models to accelerate decoding.

Education
======
<ul class="education-list">
  <li>
    <div class="education-header">
      <span class="education-institution"><strong>King's College London</strong></span>
      <span class="education-dates">Sep. 2023 – Jun. 2027 (expected)</span>
    </div>
    <div class="education-degree">Ph.D. in Computer Science.</div>
    <div class="education-notes">Supervised by Prof. Yulan He with Dr. Lin Gui as co-advisor. Focus areas: large language models, in-context learning, interpretability.</div>
  </li>
  <li>
    <div class="education-header">
      <span class="education-institution"><strong>Southeast University</strong></span>
      <span class="education-dates">Sep. 2020 – Jun. 2023</span>
    </div>
    <div class="education-degree">M.S. in Software Engineering.</div>
    <div class="education-notes">Supervised by Prof. Deyu Zhou with research on question answering and code generation.</div>
  </li>
  <li>
    <div class="education-header">
      <span class="education-institution"><strong>Hefei University of Technology</strong></span>
      <span class="education-dates">Sep. 2016 – Jun. 2020</span>
    </div>
    <div class="education-degree">B.E. in Computer Science and Technology.</div>
  </li>
</ul>

Awards and Honors
======
- NMES International Studentship (2023 – 2027)
- Outstanding Graduate Student, Hefei University of Technology (2020)

Invited Talks
======
- Meta, LLaMA Community Meet-up (Apr. 6, 2025): “Towards Automatic Code Reproduction for Scientific Papers: Benchmarks and Methodologies.” [[event post](https://www.linkedin.com/posts/yanzheng-xiang-9aa572282_ai-llm-agenticai-activity-7336720296193761281-yGy2/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAETIZhIBXh5XAI2i8HIYl-QGLzQlxhu0J98)]

Competitions
======
- **National First Prize (Top 0.65%)**, China Undergraduate Mathematical Contest in Modelling (2018). Team-based modeling competition solving open-ended applied problems.
- **1st Place**, [Spider Leaderboard](https://yale-lily.github.io/spider) (2022). Our model G3R achieved the top rank on the “exact set match without values” metric and is currently 5th overall.

Publications
======
<ul class="publication-list">
{% for publication in site.publications reversed %}
  {% assign post = publication %}
  {% include publication-list-item.html %}
{% endfor %}
</ul>
