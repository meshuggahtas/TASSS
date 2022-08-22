---
# example 404.md

layout: default
permalink: /404.html
---

<ul>
  {% assign mypages = site.pages | sort: "order" %}
    {% for page in mypages %}
    <li><a href="{{ page.url | absolute_url }}">{{ page.title }}</a></li>
    {% endfor %}
</ul>

<br>
<b>{% file.name %}</b>

Custom 404 error
