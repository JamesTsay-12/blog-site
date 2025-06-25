---
layout: page
title: Music
permalink: /music/
---

Welcome to my music blog! 🎵

Here I'll share:

- Songs I'm working on
- Favorite tracks
- Music production notes
- Instruments and gear I use

---

### 🎧 Listen on SoundCloud

<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay"
  src="https://w.soundcloud.com/player/?url=https%3A//soundcloud.com/james-tsay-857457878&color=%23ff5500&inverse=false&auto_play=false&show_user=true">
</iframe>

---

### 🎧 Blog Posts

{% assign music_posts = site.categories.music %}

{% if music_posts %}
  {% assign sorted_music_posts = music_posts | sort: 'date' | reverse %}
  {% for post in sorted_music_posts %}
  - [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) <span style="color:#888;">{{ post.date | date: "%b %d, %Y" }}</span>
  {% endfor %}
{% else %}
  _No music posts found yet. Stay tuned!_
{% endif %}

Stay tuned for posts tagged with `music`!





