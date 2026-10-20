---
layout: page
title: Life
permalink: /life/
---

<h2>Life Posts</h2>


Hello, everyone!  I'm James - a scientist and dabbler who writes blogs about random life observations and practical experiences which I hope benefit people. 

In my blog about life — I explore:

- Work, life, and hobby intersections
- Navigating changing life and health circumstances
- International travel, living, and identity
- Thoughts on the future

I'm tying other relevant blogs to this page for context.



<ul>
  {% for post in site.categories.life %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%B %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>
