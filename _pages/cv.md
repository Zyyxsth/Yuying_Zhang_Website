---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
lang: en
alternate_url: /zh/cv/
redirect_from:
  - /resume
---

Education
======

- **Ph.D. in Your Field**, University Name, 2023–Present
- **M.Sc. in Your Field**, University Name, 2020–2023
- **B.Sc. in Your Field**, University Name, 2016–2020

Research and professional experience
======

- **Position or research experience**, Institution Name, Year
- **Position or research experience**, Institution Name, Year

Research interests
======

- Research direction one
- Research direction two
- Research direction three

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks
======

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
