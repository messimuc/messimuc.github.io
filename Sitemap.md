---
layout: page
title: Sitemap
permalink: /Sitemap/
---

<ul>
{% for page in site.pages %}
<li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %} <!-- page -->
</ul>