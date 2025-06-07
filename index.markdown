---
layout: default
title: Inicio
---

[Inicio]({{ "/" | relative_url }}) | [Acerca de]({{ "/about/" | relative_url }})

---

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
