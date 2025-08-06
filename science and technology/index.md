---
layout: page
title: Science
permalink: /Science/
---

Welcome to my Science and Technology blog!

I'm a scientist in the biotech industry and I'm here to discuss some of the latest advances in science and impact on our lives.

You can find me on Linkedin **🔗 [LinkedIn Profile](https://www.linkedin.com/in/james-tsay-b2700a19/)**
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
