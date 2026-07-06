---
permalink: /
title: "Lucheng Fu's Personal Page"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello there! My name is Lucheng Fu.

I am a Master's student in Computational Science and Engineering at the Georgia Institute of Technology.

My research is focused on Large Language Models, Prompt Optimization, Robust Machine Learning, and Multi-Agent Systems. I am passionate about exploring the application of these technologies to solve complex problems and build innovative systems.


<h2><i class="fas fa-newspaper" aria-hidden="true"></i> News</h2>
<ul>
  <li><strong>Jan 2026</strong> – One paper accepted by ICLR 2026.</li>
  <!-- <li><strong>Month Year</strong> – Another short update.</li> -->
</ul>

<h2><i class="fas fa-graduation-cap" aria-hidden="true"></i> Education</h2>
<ul>
  <li><strong>M.S. in Computational Science and Engineering</strong>, Georgia Institute of Technology, Aug 2025 – present.</li>
  <li><strong>B.S. in Computer Science</strong>, Wuhan University, Sep 2021 – Jun 2025.</li>
</ul>


<h2><i class="fas fa-book-open" aria-hidden="true"></i> Publications</h2>

<p>Guancheng Wan*, <strong>Lucheng Fu*</strong>, Haoxin Liu, Yiqiao Jin, Hui Yi Leong, Eric Hanchen Jiang, Hejia Geng, Jinhe Bi, Yunpu Ma, Xiangru Tang†, B. Aditya Prakash†, Yizhou Sun†, Wei Wang†. Beyond Magic Words: Sharpness-Aware Prompt Evolving for Robust Large Language Models with TARE. ICLR 2026 (<a href="https://arxiv.org/abs/2509.24130">Paper</a>) (<a href="https://github.com/GuanchengWan/TARE">Code</a>)</p>

<p><strong>Lucheng Fu</strong>, Ye Yu, Yiyang Wang, Yiqiao Jin, Haibo Jin, B. Aditya Prakash, Haohan Wang. TextReg: Mitigating Prompt Distributional Overfitting via Regularized Text-Space Optimization. arXiv preprint 2026 (<a href="https://arxiv.org/abs/2605.21318">Paper</a>) (<a href="https://github.com/luchengfu6/TextReg">Code</a>) (<a href="https://textreg.github.io/">Website</a>)</p>

<p>Yiqiao Jin, Yiyang Wang, <strong>Lucheng Fu</strong>, Yijia Xiao, Yinyi Luo, Haoxin Liu, B. Aditya Prakash, Josiah Hester, Jindong Wang, Srijan Kumar. UniSD: Towards a Unified Self-Distillation Framework for Large Language Models. arXiv preprint 2026 (<a href="https://arxiv.org/abs/2605.06597">Paper</a>) (<a href="https://github.com/Ahren09/UniSD">Code</a>) (<a href="https://unifiedsd.github.io/">Website</a>)</p>

<p>Jiaming Qu, <strong>Lucheng Fu</strong>, Yibo Hu. Easier to Mislead Than to Correct: Harmful and Beneficial Revision in LLM Conformity. arXiv preprint 2026 (<a href="https://arxiv.org/abs/2606.01637">Paper</a>) (<a href="https://github.com/yibo-hu-lab/Easier-to-Mislead-Than-to-Correct">Code</a>)</p>

{% include base_path %}

<!-- Render publications on the home page using the same logic as the publications page -->
<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h3>{{ category[1].title }}</h3><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} -->

