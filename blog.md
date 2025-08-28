---
layout: default
title: Blog
permalink: /blog/
description: "All Articles"
---

<ul>
  {% for post in site.posts %}
    <li style="margin-bottom:8px;">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%b %d, %Y" }}</small><br/>
      {% if post.excerpt %}
        <span style="color:#9aa0a6;">{{ post.excerpt | strip_html | truncate: 160 }}</span>
      {% endif %}
    </li>
  {% endfor %}
</ul>
