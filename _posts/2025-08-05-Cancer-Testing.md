---
layout: post
title: "Cancer Testing and Drugs, Where are we today?"
date: 2025-08-05
categories: Science
---

This post is in progress.  I'll dive into my family's current journey navigating the health system, cancer, and the utilization of the latest available technology from biotech.

### 📚 Recent Posts

{% assign Science_posts = site.categories.Science %}

{% if Science_posts %}
  {% assign sorted_Science_posts = Science_posts | sort: 'date' | reverse %}
  {% for post in sorted_Science_posts %}
  - [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) <span style="color:#888;">{{ post.date | date: "%b %d, %Y" }}</span>
  {% endfor %}
{% else %}
  _No Science posts published yet — stay tuned!_
{% endif %}
