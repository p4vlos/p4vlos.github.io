---
layout: default
title: Writing
---

# Writing

<ul class="pubs">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="year">— {{ post.date | date: "%B %Y" }}</span>
  </li>
{% endfor %}
</ul>

<p><a href="{{ '/' | relative_url }}">← back home</a></p>
