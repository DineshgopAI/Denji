---
layout: default
title: Denji
---

# Denji

*Raw thoughts. Unfiltered.*

---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}" class="post-title">{{ post.title }}</a>
      <span class="post-meta">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
