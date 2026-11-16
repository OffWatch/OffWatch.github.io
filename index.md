---
layout: default
---
# {{ site.title }}

Merchant mariner (Chief Mate / Master track) learning C++, systems programming, and ML inference.

---

## Projects

- *Coming soon — C++ systems &amp; ML projects will be linked here.*

## Posts

<ul>
{% for post in site.posts %}
  <li><span class="meta">{{ post.date | date: "%Y-%m-%d" }}</span> — <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
