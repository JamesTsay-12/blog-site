---
layout: page
title: Art
permalink: /art/
---

## 🎨 Art

Welcome to the art section of my blog. Here I share thoughts and artworks.
Feel free to browse recent posts or curated works.

---

{% assign art_posts = site.categories.art %}

{% if art_posts %}
  {% assign sorted_art_posts = art_posts | sort: 'date' | reverse %}
  <ul>
  {% for post in sorted_art_posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <span style="color:#888;">{{ post.date | date: "%b %d, %Y" }}</span>
    </li>
  {% endfor %}
  </ul>
{% else %}
  <p><em>No art posts found yet. Stay tuned!</em></p>
{% endif %}



---

If you're interested in collaborating or showcasing your work, [get in touch](/contact/).
