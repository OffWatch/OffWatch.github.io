---
layout: default
---
# OffWatch

Mariner learning C++, systems programming, and ML inference.

---

## Projects

- Started 06/11/2026 Currently learning basics of C++ from learncpp.com. 

## Posts

<ul>
{% for post in site.posts %}
  <li><span class="meta">{{ post.date | date: "%Y-%m-%d" }}</span> — <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
