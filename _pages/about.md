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

My research is focused on Large Language Models (LLMs) and AI Agents. I am passionate about exploring the application of these technologies to solve complex problems and build innovative systems.


<h2>News</h2>
<ul>
  <li><strong>Jan 2026</strong> – One paper accepted by ICLR 2026.</li>
  <!-- <li><strong>Month Year</strong> – Another short update.</li> -->
</ul>

<h2>Education</h2>
<ul>
  <li><strong>M.S. in Computational Science and Engineering</strong>, Georgia Institute of Technology, Aug 2025 – present.</li>
  <li><strong>B.S. in XXX</strong>, Wuhan University, Sep 2021 – Jun 2025.</li>
</ul>


<h2>Publications</h2>

{% include base_path %}

<!-- Render publications on the home page using the same logic as the publications page -->
{% if site.publication_category %}
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
{% endif %}

