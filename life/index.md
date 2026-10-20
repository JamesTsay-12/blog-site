---
layout: page
title: Life
permalink: /life/
---

<h2>Life Posts</h2>


##  Life

Hello, everyone!  I'm James - a scientist and who writes about philosophy and real life. 

In my blog about life — I explore:

Work, life, and hobby intersections
Changing life and health circumstances
International travel, living, and identity
Thoughts on the future

<ul>
  {% for post in site.categories.life %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%B %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>
