---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am Patrick Neumann, a researcher in the area of symmetric cryptography. I am currently a Post-Doc at Inria (Paris), where I am working on the cryptanalysis of symmetric ciphers.

Publications
------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}</ul>
  
Talks
------
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk.html  %}
  {% endfor %}</ul>

Work History
------
* 2025 - Now: Inria, Paris, France
* 2020 - 2025: Ruhr University Bochum, Bochum, Germany

