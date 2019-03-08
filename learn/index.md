---
title: Learn about charging and the "Hostile Environment"
layout: page
---

Everything you need to know about the governments charging policy and how it fits into their wider "Hostile Environment".

<ul>
  {% for p in site.pages %}
    {% if p.name != 'index.md' and p.dir == '/learn/' %}
      <li><a href="{{ p.url }}">{{ p.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
