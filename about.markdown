---
layout: page
title: About
permalink: /about/
---

{%- include youtube_frame.html  youtube_id= "tnwFVcm8A_8" -%}


-----------collections --------------------
{{ site.staff_members.Jane }}
{% for staff_member in site.staff_members %}
asdfasd
<h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
<p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
-------------------------------
This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)



You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll

