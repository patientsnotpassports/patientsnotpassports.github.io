---
title: Learn about charging and the "Hostile Environment"
layout: page
---

Everything you need to know about the governments charging policy and how it fits into their wider "Hostile Environment".

<ul>
  {% assign pages = site.pages | where: "dir", "/learn/" | where_exp: "item", "item.name != 'index.md'" | sort: "ordinal" %}
  {% for p in pages %}
    <li><a href="{{ p.url }}">{{ p.title }}</a></li>
  {% endfor %}
</ul>
