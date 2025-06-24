---
layout: page
title: Art
permalink: /art/
---

## 🎨 Art

Welcome to the art section of my blog. Here I share thoughts and artworks.
Feel free to browse recent posts or curated works.

---

{% assign art_posts = site.categories.art | sort: 'date' | reverse %}
{% for post in art_posts %}
- [{{ post.title }}]({{ post.url }}) <span style="color:#888;">{{ post.date | date: "%b %d, %Y" }}</span>
{% endfor %}

---

If you're interested in collaborating or showcasing your work, [get in touch](/contact/).
