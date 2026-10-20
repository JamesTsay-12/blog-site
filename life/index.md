---
layout: page
title: Life
permalink: /life/
---

<h2>Life Posts</h2>

<ul>
  {% for post in site.categories.life %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%B %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>
