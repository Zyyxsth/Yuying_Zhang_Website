---
layout: archive
title: "个人简历"
permalink: /zh/cv/
author_profile: true
lang: zh
alternate_url: /cv/
---

教育经历
======

- **博士，专业名称**，某某大学，2023—至今
- **硕士，专业名称**，某某大学，2020—2023
- **学士，专业名称**，某某大学，2016—2020

工作与研究经历
======

- **职位或研究经历**，机构名称，年份
- **职位或研究经历**，机构名称，年份

研究方向
======

- 研究方向一
- 研究方向二
- 研究方向三

论文
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

学术报告
======

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
